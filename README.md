# Handwritten Digit Classification

## Overview
This project implements a handwritten digit classification algorithm using a Convolutional Neural Network (CNN) on the MNIST dataset. The model is trained to recognize digits from 0 to 9 and can be used in a graphical user interface (GUI) application for real-time digit classification.

## Table of Contents
- [Data Preparation](#data-preparation)
- [Model Architecture](#model-architecture)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [GUI Application](#gui-application)
- [Usage](#usage)

## Data Preparation
1. Load the MNIST dataset.
2. Preprocess the data by normalizing pixel values to the range [0, 1].

## Model Architecture
1. Define a Convolutional Neural Network (CNN) with the following layers:
   - Convolutional layers with ReLU activation.
   - Max pooling layers.
   - Fully connected layers.
   - Output layer with softmax activation for classification.
2. Choose the loss function as categorical cross-entropy and the optimizer as Adam.

## Model Training
1. Split the dataset into training and testing sets.
2. Train the model on the training set using backpropagation.

## Evaluation
1. Evaluate the trained model on the test set.
2. Print the test accuracy.

## Hyperparameter Tuning
1. Experiment with different hyperparameters (e.g., learning rate, batch size, number of epochs) for optimal performance.

## GUI Application
A simple GUI application is created using Tkinter that allows users to draw digits and classify them using the trained model.

### GUI Features
- Canvas for drawing digits.
- Clear button to reset the canvas.
- Display of the predicted digit.

## Usage
1. Run the training script to train the model on the MNIST dataset.
2. Save the trained model as `mnist.h5`.
3. Run the GUI application to draw digits and classify them.

