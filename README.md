# LiverNet: Automated Tumor Detection and Classification

This repository contains the code and documentation for **LiverNet**, an advanced deep learning-based system for automated detection, segmentation, and classification of liver tumors from medical images. The goal is to enhance diagnostic accuracy and provide a reliable tool for early tumor detection using convolutional neural networks.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)


---

## Introduction
Liver cancer is among the leading causes of cancer-related deaths worldwide. Early detection and accurate diagnosis can improve patient outcomes. **LiverNet** leverages **U-Net** for tumor segmentation and optional classification models to differentiate between benign and malignant tumors. 

This project integrates **image preprocessing techniques** and **deep learning models** to process liver CT or MRI scans, extract features, and classify tumors effectively.

---

## Features
- **Image Preprocessing:** Resizing, normalization, grayscale conversion, and augmentation.
- **Segmentation Model:** U-Net for precise tumor boundary detection.
- **Optional Classification Model:** Extendable to include classifiers like ResNet or VGGNet.
- **Visual Predictions:** Display predictions overlaid on original images.
- **Evaluation Metrics:** Accuracy, Dice coefficient, and loss tracking.

---

## Dataset
You can use publicly available datasets like the **LiTS (Liver Tumor Segmentation Challenge)** dataset.

- **Images:** Liver CT or MRI scans.
- **Masks:** Binary masks identifying tumor regions.
  

