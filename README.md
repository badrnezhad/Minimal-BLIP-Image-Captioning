# Image Captioning with BLIP (Kaggle + PyTorch)

This project demonstrates a minimal and practical implementation of **image captioning** using a pretrained BLIP model. The code is designed to be simple, readable, and directly runnable in a Kaggle notebook environment.

---

## Overview

The model takes an input image and generates a natural language description (caption) of its content.

- Model: `Salesforce/blip-image-captioning-base`
- Framework: PyTorch
- Environment: Kaggle (GPU supported)

---

## Features

- Uses a **pretrained model** (no training required)
- Supports **single image captioning**
- Can load images from:
  - Local Kaggle dataset (`/kaggle/input`)
  - External sources (e.g., GitHub raw URLs)
- Minimal and clean implementation

