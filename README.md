# CIFAR-10 MLP Classifier

A Multilayer Perceptron (MLP) neural network implemented in PyTorch for image classification on the CIFAR-10 dataset (10 classes).  
Includes experiments with multiple architectures, learning rates, dropout values, batch sizes, regularization techniques, and early stopping.

---

## Overview

This project explores how different hyperparameters affect the performance and generalization ability of an MLP model on a complex dataset like CIFAR-10.  
The final model achieves **57.95% test accuracy**, which is a solid result for a pure MLP on CIFAR-10.

---

## Features

- Full MLP implementation in PyTorch  
- Customizable architecture (1–4 hidden layers)  
- Experiments with:
  - Learning rate  
  - Dropout  
  - Batch size  
  - Weight decay  
  - Number of epochs  
- Early stopping and model evaluation  
- Metrics: accuracy, precision, recall, F1-score  
- Training & test loss curves visualization  

