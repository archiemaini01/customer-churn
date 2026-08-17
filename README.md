# Customer Churn Prediction

## Project Overview

This project focuses on predicting customer churn using machine learning.

A Random Forest classification model was trained using customer information such as age, tenure, monthly bill, support calls, contract type, payment method, family plan, and data usage.

The goal is to identify customers who are likely to churn so that the business can take appropriate retention actions.

## Machine Learning Model

The project uses a **Random Forest Classifier**, an ensemble learning method for classification.

The dataset was divided into training and testing sets using a **75/25 split**.

The Random Forest model was tuned by increasing the number of trees from 100 to 200.

## Model Results

The tuned model achieved the following results on the test set:

- **Accuracy:** 95.2%
- **Precision:** 95.83%
- **Recall:** 92%
- **F1 Score:** 93.88%

## Confusion Matrix

The confusion matrix results were:

- **True Negatives:** 73
- **False Positives:** 2
- **False Negatives:** 4
- **True Positives:** 46

The model correctly identified most customers who churned while making relatively few incorrect predictions.

## Business Usefulness

The model can help a business identify customers who are at risk of churning and prioritize retention efforts.

Recall is particularly important because missing a customer who actually churns may result in a lost opportunity to retain them.

## Conclusion

The tuned Random Forest model provides a strong approach for predicting customer churn. Further improvements could include additional model tuning and monitoring model performance as new customer data becomes available.

## Notebook

The complete project is available in the included Google Colab/Jupyter Notebook.
