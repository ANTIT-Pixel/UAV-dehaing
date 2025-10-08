# UAV-Dehazing: Real-time Dehazing for UAV Videos

[![Paper](https://img.shields.io/badge/Paper-PDF-informational)](#)
[![Project Page](https://img.shields.io/badge/Project-Website-blue)](https://antit-pixel.github.io/-UAV-Dehazing/)
[![Dataset](https://img.shields.io/badge/Dataset-Download-success)](#dataset)
[![Demo Video](https://img.shields.io/badge/Video-YouTube-red)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **TL;DR** We propose a lightweight UAV-oriented dehazing method that runs in real time and is friendly for on-device deployment. Code, data, and training scripts are provided.

<p align="center">
  <img src="assets/teaser.jpg" width="90%" alt="UAV Dehazing teaser"/>
</p>

## ✨ Highlights
- **UAV-specific robustness** to high altitude, fast motion, and atmospheric scattering.
- **Real-time**: **XX FPS** on **Your GPU/Device**.
- **Efficient**: **X.XM** params, **XX GFLOPs**.
- **Reproducible**: training scripts + pretrained weights.

## 📦 Environment
```bash
conda create -n uavdehaze python=3.10 -y
conda activate uavdehaze
pip install -r requirements.txt
