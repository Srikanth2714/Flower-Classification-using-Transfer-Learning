# 🌸 Flower Classification using Transfer Learning (VGG16 + PyTorch)

<div align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-PyTorch-red" />
  <img src="https://img.shields.io/badge/Model-VGG16-blueviolet" />
  <img src="https://img.shields.io/badge/Accuracy-86%25-brightgreen" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen" />
</div>

---

## 📌 Project Overview

This project demonstrates the application of **transfer learning** using a pretrained **VGG16** model to classify images of flowers into distinct categories. Built with **PyTorch**, this end-to-end pipeline includes data preprocessing, augmentation, model fine-tuning, and performance evaluation — achieving **86% accuracy** on the test dataset.

---

## 📂 Dataset

- **Source:** [Kaggle - PyTorch Challenge Flower Dataset](https://www.kaggle.com/datasets/nunenuh/pytorch-challange-flower-dataset)
- **Classes:** Multiple flower species
- **Structure:** Image files organized by class folders
- **Split:** Train, Validation, Test folders

---

## 🧠 Model Architecture

- **Backbone:** `VGG16` pretrained on ImageNet
- **Custom Head:** Final fully connected layers replaced to match dataset classes
- **Loss Function:** CrossEntropyLoss
- **Optimizer:** Adam
- **Epochs:** 10+
- **Hardware:** Trained using GPU (if available)

---

## 🔧 Features & Techniques

- ✅ Transfer Learning (VGG16 with Frozen Conv Layers)
- ✅ Custom Classifier Head
- ✅ Data Augmentation (`RandomResizedCrop`, `RandomHorizontalFlip`)
- ✅ Dataset Normalization
- ✅ Real-time Accuracy/Loss Tracking
- ✅ Final Predictions & Result Visualization

---

## 📊 Results

| Metric        | Score     |
|---------------|-----------|
| **Test Accuracy** | **86%** |
| **Train Accuracy** | _Not Recorded_ |
| **Validation Accuracy** | _Not Recorded_ |

> Train/Val accuracy was not tracked, but the final test accuracy confirms solid generalization performance.
