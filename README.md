# Classification by finetuning ResNet50 and VGG16

We finetune the pretrained VGG16 and ResNet50 architectures to classify for a Dogs and Cats dataset.

The dataset used is available here: https://www.kaggle.com/datasets/salader/dogs-vs-cats

# Dogs vs Cats Classification using Transfer Learning

This project demonstrates binary image classification (dogs vs. cats) using transfer learning with pre-trained VGG16 and ResNet50 models in TensorFlow/Keras.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Results](#results)

---

## Overview

The notebook implements two deep learning models for classifying images of dogs and cats:

- **Model 1:** VGG16 + custom classifier
- **Model 2:** ResNet50 + custom classifier

Both models are trained and evaluated on a dataset of dog and cat images using transfer learning.

---

## Dataset

- **Source:[Kaggle](https://www.kaggle.com/datasets/chetankv/dogs-cats-images)** Directory-based dataset with the following structure:
dataset/
train/
cats/
dogs/
test/
cats/
dogs/

---
- **Train:** 8,000 images (cats and dogs)
- **Test:** 2,000 images (cats and dogs)

## Results

| Model     | Validation Accuracy |
|-----------|--------------------|
| VGG16     | ~92.8%             |
| ResNet50  | ~67.6%             |





