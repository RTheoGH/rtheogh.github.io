---
title: MAIge Academy
date: '2024-12-16T18:13:27.758Z'
draft: false
image: '/projets/images/transformgif.gif'
summary: "Agent Game - Godot"
---

**MAIge Academy** is an **AI-driven simulation game** developed in **Godot 4.3**.\
The project was created for the **Multi-Agent Systems** course and focuses on designing intelligent agents with dynamic behaviors, interacting within an asynchronous, rule-based environment.

Set in a magical academy, players observe and analyze the interactions between two types of agents : **Teachers** and **Students**. Each governed by distinct sets of goals and behaviors.
Teachers can **cast spells** such as Freeze, Transform, or Teleport to influence students, while students attempt to **collect candies**, avoid **teacher**, and **return safely** to their base.

The simulation operates using a hybrid time system:
- Three **update loops** run in parallel: rendering, physics/pathfinding, and agent logic.
- Agents update **synchronously** at a fixed frequency but interact **asynchronously** via **event-based communication**.
- Goals and actions are defined using **lambda functions** for dynamic validation and flexible rule definition.
- Student behavior is implemented through **strategy subclasses**, allowing polymorphic and easily extendable AI.

Several **student strategies** were implemented and compared:
- Naïve
- CandyByTime
- LoneWolf
- TwoByTwoEscapeTeacher

The simulation highlights how agent design and goal structures affect collective outcomes, making **MAIge Academy** both a research-oriented and playful exploration of **agent-based AI**.

Links to the project :
- [ITCH](https://ohhnyx.itch.io/maige-academy) : Game page
- [GitHub](https://github.com/binaryHips/MAIgeAcademy) : Source code