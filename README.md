# Car Price Prediction using Machine Learning & Deep Learning

This repository contains a project focused on predicting car prices based on various features such as mileage, horsepower, top speed, and others. The project leverages both **Machine Learning** and **Deep Learning** models for predicting the target variable: `price`.

## Overview

### Objective
The goal of this project is to predict the **price of cars** based on various features like mileage, horsepower, top speed, and other vehicle characteristics.

### Dataset
The dataset used contains data on various cars, each with features that affect pricing, such as engine size, weight, horsepower, and fuel type. The target variable is `price`.

The dataset includes the following columns:
- `mileage`: The mileage of the car (in kilometers).
- `horsepower`: The horsepower of the car.
- `top_speed`: The top speed of the car (in km/h).
- `car_age`: Age of the car.
- `weight`: The weight of the car (in kilograms).
- `engine_size`: The size of the engine (in liters).
- `fuel_type`: Type of fuel (categorical).
- `num_doors`: Number of doors in the car (categorical).
- `price`: The target variable (price of the car).

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - `Pandas`: Data manipulation and cleaning
  - `NumPy`: Numerical computations
  - `Scikit-learn`: For building Machine Learning models
  - `TensorFlow`/`Keras`: For building Deep Learning models
  - `Matplotlib`: Visualization of results
- **Development Environment:**
  - Jupyter Notebooks or any Python IDE
  - Anaconda (optional) for virtual environment and package management

## Features of the Project

### Data Cleaning & Preprocessing
- Removed missing values.
- Encoded categorical variables (`fuel_type` and `num_doors`) using one-hot encoding.
- Scaled numerical features like `mileage`, `horsepower`, `top_speed`, `weight`, etc., using `StandardScaler`.

### Data Exploration & Visualization
- Analyzed the distribution of features and their relationships with the target variable (`price`).
- Visualized correlations between features using heatmaps and scatter plots.

### Models Built
 **Deep Learning Model (Neural Network)**
- Built a deep neural network using **Keras/TensorFlow**.
- Utilized **ReLU** activation functions in hidden layers and a linear output layer.
- Optimized with the **Adam optimizer** and used **Mean Squared Error (MSE)** as the loss function.


