# Calorie Burn Predictor (NumPy from Scratch)

This repository contains a **Multiple Linear Regression** model built entirely from scratch using **NumPy**. The goal of the project is to predict the number of calories burned during a workout based on features like duration, heart rate, and body temperature.

## 🚀 Key Features
- **Custom Optimizer:** Implemented Gradient Descent from scratch (no `sklearn` for training).
- **Vectorized Math:** Utilized NumPy matrix operations for efficient computation.
- **Data Preprocessing:** Includes feature scaling (Standardization) to handle multi-scale health data.
- **Performance Metrics:** Evaluated using R-squared ($R^2$) and Mean Absolute Error (MAE).

## 📊 Model Performance
- **Accuracy (R-squared):** ~99.2%
- **Mean Absolute Error:** ~10.5 Calories

## 🛠️ Technologies Used
- **Python**
- **NumPy** (Model Logic & Math)
- **Matplotlib** (Data Visualization)
- **Scikit-Learn** (Data Loading & Scaling only)
- **Google Colab** (Development Environment)

## 📖 How it Works
The model uses the Linear Regression formula:
$y = XW + b$

The weights are optimized using **Gradient Descent** by minimizing the **Mean Squared Error (MSE)** loss function over 1000 iterations.
