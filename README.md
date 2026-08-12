# Pneumonia Detection Using CNN

A deep learning-based chest X-ray image classification project using a **Convolutional Neural Network (CNN)** to classify X-ray images into **PNEUMONIA** and **NORMAL** categories.

## 🩺 Project Overview

This project uses a Convolutional Neural Network to analyze chest X-ray images and classify them into two categories:

- PNEUMONIA
- NORMAL

The input images are resized to **150 × 150 pixels** and processed as grayscale images before being passed to the CNN model.

## 🎯 Objectives

- Classify chest X-ray images using deep learning.
- Detect pneumonia from chest X-ray images.
- Preprocess and resize X-ray images.
- Train a CNN image classification model.
- Evaluate the model using test data.
- Predict the class of a new X-ray image.

## 🧠 Model Architecture

The CNN model consists of:

- Conv2D layer
- MaxPooling2D layer
- Conv2D layer
- MaxPooling2D layer
- Flatten layer
- Dense layer
- Softmax output layer

### Output Classes


0 → PNEUMONIA
1 → NORMAL

🔄 Project Workflow
Chest X-Ray Image
        ↓
Image Loading
        ↓
Image Preprocessing
        ↓
Resize to 150 × 150
        ↓
CNN Feature Extraction
        ↓
Max Pooling
        ↓
Flatten
        ↓
Dense Layer
        ↓
Softmax Classification
        ↓
PNEUMONIA / NORMAL
🛠️ Technologies Used
Python
TensorFlow
Keras
NumPy
Scikit-learn
Scikit-image
Matplotlib
Jupyter Notebook / Google Colab
📊 Model Training

The model is trained using:

Optimizer: Adam
Loss Function: Sparse Categorical Crossentropy
Metric: Accuracy
Epochs: 10
Batch Size: 20
📈 Results

The CNN model achieved approximately:

Test Accuracy: 97.97%

The model was evaluated on the test dataset and achieved strong classification performance for the PNEUMONIA and NORMAL classes.

🔍 Prediction

The trained CNN can be used to predict a new chest X-ray image.

The prediction process includes:

Loading the X-ray image.
Resizing the image to 150 × 150 pixels.
Reshaping the image for CNN input.
Passing the image to the trained model.
Obtaining prediction probabilities.
Selecting the class with the highest probability.
