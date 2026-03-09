# Simple Binary Classification of Cloud Images

This repository contains a PyTorch implementation for **binary classification of cloud images**.  
The project explores deep learning models for classifying images into two categories using both **CNN-based architectures (ResNet)** and **Transformer-based architectures (Vision Transformer, ViT)**.

The implementation is designed for research and experimentation with different backbone networks for image classification tasks.

---

## Features

- Binary image classification using deep learning
- Supports **ResNet50** backbone
- Supports **Vision Transformer (ViT)** backbone
- Implemented with **PyTorch**
- Modular code structure for experimentation

---

## Model Backbones

### ResNet

The ResNet implementation is adapted from the official PyTorch implementation:

https://github.com/pytorch/vision

Supported model:
- ResNet50

---

### Vision Transformer (ViT)

The Vision Transformer implementation is adapted from the **timm** library:

https://github.com/rwightman/pytorch-image-models

Supported variants include:

- vit_tiny_patch16_224
- vit_small_patch16_224
- vit_base_patch16_224
- vit_large_patch16_224
Pretrained weights are loaded from the timm model repository.

---

# Requirements:
-Python 3.9+
-torch==2.0.1+cu128
-torchvision==0.23.0+cu128
-timm==0.9.12
-numpy==1.21.5
-scikit-learn==1.0.2
-Pillow==9.2.0
-matplotlib==3.5.2
