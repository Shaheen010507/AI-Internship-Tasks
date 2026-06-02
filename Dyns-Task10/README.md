# Task 2 - Transfer Learning: Image Classification

## Objective
To implement Transfer Learning using the MobileNetV2 pre-trained model for image classification and evaluate its performance on the CIFAR-10 dataset.

## Dataset
CIFAR-10 Dataset

Source:
https://keras.io/api/datasets/cifar10/

## Dataset Description
The CIFAR-10 dataset consists of 60,000 color images belonging to 10 different classes.

Classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

Dataset Distribution:
- Training Images: 50,000
- Testing Images: 10,000
- Image Size: 32 × 32 pixels

## Pre-trained Model
MobileNetV2

MobileNetV2 is a lightweight Convolutional Neural Network (CNN) pre-trained on the ImageNet dataset. It is commonly used for Transfer Learning due to its efficiency and strong image classification performance.

## Methodology

### Data Loading
- Loaded the CIFAR-10 dataset directly from Keras.
- Split into training and testing datasets.

### Data Preprocessing
- Resized images to match MobileNetV2 input requirements.
- Normalized pixel values.
- Applied preprocessing suitable for MobileNetV2.

### Transfer Learning
- Loaded MobileNetV2 with pre-trained ImageNet weights.
- Frozen the base model layers.
- Added custom classification layers.

### Model Training
- Trained the model on the CIFAR-10 dataset.
- Used validation data to monitor performance.

### Model Evaluation
- Test Accuracy
- Test Loss
- Accuracy Graph
- Loss Graph
- Sample Predictions

## Technologies Used
- Python
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Matplotlib
- Google Colab

## Results
The MobileNetV2 model successfully classified images from the CIFAR-10 dataset. The model achieved good accuracy while benefiting from Transfer Learning, reducing training time and computational requirements.

## Learning Outcomes
- Understanding Transfer Learning
- Working with Pre-trained Models
- Image Classification using Deep Learning
- MobileNetV2 Architecture
- Performance Evaluation and Visualization

## Conclusion
This project demonstrates the application of Transfer Learning using MobileNetV2 for image classification. By leveraging pre-trained ImageNet features, the model effectively classified CIFAR-10 images while achieving strong performance with reduced training effort.
