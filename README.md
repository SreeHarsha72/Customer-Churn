# E-Commerce Customer Churn Prediction

## Project Overview

In this project, I built an end-to-end machine learning pipeline to predict whether an e-commerce customer is likely to churn. The objective is to help businesses identify customers who are at risk of leaving so they can take proactive retention measures.

I followed a complete data science workflow including data cleaning, exploratory data analysis (EDA), feature preprocessing, model building, evaluation, and business interpretation.

## Project Goal

The goal of this project is to:
- Understand customer behavior
- Identify factors that influence customer churn
- Compare multiple machine learning models
- Predict future customer churn
- Provide business insights that can improve customer retention


## Dataset

The dataset contains customer demographic information, purchasing behavior, account details, and service usage, along with a target variable indicating whether the customer has churned.

Features include:
- Customer demographics
- Tenure
- Preferred payment method
- Order history
- Cashback amount
- Satisfaction score
- Warehouse distance
- Number of devices
- Complaint history
- Total spending

Target variable: Churn (Yes / No)


# Project Workflow

## 1. Data Loading

I loaded the dataset into Pandas and inspected:
- Dataset size
- Data types
- Missing values
- Duplicate records
- Overall data quality


## 2. Data Cleaning
I prepared the dataset by:
- Cleaning column names
- Handling missing values
- Fixing inconsistent data
- Preparing categorical and numerical features
- Creating a clean dataset for modeling

## 3. Exploratory Data Analysis (EDA)

I explored customer behavior to understand patterns related to churn.

The analysis included:
- Distribution of customer attributes
- Churn distribution
- Numerical feature analysis
- Categorical feature analysis
- Business insights from customer behavior

## 4. Feature Engineering

I prepared the features using a preprocessing pipeline.

The pipeline included:
- Missing value imputation
- One-Hot Encoding for categorical variables
- Standard Scaling for numerical variables
- Column Transformer
- Scikit-learn Pipeline

This makes the workflow reusable and prevents data leakage.


## 5. Model Building

I trained and compared multiple classification models.

### Logistic Regression

Logistic Regression provides a simple and reliable baseline for classification tasks, though its performance may be limited when dealing with complex, nonlinear relationships.


### Random Forest

Random Forest is a powerful and reliable machine learning algorithm that captures complex patterns while reducing overfitting, although it is less interpretable and requires more training time.


### XGBoost

XGBoost delivers excellent predictive performance by capturing complex relationships in structured data, though it requires more computational resources and careful hyperparameter tuning.

# Model Evaluation

I evaluated the models using several classification metrics.

Evaluation metrics include:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

Comparing multiple metrics provides a better understanding of model performance than relying on accuracy alone.


# Technologies Used
Python, Pandas, NumPy, Matplotlib, Scikit-learn, XGBoost

### Model Pipeline

- Pipeline
- ColumnTransformer
- OneHotEncoder
- StandardScaler
- SimpleImputer



# ✅ Conclusion

In this project, I developed a complete customer churn prediction workflow, starting from raw data and ending with predictive models and business insights. By comparing multiple machine learning algorithms and following a structured pipeline, I gained practical experience in solving a real-world classification problem while building a solution that can support data-driven customer retention strategies.
