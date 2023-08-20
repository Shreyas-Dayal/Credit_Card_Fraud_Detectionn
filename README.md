## Credit-Card-Fraud-Detection

This repository contains a project focused on Credit Card Fraud Detection using various machine learning algorithms, including Logistic Regression, Decision Tree, and Random Forest. The goal of this project is to develop a model that can effectively identify fraudulent credit card transactions.

# Introduction
Credit card fraud is a significant concern in the financial industry. The ability to accurately detect fraudulent transactions is crucial to prevent financial losses for both consumers and credit card companies. In this project, we aim to develop machine learning models capable of identifying fraudulent credit card transactions by analyzing various transaction features.

# Algorithms Used
We have employed the following machine-learning algorithms for this project:

# Logistic Regression: 
Logistic Regression is a standard classification algorithm that's often used for binary classification tasks. We've used it as one of the baseline models for fraud detection.

# Decision Tree:
Decision Trees are a versatile algorithm used for both classification and regression tasks. In our project, we've utilized Decision Trees to capture complex relationships within the data.

# Random Forest:
Random Forest is an ensemble learning method that combines multiple Decision Trees to improve prediction accuracy and control overfitting.

# Data Preprocessing
Proper data preprocessing is essential for model performance. We've carried out necessary steps such as data cleaning, handling missing values, and converting categorical variables into numerical ones.

# Exploratory Data Analysis (EDA)
Before building the models, we conducted exploratory data analysis to gain insights into the data distribution, identify potential outliers, and understand feature correlations. EDA helps in making informed decisions during feature selection and model training.

# Handling Imbalanced Data
Credit card fraud detection datasets are often highly imbalanced, with the majority of transactions being legitimate. To address this, we've implemented the K-Nearest Neighbors (KNN) algorithm to oversample the minority class and balance the dataset, improving model performance on detecting fraudulent transactions.

# Model Performance
The success of our models is evaluated primarily based on their ability to correctly identify fraudulent transactions. We've achieved a recall value of 0.833, which indicates that the models are effectively capturing a large portion of actual fraudulent cases.
