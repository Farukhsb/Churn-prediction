# Churn-prediction
# Telco Customer Churn Prediction

## Description

This project aims to predict customer churn in a telecommunications company using machine learning techniques. Customer churn, or customer attrition, refers to the phenomenon where customers stop doing business with a company. Predicting churn is crucial for businesses to identify customers at risk of leaving and take proactive measures to retain them.

## Overview

The dataset used in this project contains information about telecom customers, including demographics, services subscribed, and churn status. We preprocess the data, train several machine learning models, and evaluate their performance to predict customer churn.

# Model Evaluation

## kNN Model

- **Accuracy:** 76.95%
- **Precision (Class 0):** 83%
- **Recall (Class 0):** 86%
- **F1-score (Class 0):** 84%
- **Precision (Class 1):** 58%
- **Recall (Class 1):** 53%
- **F1-score (Class 1):** 56%
- **AUC-ROC:** 69.59%

The kNN model achieved an accuracy of 76.95% and demonstrated decent performance in predicting both churned and non-churned customers. However, its AUC-ROC score indicates moderate discriminatory power.

## Logistic Regression Model

- **Accuracy:** 80.93%
- **Precision (Class 0):** 84%
- **Recall (Class 0):** 91%
- **F1-score (Class 0):** 87%
- **Precision (Class 1):** 69%
- **Recall (Class 1):** 54%
- **F1-score (Class 1):** 61%
- **AUC-ROC:** 72.60%

The Logistic Regression model outperformed the kNN model with an accuracy of 80.93%. It showed higher precision, recall, and F1-score for both classes, indicating better overall performance.

## Decision Tree Model

- **Accuracy:** 78.56%
- **Precision (Class 0):** 80%
- **Recall (Class 0):** 94%
- **F1-score (Class 0):** 87%
- **Precision (Class 1):** 71%
- **Recall (Class 1):** 36%
- **F1-score (Class 1):** 48%
- **AUC-ROC:** 65.24%

The Decision Tree model achieved an accuracy of 78.56% but showed lower recall for class 1, indicating challenges in correctly predicting churned customers.

### Summary

- The Logistic Regression model demonstrated the best overall performance with the highest accuracy and balanced precision, recall, and F1-score for both classes.


## Usage

To use this project, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/farukhsb/Churn-prediction.git

