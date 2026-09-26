https://github.com/narmeenjamil/ANN-project-class-room-image-classification/actions
# ANN Project – Classroom Image Classification

## Project Overview

This project uses an Artificial Neural Network (ANN) to classify images into three categories based on cleanliness level:

- Clean
- Moderately_Dirty
- Dirty

## Objective

The main objective of this project is to automatically classify a new image into the correct cleanliness category using an ANN model.

## Dataset

The dataset contains images organized into three classes:

### Clean
Images with little or no visible dirt or waste.

### Moderately_Dirty
Images with a medium level of dirt or waste.

### Dirty
Images with clearly visible and higher amounts of dirt or waste.

## Preprocessing

- Images are converted to RGB format.
- Images are resized to 64 × 64 pixels.
- Pixel values are normalized by dividing by 255.
- The dataset is divided into training and testing data.

## ANN Model

The model contains:

- Flatten layer
- Dense layer with 128 neurons and ReLU activation
- Dropout layer with 0.3 rate
- Dense layer with 64 neurons and ReLU activation
- Output layer with 3 neurons and Softmax activation

## Training

- Optimizer: Adam
- Loss Function: Sparse Categorical Cross-Entropy
- Metric: Accuracy
- Epochs: 20
- Batch Size: 8

## Evaluation

The model is evaluated using:

- Test Accuracy
- Test Loss
- Accuracy and Loss graphs
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

## Project File

`ANN_MID_Project.ipynb`

## Platform

Google Colab / Python / TensorFlow-Keras
