---
title: Denoiser CNN
date: '2025-12-10T18:13:27.758Z'
draft: false
image: '/projets/images/noise.png'
tags: ["Research", "Python", "Pytorch", "Machine Learning", "Image Processing"]
summary: "Denoiser CNN - Python/Pytorch"
---

This project aims to denoise images using a convolutional neural network (CNN). It notably incorporates an encoder, a decoder, and a GAN to produce denoised images.

Noise type | Base | Result
:-------------------------:|:-------------------------:|:-------------------------:
Gaussian | ![png1](/projets/images/denoiser/image04312_input.png "screen1") | ![png2](/projets/images/denoiser/image04312_pred.png "screen2")
Salt & Pepper | ![png3](/projets/images/denoiser/image04583_input.png "screen3")  |  ![png4](/projets/images/denoiser/image04583_pred.png "screen4")
Poisson | ![png3](/projets/images/denoiser/image04597_input.png "screen5")  |  ![png4](/projets/images/denoiser/image04597_pred.png "screen6")
Periodic | ![png3](/projets/images/denoiser/image04629_input.png "screen7")  |  ![png4](/projets/images/denoiser/image04629_pred.png "screen8")

Link to the project :
- [GitHub](https://github.com/RTheoGH/Projet_debruitage) : Source code