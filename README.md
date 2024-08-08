# Credit Card Defaulter Detection using Random Forest
This repository contains a machine learning project aimed at detecting potential credit card defaulters using a Random Forest classifier. The goal is to accurately predict whether a customer will default on their credit card payment based on historical data.

# Table of Contents
### 1. Project Overview
### 2. Dataset
### 3. Modeling
### 4. Evaluation
### 5. Contributing
### 6. License
# Project Overview
This project aims to build a predictive model to identify customers who are likely to default on their credit card payments. By leveraging the Random Forest algorithm, the model analyzes various features related to customer behavior, credit history, and other financial factors.

#  Dataset
The dataset includes 4,600 samples and 58 features, likely covering various aspects of customer financial data. These features may include payment history, credit utilization, demographic information, and more.

## Number of Samples: 4,600
## Number of Features: 58
## Target Variable:
 A binary column indicating whether the customer defaulted (1) or not (0).

# Modeling
The project focuses on using the Random Forest algorithm, a robust and versatile method known for its high accuracy and ability to handle large datasets with many features.

# Steps:
### Data Preprocessing: 
Handling missing values, feature scaling, and encoding categorical variables.
### Model Training: 
Using the Random Forest classifier to train on the preprocessed data.
### Hyperparameter Tuning: 
Optimizing the Random Forest parameters for the best performance.
# Evaluation
The performance of the Random Forest model is evaluated using the following metrics:

## Accuracy: 
Overall correctness of the model.
## Precision: 
Correctness of positive predictions.
## Recall: 
Ability to find all positive samples.
## F1-Score:
Harmonic mean of precision and recall.
## ROC-AUC Score: 
Measure of the model's ability to distinguish between classes.
# Contributing
Contributions are welcome! If you have suggestions or find any issues, feel free to open an issue or submit a pull request.

# License
This project is licensed under the MIT License. See the LICENSE file for more details.
