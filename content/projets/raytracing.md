---
title: Ray Tracer CPU
date: '2025-01-04T18:13:27.758Z'
draft: false
image: '/projets/images/raytracing.png'
summary: "Ray Tracer - C++"
---

**Lancer de Rayons** is a **CPU-based ray tracing engine**.\
The goal of this project was to implement a complete **ray tracing renderer** from scratch in **C++**, progressively building all the essential components of a physically inspired rendering pipeline.

The project was divided into four major phases, each introducing new rendering features and optimizations:

**Phase 1 – Ray Casting & Geometry**

Implementation of the fundamental ray tracing functions:
- **Ray-sphere** and **ray-square intersections**
- Scene traversal and nearest-hit detection
- Basic material color rendering within a Cornell Box

**Phase 2 – Illumination & Shadows**

Introduction of the **Phong lighting model**, combining **ambient**, **diffuse**, and **specular** reflections.\
Added **hard shadows** via shadow rays and **soft shadows** using **multi-ray sampling** of area lights to achieve realistic shading gradients.

**Phase 3 – Meshes & Reflections**

Support for **triangle mesh loading** (e.g., Suzanne.off) and **interpolated texture coordinates** for advanced rendering.\
Implementation of **mirror reflection** and **recursive ray tracing**, enabling **reflective materials** and multi-bounce light simulation.

**Phase 4 – Refraction & Acceleration Structures**

Integration of **transparent** materials using Snell’s Law for light refraction.\
Development of a full **Kd-Tree spatial acceleration structure**, drastically improving mesh rendering performance by reducing intersection computations.

**Final Enhancements**

Added **texture mapping** for both planar and spherical surfaces, allowing **UV-based color sampling** from `.ppm`images.\
The final renderer can display **realistic Cornell Box** scenes with **textured walls**, **reflective spheres**, and **refractive glass objects** — all computed via pure ray tracing.

Link to the project :
- ![GitHub](https://github.com/RTheoGH/RayTracing_CPU)