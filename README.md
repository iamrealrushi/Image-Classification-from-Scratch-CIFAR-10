# Image Classification from Scratch (CIFAR-10)

## Overview

This project implements a neural network **from scratch using only NumPy** to classify images from three selected classes of the CIFAR-10 dataset. The implementation includes manual forward propagation, backpropagation, and gradient descent—no high-level ML libraries or pre-trained models are used.

## Dataset

- **Source:** CIFAR-10 (via Keras datasets)
- **Classes Used:** (e.g., airplane, automobile, bird)
- **Preprocessing:** Normalization, flattening, and one-hot encoding

## Methodology

- **Model:** Two-layer fully connected neural network with ReLU and softmax activations
- **Training:** Manual implementation of forward and backward propagation, L2 regularization, and gradient descent
- **Evaluation:** Test accuracy, precision, recall, F1-score, and confusion matrix

## Results

- **Test Accuracy:** 64.43%
- **Precision, Recall, F1-score:** Reported for each class in the output
- **Visualizations:** Loss and accuracy curves, confusion matrix


## Requirements

- Python 3.7+
- numpy
- scikit-learn
- matplotlib
- seaborn

## Analysis

See `report.pdf` for a 200-word analysis of model performance, challenges faced, and possible improvements.
