# Artificial Neural Network From Scratch

# Description

The goal of this project is to build a simple but functional artificial neural network using only Numpy, a powerful library for numerical computations in Python. This will involve:

### Objectives

* Understanding the basic theory behind neural networks, including their architecture and how they learn.
* Implementing the neural network components such as layers, weights, biases, and activation functions.
* Designing a backpropagation algorithm to update the network weights based on error.
* Testing the network on simple datasets to observe its learning capabilitie

## Prerequisites

* Basic knowledge of Python programming.
* Familiarity with Numpy and its array operations.
* Understanding of basic calculus and linear algebra (mainly matrix operations).
* Basic concepts of machine learning such as training, testing, loss functions, etc.

# Steps to Build the ANN

## Step 1: Forward Propagation

* Implement the linear part of a layer's forward step, which is essentially z=wx+b (where w is weight, x is input, and b is bias).
* Apply an activation function like sigmoid, tanh, or ReLU to introduce non-linearity.


## Step 2: Loss Computation

* Implement a loss function, such as mean squared error for regression or cross-entropy loss for classification, to evaluate the performance of the network.


## Step 3: Backward Propagation

* Calculate gradients of the loss function with respect to each weight and bias by applying the chain rule, moving backward from the output to the input layer.
* Update the weights and biases, typically using a simple gradient descent method or other optimization algorithms like SGD, Adam, etc.


## Step 4: Training the Network

* Combine the forward pass, loss computation, and backward pass into a training loop.
* Iterate over a set number of epochs or until the loss reaches an acceptable level.
* Optionally implement batch or mini-batch processing to improve training efficiency.


## Step 5: Evaluation and Testing
* Evaluate the trained model on a separate testing set to check its generalization capability.
* Fine-tune parameters or add complexity like more layers or different activation functions to improve accuracy


# Example Dataset
we used Dataset [Breast Cancer](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)

## Table of Contents

- [Installation](#installation)
- [Contact](#Contact)


## Installation

```bash
pip install -r requirements.txt
```


## Contact

Feel free to connect with me.
[Linkedin](https://www.linkedin.com/in/shukur-alam/)