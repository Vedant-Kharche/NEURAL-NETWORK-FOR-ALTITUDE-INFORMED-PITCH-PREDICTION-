# NEURAL-NETWORK-FOR-ALTITUDE-INFORMED-PITCH-PREDICTION-
This project implements a feedforward neural network to predict aircraft pitch based on altitude, airspeed, and roll. The neural network is trained using either batch or stochastic gradient descent and supports multiple activation functions.

# Data Preprocessing:

Ensured data integrity by handling missing values and removing duplicates.
Scaled and organized data into a suitable format for neural network training.

# Neural Network Development:

Defined a structure with input, hidden, and output layers.
Initialized weights and biases with random values.
Used feedforward and backpropagation methods for training.

# Implementation:

Explored both batch and stochastic gradient descent training methods.
Tested multiple activation functions (ReLU, Sigmoid, Tanh) and learning rates (0.01, 0.001).
Employed dynamic iterations and early stopping mechanisms to avoid overfitting or underfitting.

## Results

Batch Training:
Best result achieved with ReLU activation and a 0.01 learning rate, yielding an MSE of 0.0086.

Stochastic Training:
Best result achieved with Sigmoid activation and a 0.001 learning rate, yielding an MSE of approximately 4.90e-09.

![image](https://github.com/user-attachments/assets/552d5d30-4d1f-44d9-8822-a4add0838ddf)


ReLU consistently demonstrated robust performance across both training methods.
Comparison revealed that batch gradient descent was more time-efficient, while stochastic gradient descent had faster convergence.
