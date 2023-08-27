# Health Insurance Cross-Sell Prediction

This repository contains code and documentation for a machine learning project focused on predicting cross-sell opportunities for health insurance.

## Overview

The goal of this project is to predict whether a customer will be interested in purchasing vehicle insurance, also known as cross-selling. The project involves exploratory data analysis, data transformation, model training, hyperparameter tuning, and model evaluation.

## Contents

- **Part 1: Data Exploration and Preprocessing:** Initial exploration of the dataset, handling missing values, and preparing the data for modeling.
- **Part 2: Model Training (Baseline Models):** Training initial machine learning models including Logistic Regression, Naive Bayes, Decision Tree, Random Forest, and XGBoost.
- **Part 3: Hyperparameter Tuning:** Using RandomizedSearchCV to fine-tune hyperparameters for the XGBoost model.
- **Part 4: Model Comparison:** Comparing the performance of models with and without hyperparameter tuning using evaluation metrics.
- **Part 5: Model Selection and Future Work:** Selecting the best-performing model, discussing observations, and outlining future steps.


## Results

The best-performing model is the RandomForestClassifier with hyperparameters (max_depth = 10, n_estimators = 200, min_samples_split = 100). It achieves an accuracy of 78.5% on the test data.

## Future Work

- Save the best-performing model in a pickle file for deployment.
- Load the saved model and make predictions on unseen data.
- Explore additional feature engineering techniques.
- Experiment with other machine learning algorithms.

for more details or for in any queries contact sumantkale1999@gmail.com

