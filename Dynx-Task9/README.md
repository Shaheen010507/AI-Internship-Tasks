# Task 1 - Handwritten Digit Recognition using Artificial Neural Network (ANN)

## Objective
To develop an Artificial Neural Network (ANN) model capable of recognizing handwritten digits using the MNIST dataset and evaluate its performance using accuracy and loss metrics.

## Dataset
MNIST Handwritten Digit Dataset

- Source: TensorFlow / Keras Built-in Dataset
- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 Pixels
- Classes: Digits 0–9

## Problem Statement
Handwritten digit recognition is a fundamental computer vision task. The objective is to train an ANN model that can accurately identify handwritten digits from image data.

## Methodology

### 1. Data Loading
- Loaded the MNIST dataset directly from Keras.
- Split into training and testing datasets.

### 2. Data Preprocessing
- Normalized pixel values from 0–255 to 0–1.
- Prepared image data for neural network training.

### 3. Model Architecture
- Input Layer (28 × 28 image)
- Hidden Layer 1: 128 neurons (ReLU)
- Hidden Layer 2: 64 neurons (ReLU)
- Output Layer: 10 neurons (Softmax)

### 4. Model Training
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 10

### 5. Model Evaluation
- Accuracy Score
- Loss Score
- Accuracy Graph
- Loss Graph
- Sample Predictions

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

## Results
The ANN model successfully learned patterns from handwritten digit images and achieved high classification accuracy on the test dataset. The generated accuracy and loss graphs demonstrated effective model training and convergence.

## Learning Outcomes
- Understanding Artificial Neural Networks
- Image Classification Fundamentals
- Deep Learning Workflow
- Model Training and Evaluation
- Handwritten Digit Recognition using MNIST

## Conclusion
This project demonstrates the implementation of an Artificial Neural Network for handwritten digit recognition. The trained model accurately classifies digits from 0 to 9 and showcases the effectiveness of deep learning techniques for image classification tasks.
