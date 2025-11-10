---
title: Blocks World VR
date: '2025-10-14T18:13:27.758Z'
draft: false
image: '/projets/images/devilgr.png'
summary: "Advanced Agents - Godot"
---

**Block World VR** is an experimental **virtual reality project**.\
The project explores the integration of **agent-based reasoning** with **real-time 3D interaction** in a **VR environment** built using **Godot Engine** and **GodotXRTools**.

At its core, Block World VR simulates a simple world of **3D agents** — each defined by attributes such as position, rotation, and scale — capable of performing **data-driven** actions.
These actions are represented as modular data structures controlling transformations, enabling the creation of **state trees** to explore possible sequences of moves from an initial configuration to a desired final state.

The team implemented:
- A **data-driven action system**, separating logic from data for easier experimentation.
- A **state tree search algorithm**, using a geometric heuristic (Euclidean distance) to optimize the path between configurations — with the potential for extension to **A\*** algorithms.
- A **VR interface**, allowing users to manipulate objects directly through **motion controllers**, observe agent actions, and visualize state transitions in real time.

Link to the project :
- [GitHub](https://github.com/VigKillian/BlockWorld)