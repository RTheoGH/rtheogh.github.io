---
title: DogGO
date: '2025-04-13T18:13:27.758Z'
draft: false
image: '/projets/images/doggooo.png'
summary: "Exploration algorithm - Godot"
---

**DogGO** is a strategic board game simulation based on the traditional **Game of Go**.\
The goal of the project was to design a playable digital version of Go, complete with an AI opponent capable of making decisions through **Monte Carlo simulations**.

The project implements all the fundamental mechanics of the Go board (goban):
- Representation of the grid as a **graph**, where each intersection is a node connected to its neighbors (Von Neumann adjacency).
- Detection of **groups of stones** and computation of their **degrees of freedom** (liberties).
- Implementation of **capture rules**, **valid move conditions**, and **end-of-game detection** based on player passes or full board states.

For the artificial intelligence, several classic algorithms were explored before settling on a **Monte Carlo–based approach**, which simulates thousands of random games to statistically determine the best moves.
Each move is evaluated according to tactical criteria such as territory control, defense reinforcement, and capture potential, producing a balanced and adaptive **AI opponent**.

The game includes a **graphical interface** with menus for setup, gameplay, and AI mode selection. Players can challenge another human or face off against the algorithm in increasingly difficult matches.

Links to the projects :
- [ITCH](https://ohhnyx.itch.io/doggo) : Game page
- [GitHub](https://github.com/RTheoGH/doggo) : Source code