# Neural Network Training for Japanese MNIST Dataset

This project focuses on developing and training custom neural network architectures to classify handwritten Hiragana characters using the Japanese MNIST dataset. The primary goal is to achieve accurate recognition of these characters with a minimum accuracy of 80%, through various experiments with different architectures and hyperparameters.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Experiments and Architectures](#experiments-and-architectures)
- [Results](#results)
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Neural networks, inspired by the human brain's architecture, have demonstrated unparalleled capabilities in image recognition, natural language processing, and pattern recognition. This project explores the development and training of custom neural network architectures to classify handwritten Hiragana characters from the Japanese MNIST dataset.

## Data

The project utilizes the **Japanese MNIST dataset**, which contains 70,000 images of handwritten Hiragana characters:
- **Dimensions**: Each image is 28x28 pixels, represented as a 784-dimensional vector.
- **Classes**: 10 distinct classes representing different Hiragana characters.
- **Preprocessing**: Images are normalized, and the target variable is converted into a binary class matrix.

## Experiments and Architectures

Three experiments were conducted with different neural network architectures:

1. **Experiment 1: L2 Regularization Architecture**
   - Uses L2 regularization to prevent overfitting.
   - Architecture: One hidden layer with a dropout layer.
   - Performance: Training accuracy of 99.98%, Testing accuracy of 88.61%.

2. **Experiment 2: Early Stopping Architecture**
   - Implements early stopping to prevent overfitting.
   - Architecture: One hidden layer with a dropout layer.
   - Performance: Training accuracy of 99.11%, Testing accuracy of 88.81%.

3. **Experiment 3: L2 Regularization with Multiple Hidden Layers**
   - Utilizes L2 regularization and multiple hidden layers to capture complex patterns.
   - Performance: Training accuracy of 99.82%, Testing accuracy of 98.34%.

## Results

- **Best Model**: Experiment 3 achieved the highest testing accuracy of 98.34%, demonstrating superior generalization performance.
- The project demonstrates the effectiveness of using regularization and multiple hidden layers to enhance model accuracy and generalization capabilities.

## Requirements

To run the code, you need to install the following libraries:

- Python 3.8 or higher
- NumPy
- Pandas
- TensorFlow or PyTorch
- Matplotlib
- Jupyter Notebook

You can install all dependencies using the following command:

```bash
pip install -r requirements.txt
