# Classification of Image Data

## Project Overview
This project explores image classification using **Multilayer Perceptrons (MLPs)** and **Convolutional Neural Networks (CNNs)**. The goal is to analyze how hyperparameters, regularization, and optimization affect model performance on image datasets.

## Key Highlights
- Implemented MLPs with different weight initialization methods, hidden layers, and activation functions.
- Built CNNs to compare performance with MLPs.
- Benchmarked models on Fashion MNIST and CIFAR-10 datasets.

## Technologies Used
- **PyTorch**: Model implementation and training.
- **Python**: Preprocessing and result visualization.

## Datasets
- **Fashion MNIST**: Zalando’s article images (28x28 grayscale images).
- **CIFAR-10**: Color images in 10 classes (32x32 pixels).

## Results
- **MLPs**:
  - Xavier and Kaiming initialization yielded superior results.
  - Regularization (L2) effectively reduced overfitting.
- **CNNs**:
  - Slightly outperformed MLPs, especially for CIFAR-10.
  - Leveraged spatial relationships for improved feature extraction.

## References
- [Fashion MNIST Dataset](https://pytorch.org/vision/stable/generated/torchvision.datasets.FashionMNIST.html)
- [CIFAR-10 Dataset](https://pytorch.org/vision/main/generated/torchvision.datasets.CIFAR10.html)
