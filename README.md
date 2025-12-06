# Video Views Prediction - ML Project

## 📋 Overview

This project predicts YouTube Shorts and TikTok video views using machine learning models. We analyze social media trends data from 2025 to understand what factors can be used to predict the video viewcount

**Dataset Source:** Kaggle / Hugging Face  
**Authors:** Code for Fun Dev, Timur, Will O'Halloran

## Models Implemented

1. **XGBoost Regressor** - Gradient boosting with hyperparameter tuning via GridSearchCV
2. **Linear Regression** - With feature scaling (MinMaxScaler) and 5-fold cross-validation
3. **Polynomial Regression** - Degree-2 polynomial features to capture non-linear relationships
4. **Neural Network (MLPRegressor)** - Multi-layer perceptron with (64, 32) hidden layers
