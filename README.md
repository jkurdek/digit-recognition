# Digit Recognition using Neural Networks

A Python implementation of a neural network for recognizing handwritten digits using the MNIST dataset.

## Overview

This project implements a feedforward neural network from scratch to classify handwritten digits. The model achieves approximately 98% accuracy on the MNIST test set.

## Features

- Custom implementation of neural network architecture
- Support for different cost functions (MSE and Cross Entropy)
- Stochastic gradient descent optimization
- Early stopping to prevent overfitting
- Batch processing for efficient training

## Dependencies

- Python 3.8+
- NumPy
- tqdm
- pickle
- gzip

## Dataset

The project uses the MNIST dataset, which should be downloaded as `mnist.pkl.gz` and placed in the project root directory.

## Usage

1. Ensure all dependencies are installed
2. Download the MNIST dataset
3. Run the Jupyter notebook `Digit_Recognition.ipynb`

## Model Architecture

- Input layer: 784 neurons (28x28 pixel images)
- Hidden layer 1: 300 neurons
- Hidden layer 2: 100 neurons
- Output layer: 10 neurons (one for each digit)

## Performance

The model typically achieves:

- Training accuracy: ~98%
- Test accuracy: ~98%
