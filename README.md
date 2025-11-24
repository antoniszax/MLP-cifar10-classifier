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



---

## Experiments Summary

Across the experiments, several observations were made:

- Lower learning rates improved stability  
- High learning rates (e.g., **0.01**) caused the model to fail completely (stuck at **10% accuracy**)  
- Adding more hidden layers increased training accuracy but did not always improve generalization  
- Dropout and weight decay helped reduce overfitting  
- Early stopping prevented wasted training time  
- The best model reached **57.95% test accuracy**, which is strong for MLPs on CIFAR-10  
