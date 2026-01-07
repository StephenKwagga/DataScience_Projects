# Task 2: Credit Risk Prediction (Loan Default Classification)

# Objective
Predict if a loan applicant is likely to default using a supervised classification model.

# Dataset
- Source: Loan Prediction Dataset (Kaggle)
- Target: Loan_Status
- Key Features: Gender, Married, Education, ApplicantIncome, LoanAmount, Credit_History

# Approach
1. Data Cleaning
   - Filled missing values (LoanAmount, Credit_History, etc.)
   - Encoded categorical features using Label Encoding.

2. Exploratory Data Analysis (EDA)
   - Count Plots – For categorical variables like loan status, gender, and education.
   - Box Plots – To understand distribution of loan amount and income by approval status.
   - Bar Charts – To compare approval rates across different categories.

3. Modeling
   - Model: Decision Tree Classifier  
   - Achieved Accuracy: 69%

4. Evaluation
   - Confusion Matrix & Classification Report used for performance check.

# 🔍 Key Insights
- Credit History is a strong predictor.
- Education and Income also influence loan approval.
- Dataset had some imbalance affecting precision.