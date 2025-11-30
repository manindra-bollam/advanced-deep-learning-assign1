# Feature Extraction and Dimensionality Reduction via Autoencoders

This repository contains the implementation of various feature extraction and dimensionality reduction techniques using **Principal Component Analysis (PCA)** and different variants of **Autoencoders**. The project uses the **CIFAR-10** (converted to grayscale) and **MNIST** datasets to explore latent space representations, reconstruction errors, and classification performance.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Prerequisites](#prerequisites)
- [Task Breakdown](#task-breakdown)
  - [Task 1: PCA & Logistic Regression](#task-1-pca--logistic-regression)
  - [Task 2: Linear Autoencoder vs. PCA](#task-2-linear-autoencoder-vs-pca)
  - [Task 3: Deep Convolutional vs. Shallow Autoencoders](#task-3-deep-convolutional-vs-shallow-autoencoders)
  - [Task 4: MNIST 7-Segment Display Classification](#task-4-mnist-7-segment-display-classification)
- [File Structure](#file-structure)
- [Results & Observations](#results--observations)

## 🔍 Project Overview
The primary goal of this assignment is to compare classical dimensionality reduction (PCA) with neural network-based approaches (Autoencoders). We analyze how well these methods capture essential features for both image reconstruction and downstream classification tasks.

## 💾 Datasets
1.  **CIFAR-10**:
    * Converted to **Grayscale**.
    * Split: **70% Training**, **30% Validation/Test**.
    * Used for Tasks 1, 2, and 3.
2.  **MNIST**:
    * Used for Task 4 (Deep Convolutional Autoencoder for feature extraction).

## 🛠 Prerequisites
The project is implemented in Python using the following libraries:
* `tensorflow` / `keras`
* `numpy`
* `scikit-learn`
* `matplotlib`
* `seaborn` (for confusion matrix visualization)

To install dependencies:
```bash
pip install tensorflow numpy scikit-learn matplotlib seaborn
