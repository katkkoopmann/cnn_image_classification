# Image Classification using Convolutional Neural Networks (CNN)

This project implements a Deep Learning model to classify images from the **CIFAR-10** dataset using TensorFlow and Keras.

## Project Overview
The goal is to recognize 10 different categories of images (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck) by training a CNN.

## Model Architecture
The network consists of a sequential stack of layers designed for spatial feature extraction:
* **Convolutional Layers (Conv2D):** Three layers with 32 and 64 filters to detect visual patterns.
* **Max Pooling Layers:** To reduce spatial dimensions and computational load.
* **Dropout (0.5):** Implemented to prevent overfitting during training.
* **Dense Layers:** A fully connected head with ReLU activation and a Softmax output layer for multi-class classification.

## Performance
* **Training Epochs:** 15
* **Batch Size:** 64
* **Final Test Accuracy:** 68.10%
