---
title: Photo Mosaic
date: '2025-04-18T18:13:27.758Z'
draft: false
image: '/projets/images/mosaique.png'
summary: "Image Processing - C++"
---

**Photo Mosaic** is an image processing project.\
The goal of the project was to reconstruct a target image using a set of smaller images — known as imagettes — to create a visual mosaic.

The work explores and compares several image similarity methods to optimize both visual quality and computation time.

Three main approaches were implemented and analyzed:
- **Block averaging**: a fast but imprecise method, assigning each tile the image with the closest average color.
- **Histogram comparison (Bhattacharyya distance)**: a more accurate technique that improves visual resemblance at the cost of higher computation time.
- **Histogram specification**: a hybrid approach combining the efficiency of averaging with the perceptual accuracy of histogram matching.

Each method was evaluated using **PSNR** (Peak Signal-to-Noise Ratio) and execution time to measure performance and visual fidelity.
A graphical interface was also created to display results and allow interactive testing with different block sizes and image datasets.

Link to the project :
- [GitHub](https://github.com/RTheoGH/projet_image)