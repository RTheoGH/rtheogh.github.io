---
title: Magie VR
date: '2026-01-18T10:13:27.758Z'
draft: false
image: '/projets/images/vr_img.png'
summary: "VR Game - Godot"
---

**Maige VR** is a virtual reality game project developed with **Godot Engine**.\
The goal of the project was to let the player embody a mage in a medieval fantasy world, casting spells through natural, embodied interactions rather than simple button presses.

The work explores and compares three different spell-casting input methods to determine which interaction paradigm feels most intuitive and effective for players.

Three main spell-casting systems were implemented and analyzed:
- **Magic Wand**: gesture-based casting, where the player performs specific motions with a wand controller inside a summoned magic circle to trigger a spell.
- **Enchanted Quill**: rune-drawing on interactive surfaces, using the **$Q gesture recognition algorithm**, which converts 3D drawn strokes into 2D point clouds for shape detection.
- **Spellbook**: voice-based casting, using **Godot Whisper** for real-time speech recognition to convert spoken spell names into in-game actions.

Each method was evaluated through an integrated **analytics system**: an initial questionnaire captured player profile data (age, gender, gaming/VR familiarity), while in-game performance data was logged in real time via **DuckDB** to compare accuracy, speed, and player preference across the three methods.

The project was built in **Godot Engine** with VR support, using **Godot XRTools** for VR interactions and locomotion (joystick movement, object grabbing, teleportation), alongside the **Multistroke Gesture Recognizer** for shape detection.

![png1](/projets/images/mvr/mvr1.png "screen1")  |  ![png2](/projets/images/mvr/mvr2.png "screen2")
:-------------------------:|:-------------------------:
![png3](/projets/images/mvr/mvr3.png "screen3")  |  ![png4](/projets/images/mvr/mvr4.png "screen4")

Links to the project :
- [GitHub](https://github.com/RTheoGH/Projet_VR) : Source code