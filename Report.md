# Credit Card Fraud Detection - Project Report

## 1. Introduction

Credit card fraud detection is a critical problem in financial security. This project applies machine learning techniques to classify credit card transactions as fraudulent or legitimate.

## 2. Dataset Overview

- 286,791 rows
- 31 columns (including features, amount, and class label)
- Target: `Class` (0 = legitimate, 1 = fraud)
- Features (`V1` to `V28`) are anonymized for privacy.

## 3. Data Exploration

- Examined the first and last few rows to understand the structure.
- Checked for missing values:
  - Several features have null values.
- Data is highly imbalanced (far more legitimate than fraudulent cases).

## 4. Preprocessing

- Handled missing values using `SimpleImputer`.
- Applied feature scaling where necessary.
- Used SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.

## 5. Model Selection

Chose Logistic Regression for initial classification due to its interpretability and effectiveness for binary classification.

## 6. Training and Evaluation

- Split dataset into training and testing sets.
- Trained Logistic Regression on balanced data.
- Evaluated with accuracy score.
- Observed metrics:
  - High accuracy after balancing, but further exploration of precision/recall/F1 is recommended due to the imbalanced nature.

## 7. Key Findings

- Balancing the dataset is crucial for fraud detection.
- Logistic Regression can serve as a strong baseline.
- Data preprocessing and exploratory analysis are essential steps.

## 8. Future Work

- Experiment with advanced models (Random Forest, XGBoost, Neural Networks).
- Hyperparameter tuning.
- Explore explainability (feature importance).
- Deploy model for real-time fraud detection.

## 9. References

- scikit-learn documentation
- imbalanced-learn documentation
