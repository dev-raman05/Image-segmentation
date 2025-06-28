# PyTorch Image Segmentation

This repository demonstrates how to train a semantic segmentation model (U‑Net) on a custom image↔mask dataset using PyTorch, Albumentations, and [`segmentation_models_pytorch`](https://github.com/qubvel/segmentation_models.pytorch).

## 🚀 Features

- **Custom `Dataset`**: Loads paired images and masks.
- **Albumentations Augmentations**: Synchronized transforms for images & masks.
- **Visualization**: Quick plotting utility for sanity checks.
- **Pretrained U‑Net**: Uses ImageNet‑pretrained encoder (`resnet34` by default).
- **Training & Eval Loops**: Modular `train_epoch` and `evaluate` functions.
- **Checkpointing**: Saves best model by validation loss.

