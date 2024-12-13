# Neural_Network-Make_Circles
This repository demonstrates the implementation of neural network architecture for solving a classification problem using the make_circles dataset from scikit-learn. The make_circles dataset generates a binary classification problem with two concentric circles, making it a non-linearly separable dataset ideal for testing the capabilities of neural networks.

Overview

The project explores the following key components:

1. Dataset: The make_circles dataset from scikit-learn.
2. Neural Network Architecture: A fully connected neural network with non-linear activation functions.
3. Framework Used: PyTorch.
4. Training Process: Includes forward pass, loss computation, backpropagation, and optimization.

Neural Network Architecture

The neural network (CircleModel) consists of:

* Input Layer: 2 features (coordinates X1 and X2).
* Hidden Layers: Two layers with 10 neurons each, activated using ReLU.
* Output Layer: A single neuron for binary classification.
* Activation Functions: ReLU for hidden layers and Sigmoid for output.

Training

Steps in the Training Loop:

* Forward pass: Calculate predictions from the model.
* Compute loss: Use Binary Cross-Entropy with Logits Loss (BCEWithLogitsLoss).
* Zero gradients: Clear gradients from the optimizer.
* Backpropagation: Calculate gradients.
* Update parameters: Apply gradient descent.

Metrics

* Loss: Binary cross-entropy.
* Accuracy: Proportion of correctly predicted labels.
