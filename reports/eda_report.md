
# Exploratory Data Analysis (EDA) Report

## Project
Credit Card Fraud Detection Using Machine Learning


# Dataset Overview

The dataset contains historical credit card transactions collected from European cardholders. The primary objective is to identify fraudulent transactions using machine learning techniques.


# Dataset Shape

- Number of Rows: **284,807**
- Number of Columns: **31**

The dataset is sufficiently large for training and evaluating machine learning models.


# Number of Features

The dataset consists of:

- 30 input features
- 1 target variable (`Class`)

Most features (V1–V28) have been anonymized using Principal Component Analysis (PCA).


# Missing Values

No missing values were detected in any column.

This eliminates the need for missing-value imputation during preprocessing.


# Duplicate Records

A total of **1,081 duplicate records** were identified.

These duplicate rows should be reviewed and removed before model training to reduce bias and improve model quality.


# Class Distribution

The dataset is highly imbalanced.

- Legitimate Transactions (Class = 0): **284,315**
- Fraudulent Transactions (Class = 1): **492**

Fraudulent transactions account for approximately **0.17%** of all observations.

This imbalance presents one of the major challenges of this project.

# Initial Observations

- The dataset contains only numerical features.
- There are no missing values.
- Duplicate records are present.
- The transaction amount is highly right-skewed.
- The dataset is extremely imbalanced.
- Accuracy alone will not be an appropriate evaluation metric.
- Precision, Recall, F1-score, ROC-AUC, and Precision-Recall AUC will be more suitable evaluation metrics.


# Next Steps

The next phase of the project will focus on:

- Removing duplicate records
- Preparing the dataset for modeling
- Feature scaling
- Splitting the data into training and testing sets
- Building a baseline machine learning model