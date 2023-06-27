# Neural Network Implementation from Scratch for Digit Recognition
## Introduction
This repository contains an implementation of a neural network from scratch using only the NumPy library for digit recognition. The neural network is designed to classify handwritten digits from the famous MNIST dataset. By creating this neural network implementation, you can gain a deeper understanding of the underlying principles of neural networks and how they can be applied to solve classification tasks.
## Features
The neural network implementation offers the following features:

1. **NumPy-based Implementation:** The entire neural network is built using only the NumPy library, which provides powerful mathematical functions and array operations. By relying solely on NumPy, you can focus on understanding the fundamental concepts of neural networks without the complexity of additional libraries.

2. **Feedforward Architecture:** The neural network utilizes a feedforward architecture, where information flows from the input layer through one or more hidden layers to the output layer. This implementation allows you to customize the number of hidden layers, the number of neurons in each layer, and the activation function used.

3. **Backpropagation Training:** The neural network employs the backpropagation algorithm to train the model. It calculates the gradients of the network's weights and biases with respect to the loss function, enabling iterative adjustments that improve the network's accuracy over time.

4. **Mini-batch Stochastic Gradient Descent:** The implementation uses mini-batch stochastic gradient descent with momentum as the optimization algorithm. Momentum helps accelerate the convergence of the training process by adding a fraction of the previous update to the current update step. This approach enhances the network's ability to navigate the weight space and find better minima.

5. **Model Evaluation:** The code includes evaluation metrics such as accuracy, precision, recall, and F1-score, allowing you to assess the performance of the trained model on the test dataset.
