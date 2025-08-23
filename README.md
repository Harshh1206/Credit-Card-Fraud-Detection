# Credit-Card-Fraud-Detection
Credit Card Fraud Detection
📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using a machine learning pipeline. The goal is to create a reliable fraud detection model that handles missing data, imbalanced classes, and achieves strong predictive performance.

The workflow includes:

Data cleaning with KNN Imputer

Balancing imbalanced data using SMOTE

Training Logistic Regression as the classifier

⚙️ Project Workflow

Data Cleaning

Missing values were handled using KNN Imputer, which imputes based on similarity with other records.

Duplicates were removed and features were normalized.

Data Balancing

The dataset was highly imbalanced.

Applied SMOTE (Synthetic Minority Oversampling Technique) to balance the class distribution by creating synthetic fraud samples.

Model Training

Used Logistic Regression as the model due to its interpretability and efficiency.

Applied regularization to avoid overfitting.

Model Evaluation

Achieved 98% accuracy on both training and testing sets.

Additional evaluation metrics (important for fraud detection):

Precision – to minimize false fraud alerts

Recall – to capture maximum fraud cases

F1-score – balance between Precision & Recall

ROC-AUC – to measure overall separability

🚀 Results

Logistic Regression with KNN Imputer + SMOTE gave:

98% accuracy on training and testing sets

Significant improvement in recall compared to training on the imbalanced dataset

Robust fraud detection with reduced false negatives

🛠️ Technologies Used

Python

Pandas, NumPy – Data preprocessing

Scikit-learn – KNN Imputer, Logistic Regression, evaluation metrics

Imbalanced-learn (SMOTE) – Data balancing

Matplotlib, Seaborn – Visualizations

📊 Future Enhancements

Experiment with advanced models (Random Forest, XGBoost, Neural Networks)

Deploy the trained model using Flask/FastAPI for real-time fraud detection

Build an interactive dashboard for transaction monitoring
