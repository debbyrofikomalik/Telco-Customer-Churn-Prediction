# Telco Customer Churn Prediction

This repository presents a comprehensive machine learning project aimed at predicting customer churn for a telecommunications company. The project demonstrates a full end-to-end workflow, including data preprocessing, feature engineering, model training, evaluation, and extraction of business insights.

## Project Overview

The main objective is to identify customers at risk of churn to enable proactive retention strategies. The dataset includes demographic, account, and service-related information.

### Workflow

1. **Data Cleaning and Exploration**
   - Handle missing values
   - Convert categorical features to numerical values
   - Scale numerical features

2. **Feature Engineering**
   - Label encoding for binary categorical features
   - One-hot encoding for multi-category features
   - MinMax scaling for numerical features

3. **Model Training and Evaluation**
   - Machine learning models used:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Decision Tree Classifier
   - Evaluation metrics:
     - Confusion Matrix
     - Accuracy Score
     - ROC Curve and AUC
     - Precision-Recall Curve and F1 Score
     - Feature Importance / Feature Weights

4. **Business Insights**
   - Key factors influencing churn: tenure, contract type, monthly charges, and service subscriptions
   - Strategic recommendations for customer retention
