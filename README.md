# handwritten-digit-recognition-mlp
A Multi-Layer Perceptron (Neural Network) to classify handwritten digits from the MNIST dataset using Scikit-Learn and TensorFlow.
# Handwritten Digit Recognition (MNIST) 

This project implements a **Multi-Layer Perceptron (MLP)** neural network to recognize handwritten digits (0-9). The model is trained on the famous MNIST dataset.

## Model Architecture
The network consists of:
- **Input Layer**: 784 neurons (representing 28x28 pixel images).
- **Hidden Layer 1**: 128 neurons with ReLU activation.
- **Hidden Layer 2**: 64 neurons with ReLU activation.
- **Output Layer**: 10 neurons (one for each digit 0-9) using Softmax.

## Results
The model achieves an accuracy of approx **98%** (Check your report for exact number).

## How to Run
1. Install dependencies:
   ```bash
   pip install numpy matplotlib scikit-learn tensorflow seaborn
