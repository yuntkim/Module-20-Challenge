# Module 12 Report Template

## Overview of the Analysis

In this analysis, I analyzed lending data to build a logistic regression model for predicting loan status as "healthy" or "high-risk." The process included data exploration, model training, and evaluation.

## Results

The model performed well in predicting "healthy loans" but had room for improvement in predicting "high-risk loans."

Classification Report:
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384

## Summary

In summary, the logistic regression model did really well at predicting loans that are "healthy," but it could do better at predicting "high-risk" loans. We took steps to handle the imbalance in the data, which showed how crucial it is to make accurate predictions for both types of loans in this kind of task.