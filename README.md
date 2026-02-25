# Customer Churn Prediction using Machine Learning

##  Project Overview
This project develops an end-to-end Machine Learning pipeline to analyze customer behavior and predict churn.  
The goal is to identify customers likely to leave a service so businesses can take preventive action.

## Problem Statement
Customer churn significantly impacts revenue.  
This project aims to:
- Analyze customer behavior patterns
- Predict churn using classification models
- Improve prediction performance through model optimization

##  Dataset
- Dataset: Telco / Bank Customer Churn Dataset
- Records: ~7,000+
- Features: Demographics, account information, service usage
- Target Variable: `Churn` (Yes/No)

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Imbalanced-learn (SMOTE)

## Machine Learning Pipeline

# Data Preprocessing
- Removed irrelevant ID columns
- Handled missing values using median imputation
- Converted categorical variables using one-hot encoding
- Encoded target variable
- Applied feature scaling (StandardScaler)

# Handling Class Imbalance
- Applied SMOTE to balance churn and non-churn classes

# Model Training
- Logistic Regression (Baseline Model)
- Random Forest Classifier

# Hyperparameter Tuning
- GridSearchCV with 5-fold cross-validation
- Optimized F1-score

# Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix


## 📈 Results
- Baseline Model Accuracy: ~ 0.83%
- Optimized Model Accuracy: ~ 0.95%
- Improved performance after hyperparameter tuning


---

## 📂 Project Structure
