# MNIST Digit Classifier

A feedforward neural network built with PyTorch to classify 
handwritten digits from the MNIST dataset.

## Model Architecture
- Input: 784 neurons (28×28 flattened)
- Hidden Layer 1: 128 neurons (ReLU)
- Hidden Layer 2: 64 neurons (ReLU)
- Output: 10 neurons (digits 0-9)

## Results
- Test Accuracy: 97.58%
- Epochs: 10
- Optimizer: Adam (lr=0.001)
- Loss: CrossEntropyLoss

## Run in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16Px3g9-aGNJpx-kPmSpYWwfFNFWNoMDC?usp=sharing)

## Requirements
- Python 3
- PyTorch
- torchvision
