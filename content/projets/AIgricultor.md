---
title: AIgricultor
date: '2024-11-21T18:13:27.758Z'
draft: false
image: '/projets/images/music_mouton.gif'
summary: "Agent Game - Godot"
---

**AIgricultor** is an **agent-based simulation** game developed in **Godot**.\
The project explores **autonomous behavior modeling** through **interacting intelligent agents**, each governed by perception, decision, and action cycles.

The simulation depicts a playful ecosystem where dogs and sheep coexist within a dynamic environment.
Each agent is driven by an internal Brain class — a finite state machine controlling its behavior based on local perception, global information, and spatial awareness.

**Core Concepts**
- Agent Paradigm: Each entity perceives its environment, interprets events, and reacts through defined actions.
- Three-tiered information model:
    - Local information → agent’s internal state and events
    - Global information → shared world data via a GameMaster class
    - Spatial information → sensory input from the environment
- Action system: Defined as dictionaries of name–lambda pairs, enabling modular and flexible behavior definitions.

**Agent Examples**
- **Dog agent**:\
    `run(d) ∧ see(s) ⇒ bark(d,s)`\
    `bark(d,s) ∧ ¬see(s) ⇒ run(d)`\
    → Patrols the environment and reacts to nearby sheep.

- **Sheep agent**:\
    `graze(s) ∧ exit(s) ⇒ runaway(s)`\
    `runaway(s) ∧ getBarked(s,d) ⇒ comeback(s)`\
    `comeback(s) ∧ enter(s) ⇒ graze(s)`\
    → Alternates between grazing, fleeing, and returning based on dog behavior.

Links to the project :
- [ITCH](https://ohhnyx.itch.io/aigricultor) : Game page
- [GitHub](https://github.com/VigKillian/AIgricultor) : Source code