# Neural Networks and Deep Learning – Final Project

A comprehensive analysis and implementation of various neural network architectures (MLP, LSTM, CNN) for regression and classification tasks, developed as a final project at **AGH University of Krakow**.

## Project Overview
This project focuses on investigating the impact of architecture and hyperparameters on the training process and the generalization capabilities of models. The analysis includes both low-level implementations (from scratch) and solutions based on modern deep learning frameworks.

## Scope of Research

### 1. Regression
* **AirQuality:** Predicting pollutant concentrations based on chemical sensor data.
* **Jena Climate:** Advanced time-series analysis for temperature forecasting.
    * *Achieved Performance: R² = 0.99 for selected architectures.*

### 2. Classification
* **Robot Navigation:** Predicting mobile robot movements based on sensor readings (multi-class classification).
* **Connect_4:** Determining the theoretical outcome of a game state in Connect Four.

## Architectures Used
* **MLP (Multi-Layer Perceptron):** Comparison between custom implementation (no libraries) and framework-based solutions.
* **LSTM (Long Short-Term Memory):** Optimized for sequential data modeling.
* **CNN (Convolutional Neural Networks):** Utilizing convolutional layers for feature extraction from sequences and patterns.

## Methodology and Optimization
The project involved a series of experiments regarding:
* **Optimizers:** Adam, SGD, LBFGS, RMSprop, Nadam.
* **Hyperparameters:** Learning Rate (LR), Momentum, number of layers, and neurons.
* **Regularization:** Analysis of Overfitting and weight stability.
* **Automation:** Efficient hyperparameter tuning using Random Search and Grid Search methods.

## Authors
* Filip Kopańko
* Mateusz Kucharz
* Jakub Laszczyk

---
*Project developed for the course: Neural Networks and Deep Learning (Computer Science and Econometrics, AGH).*
