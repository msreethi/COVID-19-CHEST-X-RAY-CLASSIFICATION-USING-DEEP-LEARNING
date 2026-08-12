# 🩺 Pneumonia Detection Using CNN

A deep learning-based medical image classification project that uses a **Convolutional Neural Network (CNN)** to classify chest X-ray images into two categories: **PNEUMONIA** and **NORMAL**.

## 📌 Project Description

This project aims to develop an automated system for classifying chest X-ray images using deep learning. The images are processed and resized to **150 × 150 pixels** before being provided as input to the CNN model.

The CNN learns important features from the chest X-ray images and predicts whether the image belongs to the **PNEUMONIA** or **NORMAL** class.

## 🎯 Objectives

- Classify chest X-ray images using a CNN.
- Detect pneumonia-related patterns in X-ray images.
- Preprocess and resize input images.
- Train a deep learning image classification model.
- Evaluate the model using test data.
- Predict the class of new X-ray images.

## 🧠 Model Architecture

The CNN consists of:

- Convolutional layers
- Max Pooling layers
- Flatten layer
- Fully Connected (Dense) layer
- Softmax output layer

### Classes

| Class | Label |
|-------|-------|
| PNEUMONIA | 0 |
| NORMAL | 1 |

## 🔄 Workflow

```text
Chest X-Ray Image
        ↓
Image Loading
        ↓
Image Preprocessing
        ↓
Resize to 150 × 150
        ↓
Convolutional Layers
        ↓
Max Pooling
        ↓
Flatten
        ↓
Dense Layer
        ↓
Softmax
        ↓
PNEUMONIA / NORMAL
```
Dataset : https://www.kaggle.com/datasets/khoongweihao/covid19-xray-dataset-train-test-sets?select=xray_dataset_covid19

Author

Sreethi Manoharan
