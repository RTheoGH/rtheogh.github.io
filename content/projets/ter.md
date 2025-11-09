---
title: Ocean Synthesis
date: '2025-06-02T18:13:27.758Z'
draft: false
image: '/projets/images/ter.png'
summary: "Research project - Godot"
---

**Ocean Synthesis** is a research and development project focused on realistic ocean simulation using the open-source game engine **Godot**.\
The project explores advanced rendering techniques to improve the visual realism of virtual oceans while maintaining real-time performance.

This project implements the **tiling and blending** method proposed by Lutz et al. (2024) — a modern approach that eliminates the repetitive patterns typical of classic ocean models like **Tessendorf’s algorithm**.

Using **compute shaders** in Godot 4, the team integrated several advanced rendering techniques:
- **Tiling and blending**, to generate a non-periodic, natural-looking ocean surface.
- **Flow map–based wave orientation**, to simulate directional currents and wind influence.
- **LEAN Mapping**, to produce more realistic specular highlights and reflections at different viewing distances.

Link to the project :
- [GitHub](https://github.com/RTheoGH/TER-Ocean)