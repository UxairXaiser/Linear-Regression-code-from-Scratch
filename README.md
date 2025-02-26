# Linear Regression from Scratch with Gradient Descent
This repository contains a simple Python implementation of linear regression using gradient descent, built entirely from scratch. The script demonstrates the process of training a linear model on synthetic data over 1000 epochs and visualizes the progression of the regression line.

Overview
Data Generation:
Synthetic data is created by generating X values in the range [0, 5) and computing Y as a linear function (0.4 * X + 3) with added uniform noise.

Model Prediction:
The predicting_Yp function calculates model predictions using the equation Yp = w * X + b.

Loss Calculation:
The mean squared error (MSE) is computed using the calculate_loss function, which measures the difference between the predicted and actual values.

Parameter Updates:
The updating_param function applies gradient descent to update the model parameters (weight and bias) based on the gradients computed from the loss.

Visualization:
The regression line is plotted at each epoch along with the data points, allowing you to visualize the model’s convergence over 1000 iterations.

This code serves as an educational example to illustrate the fundamental concepts of linear regression and gradient descent in Python.
