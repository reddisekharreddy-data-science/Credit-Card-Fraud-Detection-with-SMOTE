# Credit Card Fraud Detection using SMOTE

Introduction:

Credit card fraud detection is a critical application of machine learning, as financial fraud results in significant monetary losses. However, fraud detection datasets are often highly imbalanced, making it challenging to train effective models. This project applies Synthetic Minority Over-sampling Technique (SMOTE) to handle class imbalance and improve fraud detection.

Dataset:

Dataset Name: Credit Card Fraud Detection Dataset

Source: Kaggle - Credit Card Fraud Detection

Description: The dataset contains credit card transactions made by European cardholders in September 2013. It includes 284,807 transactions with 492 fraud cases (0.17% fraud rate).

Features: 30 numerical input variables (V1 to V28), Time, and Amount, with a binary target variable (0: Non-fraud, 1: Fraud).

Problem Statement:

Detecting fraudulent transactions in a highly imbalanced dataset using machine learning techniques and addressing the imbalance problem with SMOTE.

Approach

Data Preprocessing:

Load the dataset and check for missing values.

Separate features (X) and target variable (y).

Perform feature scaling.

Handling Imbalance:

Use SMOTE to generate synthetic samples for the minority (fraud) class.

Model Training & Evaluation:

Train a classification model (Logistic Regression, Random Forest, etc.).

Evaluate model performance using Precision, Recall, F1-score, and AUC-ROC.

Results:

Applied SMOTE to balance the dataset.

Improved fraud detection performance compared to the imbalanced dataset.

Performance metrics were analyzed to ensure model robustness.
