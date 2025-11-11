---
title: Gomoku
date: '2025-05-31T18:13:27.758Z'
draft: false
image: '/projets/images/gomoku.png'
summary: "Mobile Game - Kotlin"
---

**Gomoku** is an Android application developed in **Kotlin** using **Jetpack Compose** and **Firebase**.
The project aims to recreate the classic board game Gomoku — also known as “Five in a Row” — in a modern, connected, and user-friendly mobile format.

This project focuses on both **gameplay design** and **mobile development architecture**, combining real-time multiplayer features, AI opponents, and user account management.

The app allows players to:
- Play **offline**, either 1 vs 1 locally or against an AI with three levels of difficulty (easy, medium, hard).
- Play **online**, with matchmaking, ranked games, Blitz mode (timed), and asynchronous games that can be resumed later.
- Manage **profiles**, **friends**, and **leaderboards**, using **Firebase Authentication**, **Firestore**, and **Realtime Database** for cloud synchronization.
- Receive **notifications** for invitations, friend requests, or game updates through a custom background service.

The project emphasizes a **clean**, **intuitive interface** thanks to Jetpack Compose, with features such as internationalization (English/French), customizable profile pictures, and smooth navigation between screens.

<p align="center">
  <img src="/projets/images/gomoku/partie_hors_ligne.png" alt="screen1" width="23%"/>
  <img src="/projets/images/gomoku/historique.png" alt="screen2" width="23%"/>
  <img src="/projets/images/gomoku/leaderboard.png" alt="screen3" width="23%"/>
  <img src="/projets/images/gomoku/blitz.png" alt="screen4" width="23%"/>
</p>

Link to the project :
- [GitHub](https://github.com/RTheoGH/Gomoku_mobile)