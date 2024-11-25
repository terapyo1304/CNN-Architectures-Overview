# Deep Learning Models for Image Classification

This repository contains an implementation of simplified **ResNet-3** and **VGG-3** models, designed for image classification tasks using the CIFAR-10 dataset. The project explores the use of convolutional neural networks (CNNs) with different architectural strategies for feature extraction and classification.

## Table of Contents
- [Introduction](#introduction)
- [Implemented Models](#implemented-models)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [Acknowledgments](#acknowledgments)

---

## Introduction
This project demonstrates the development and training of two CNN architectures:
1. **ResNet-3**: A simplified version of ResNet with 3 residual blocks and global average pooling.
2. **VGG-3**: A reduced version of VGG with 3 convolutional layers and max pooling.

Both models are implemented from scratch using PyTorch, focusing on efficient training and evaluation on the CIFAR-10 dataset.

---

## Implemented Models

### **ResNet-3**
- **Architecture**:
  - Initial convolution layer.
  - 3 residual blocks, each with two convolutional layers and a shortcut connection.
  - Global Average Pooling (GAP) before the fully connected layer.
- **Advantages**:
  - Residual connections prevent vanishing gradients.
  - GAP reduces parameters, promoting simplicity and generalization.

### **VGG-3**
- **Architecture**:
  - 3 convolutional layers with ReLU activation, each followed by max pooling.
  - Fully connected layers for classification.
- **Advantages**:
  - Straightforward design, effective for smaller datasets like CIFAR-10.

---

## Dataset
The **CIFAR-10** dataset was used for training and testing. It consists of:
- 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck).
- 50,000 training images and 10,000 testing images.

---

