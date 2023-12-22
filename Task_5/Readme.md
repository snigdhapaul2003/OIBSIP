# 🌟 Sales Prediction Project 🌟

## Overview

Welcome to the Oasis Infobyte Sales Prediction Project! 🚀 In this project, we aim to predict sales using various regression techniques applied to a dataset sourced from Kaggle. The project is organized to provide a clear understanding of the process, from data exploration to model evaluation.

## Dataset

The dataset used for this project is available on Kaggle.

## Regression Models

In this project, we employed three powerful regression techniques for sales prediction:

1. **Logistic Regression:**
    - Logistic Regression is a widely-used algorithm for binary classification tasks, but its application for regression involves predicting a continuous target variable. In our sales prediction context, Logistic Regression might be used to model the probability of a binary outcome, such as whether a sale will happen or not. However, for the sake of this project, we are utilizing it as a regression model by transforming the problem into a binary classification task, e.g., predicting whether sales will exceed a certain threshold.

2. **Random Forest Regression:**
    - Random Forest Regression is an ensemble learning method that combines multiple decision trees to create a robust and accurate predictive model. Each tree in the forest independently predicts the target variable, and the final prediction is an average (for regression tasks) of all the individual tree predictions. Random Forest is known for handling non-linear relationships well and providing robustness against overfitting, making it a suitable choice for predicting complex patterns in sales data.

3. **Gradient Boosting Regression:**
    - Gradient Boosting Regression is another ensemble learning technique that builds a series of weak learners (usually decision trees) sequentially, with each tree correcting the errors of the previous ones. Gradient Boosting is particularly effective for capturing intricate relationships within the data. In our sales prediction project, Gradient Boosting Regression helps optimize the model's performance by iteratively minimizing the residuals, providing accurate predictions and mitigating overfitting.

These regression techniques were chosen based on their strengths in handling various types of data and capturing complex patterns, making them suitable candidates for predicting sales in a dynamic business environment.