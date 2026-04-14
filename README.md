# Deep Learning Experiments: CNNs, Vision Transformers, and Framework Comparison

Collection of deep learning experiments exploring image classification, transfer learning, Vision Transformers, and differences between PyTorch and Keras workflows.

## Overview

This repository groups multiple experiments into a single structured project to demonstrate progression from baseline models to more advanced architectures.

The goal is not to showcase isolated notebooks, but to highlight understanding of:
- model training pipelines
- architectural differences (CNN vs ViT)
- framework trade-offs (Keras vs PyTorch)
- evaluation and performance comparison

---

## Experiments

### 1. CNN Image Classification (Anime Dataset)
- Built a convolutional neural network for multi-class image classification
- Demonstrates end-to-end pipeline: preprocessing → training → evaluation

---

### 2. FashionMNIST Baseline
- Implemented baseline classification model
- Used as a controlled environment for testing architectures

---

### 3. Waste Classification (Transfer Learning)
- Applied transfer learning using pretrained CNN models
- Shows ability to adapt models to real-world datasets with limited data

---

### 4. Vision Transformers (ViT)
- Implemented in both:
  - Keras
  - PyTorch
- Demonstrates understanding of modern architectures beyond CNNs

---

### 5. CNN + ViT Hybrid Model
- Combined convolutional and transformer-based approaches
- Explores architectural integration and performance impact

---

### 6. Keras vs PyTorch Comparison
- Compared training workflows and performance
- Highlights differences in:
  - flexibility
  - control
  - implementation complexity

---

## Key Skills Demonstrated

- Deep learning model development
- Transfer learning
- CNN and Vision Transformer architectures
- PyTorch and Keras workflows
- Model evaluation and comparison
- Data preprocessing and augmentation

---

## Structure
```text
deep-learning-experiments/
├── README.md
├── notebooks/
│ ├── anime_cnn_classifier.ipynb
│ ├── fashion_mnist_baseline.ipynb
│ ├── waste_classification_transfer_learning.ipynb
│ ├── vit_keras.ipynb
│ ├── vit_pytorch.ipynb
│ ├── cnn_vit_hybrid.ipynb
│ ├── keras_vs_pytorch_comparison.ipynb
```
---

## Notes

These experiments are intentionally grouped into a single repository to present a coherent progression rather than isolated course exercises.
