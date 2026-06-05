# Credit Card Fraud Detection Using Machine Learning

## Overview
This project builds a machine learning model to detect fraudulent credit card transactions. The goal is to identify fraudulent activity in highly imbalanced datasets using classification algorithms and evaluation metrics that focus on detection performance.

## Problem Statement
Credit card fraud is rare but costly. Traditional accuracy is not enough for evaluation due to class imbalance, so this project focuses on improving fraud detection using precision, recall, and ROC-AUC.

## Dataset
The dataset used contains anonymized credit card transactions labeled as fraudulent or legitimate.

> Note: The dataset is not included in this repository due to size limitations. It can be accessed from Kaggle:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Project Workflow

### 1. Data Preprocessing
- Handled missing values (if any)
- Scaled numerical features
- Addressed class imbalance

### 2. Exploratory Data Analysis (EDA)
- Distribution of fraud vs non-fraud transactions
- Correlation analysis
- Feature insights

### 3. Feature Engineering
- Data normalization
- Feature selection techniques

### 4. Model Building
The following machine learning models were implemented:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

### 5. Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

## Results
The models were compared to determine the best-performing approach for fraud detection. Emphasis was placed on maximizing recall to reduce false negatives (missed fraud cases).

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Key Takeaways
- Accuracy alone is not sufficient for imbalanced datasets
- Ensemble methods (Random Forest) often perform better in fraud detection
- Feature scaling and preprocessing significantly impact performance

## Skills Demonstrated
- Machine Learning
- Data Preprocessing
- Classification Modeling
- Imbalanced Dataset Handling
- Model Evaluation
- Data Visualization

## Author
Oluwatobi Banjo

## License
This project is for educational and portfolio purposes only.
