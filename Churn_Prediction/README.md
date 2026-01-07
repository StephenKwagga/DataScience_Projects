# Task 3: Customer Churn Prediction (Churn Modelling Dataset)

# Objective
Identify customers who are likely to leave the bank based on personal and account data.

# Dataset
- Source: Churn_Modelling.csv  
- Target: Exited
- Features: Geography, Gender, Credit Score, Age, Balance, Tenure, NumOfProducts

# Approach
1. Data Processing
   - One-Hot Encoding for Geography, Gender
   - Feature scaling applied
   
2. Exploratory Data Analysis (EDA)
   - Count Plots – For categorical variables like loan status, gender, and education.
   - Box Plots – To understand distribution of loan amount and income by approval status.
   - Bar Charts – To compare approval rates across different categories.

3. Modeling
   - Trained Logistic Regression classifier - Accuracy: 86.60%
   - Analyzed feature importance

4. Evaluation
   - Accuracy, Precision, Confusion Matrix

# 🔍 Key Insights
- Customers with fewer products (especially 1) are more likely to churn.
- Older customers (age 50+) are at a higher risk of churning, especially with high balances and low   engagement.
- Geography (especially customers from Germany) showed higher churn rates compared to France or Spain.
- Feature importance highlighted Age, Balance, and Num Of Products as top drivers of churn.