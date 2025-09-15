# Customer Churn Prediction  

## Overview  
This project predicts **customer churn** using the IBM Telco Customer Churn dataset. Churn refers to customers who discontinue their service within a given period. Understanding and predicting churn helps businesses create effective **customer retention strategies**, ultimately reducing revenue loss and strengthening long-term loyalty.  

The notebook demonstrates a complete **machine learning workflow**, covering data exploration, preprocessing, feature engineering, model training, and evaluation.  

---

## Dataset  
The dataset used in this project is the **IBM Telco Customer Churn dataset**, available on Kaggle. It contains information about 7,043 customers with 21 attributes, each representing either demographic details, subscribed services, or account information. Each row corresponds to a single customer, while the target variable, **Churn**, indicates whether the customer discontinued the service within the last month.  

The dataset includes a wide range of customer information. Service-related attributes describe whether customers subscribed to phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming services such as TV and movies. Account-related attributes capture details such as the length of time a customer has been with the company (tenure), the type of contract (month-to-month, one year, or two years), the chosen payment method, paperless billing status, monthly charges, and total charges. Demographic attributes include gender, senior citizen status, and whether the customer has a partner or dependents.  

This combination of demographic, behavioral, and financial data makes the dataset well-suited for churn prediction tasks, as it reflects many of the factors businesses consider when analyzing customer loyalty.  

---

## Workflow  

### 1. Data Preparation  
- Data cleaning, handling missing values, correcting data types.  
- Duplicate checks and outlier detection.  
- Encoding categorical variables (label encoding, one-hot encoding).  
- Feature scaling for numerical variables.  

### 2. Exploratory Data Analysis (EDA)  
- Visualized churn distribution (revealing class imbalance).  
- Explored relationships between churn and different features (demographics, services, and account details).  
- Analyzed correlations between features and churn.  

### 3. Modeling  
- Dataset split into training and testing subsets.  
- Models implemented and compared:  
  - **K-Nearest Neighbors (KNN)**  
  - **Logistic Regression**  
  - **Decision Tree Classifier**  

### 4. Evaluation  
Since the dataset is imbalanced, multiple evaluation metrics were applied beyond accuracy:  
- Confusion Matrix  
- Precision, Recall, F1-Score  
- ROC Curve & AUC  
- Precision-Recall Curve & AUC  

---

## Skills Demonstrated  
- **Data Wrangling & Cleaning** – preparing high-quality structured data.  
- **EDA & Visualization** – uncovering churn patterns and customer insights.  
- **Feature Engineering** – encoding, scaling, and transformations.  
- **Model Development** – training and comparing classification algorithms.  
- **Evaluation Metrics** – addressing imbalanced classification challenges.  
- **Communication** – presenting findings clearly with visuals and structured explanations.  

---
