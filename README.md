Pneumonia Detection Using CNN

A deep learning-based medical image classification project that uses a Convolutional Neural Network (CNN) to classify chest X-ray images into PNEUMONIA and NORMAL categories.

🩺 Project Overview

The objective of this project is to develop a CNN model capable of analyzing chest X-ray images and automatically classifying them as either Pneumonia or Normal.

The images are preprocessed and resized to 150 × 150 × 1 before being given as input to the CNN model.

🎯 Objectives
Classify chest X-ray images using deep learning.
Detect pneumonia-related patterns in X-ray images.
Preprocess and resize input images.
Train a CNN model for image classification.
Evaluate the trained model using test data.
Predict the class of new X-ray images.

🧠 CNN Architecture

The model consists of:

Conv2D layer
MaxPooling2D layer
Conv2D layer
MaxPooling2D layer
Flatten layer
Dense layer with 100 neurons
Output Dense layer with 2 neurons
Softmax activation

The two output classes are:

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
TensorFlow / Keras
NumPy
Scikit-learn
Scikit-image
Matplotlib
Jupyter Notebook / Google Colab
📊 Model Training

The CNN model is trained using:

Optimizer: Adam
Loss Function: Sparse Categorical Crossentropy
Metric: Accuracy
Epochs: 10
Batch Size: 20

These training settings are present in the project notebook.

📈 Results

The model achieved approximately:

Test Accuracy: 97.97%

The notebook's test evaluation reports a loss of approximately 0.0569 and accuracy of approximately 97.97%.

The classification results show approximately 0.98 F1-score for both classes.

🔍 Prediction

The trained model can be used to predict a new chest X-ray image.

The image is:

Loaded.
Resized to 150 × 150 × 1.
Reshaped to include the batch dimension.
Passed to the CNN.
Classified using the class with the highest prediction probability.

The notebook demonstrates prediction of a new X-ray image as NORMAL.

👩‍💻 Author

Sreethi Manoharan
