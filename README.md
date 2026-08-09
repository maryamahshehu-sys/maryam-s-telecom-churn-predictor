# Telecom Churn Predictor
## Project Overview
This project uses machine learning to predict whether a telecommunications customer is likely to churn.
Customer churn is an important business problem because identifying customers who are likely to leave can help telecommunications companies take preventive actions and improve customer retention.

# Objective
The objective of this project is to develop a machine learning classification model that predicts customer churn based on customer demographic, account, service, and billing information.

## Dataset
The project uses the Telco Customer Churn dataset, which contains information about telecommunications customers, their services, account information, and whether they churned.

## Project Workflow

The project follows these steps:
1. Data Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Categorical Variable Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Model Comparison

## Machine Learning Models
Three classification models were evaluated:
1. Logistic Regression
2. Decision Tree
3. Random Forest

## Model Results
1. Logistic Regression
   Accuracy: 80.45%
   Churn Precision: 65%
   Churn Recall: 57%
   Churn F1-Score: 61%

2. Decision Tree
   Accuracy: 71.64%
   Churn Precision: 47%
   Churn Recall: 46%
   Churn F1-Score: 46%

3. Random Forest
   Accuracy: 78.82%
   Churn Precision: 62%
   Churn Recall: 51%
   Churn F1-Score: 56%

## Best Performing Model
Logistic Regression achieved the best overall performance among the three models evaluated, with an accuracy of 80.45%.
It also achieved the highest precision, recall, and F1-score for the churn class.

## Key Findings
The analysis showed that customer characteristics and service-related factors can be useful in predicting customer churn.
The final model can help telecommunications companies identify customers who may be at risk of leaving and potentially take targeted retention actions.

## Technologies Used
1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
6. Scikit-learn
7. Jupyter Notebook

## Author
Maryamah
