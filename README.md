# Handwritten Digit Classification using Logistic Regression in PyTorch

## Project Overview
This project implements a Logistic Regression model using PyTorch to classify handwritten digits (0–9) from the MNIST dataset. It demonstrates a simple approach to image classification using fundamental machine learning concepts.

## Key Features
- Uses MNIST dataset (28x28 grayscale digit images)
- Implements logistic regression using `nn.Linear`
- Trains model with Stochastic Gradient Descent (SGD)
- Loss function: Cross Entropy
- Achieves ~84% accuracy on test data

## Requirements
- Python 3.x
- PyTorch
- torchvision

Install dependencies:
```bash
pip install torch torchvision
