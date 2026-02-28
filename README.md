# Student Performance Prediction using Logistic Regression (From Scratch)

## Project Overview
This project implements Logistic Regression from scratch using NumPy to predict whether a student will pass or fail based on demographic and academic features.

## Objective
Predict student pass/fail outcome (G3 ≥ 10) using a custom-built logistic regression model.

## What I Implemented
- Sigmoid function
- Cross-entropy (logistic) loss
- Gradient descent optimization
- One-hot encoding for categorical variables
- Train-test split
- Feature scaling using StandardScaler
- Confusion matrix evaluation

## Data Leakage Prevention
Removed highly correlated features (G1, G2, G3) to ensure realistic evaluation.

##  Results
- Train Accuracy: ~76%
- Test Accuracy: ~71%

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn (for preprocessing & metrics)
- Matplotlib
- Seaborn

##  Dataset
Student Performance dataset (UCI Machine Learning Repository)

---

This project helped strengthen my understanding of:
- Logistic loss
- Gradient descent
- Feature correlation
- Data leakage
- Model evaluation
