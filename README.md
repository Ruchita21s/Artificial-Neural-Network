# 🎨 Fashion MNIST Image Classification Project 🛍️

## Overview ℹ️
This project aims to classify fashion items using the Fashion MNIST dataset. It involves data preprocessing, building and training an Artificial Neural Network (ANN) model, and evaluating the model's performance.

## Libraries Used 📚
- `numpy` for numerical computations
- `matplotlib` for data visualization
- `tensorflow.keras` for building and training the neural network model

## Load the Dataset 📊
The Fashion MNIST dataset is loaded using TensorFlow's Keras API. It consists of 60,000 training images and 10,000 test images, each of size 28x28 pixels.

## Data Preprocessing 🔄
The pixel values of the images are scaled to a range between 0 and 1. Additionally, the data is reshaped to match the input shape expected by the neural network model.

## Exploratory Data Analysis 🔍
Sample images from the dataset are displayed, along with a bar chart showing the distribution of samples across different classes. The uniform distribution of samples across classes is observed.

## Build an Artificial Neural Network 🧠
An ANN model is constructed using TensorFlow's Keras API. It consists of convolutional and pooling layers followed by fully connected layers. Batch normalization and dropout are applied for regularization.

## Training the Model 🚀
The model is trained using data augmentation techniques to prevent overfitting. The training process is monitored using callbacks for learning rate adjustment and early stopping.

## Model Evaluation 📈
The trained model is evaluated on the test dataset, yielding an accuracy of approximately 88.68%.

## Test Set Prediction 📝
Predictions are made on a subset of the training dataset, and the results are visualized. Correct predictions are highlighted in blue, while incorrect predictions are highlighted in red.

This project demonstrates the process of building and training a neural network model for image classification tasks using TensorFlow and Ker
