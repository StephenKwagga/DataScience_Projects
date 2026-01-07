# Task 5: Personal Loan Acceptance Prediction (Marketing Dataset)

# Objective
Predict which customers are likely to accept a personal loan offer based on marketing campaign data.

# Dataset
- Source: Bank Marketing Dataset (UCI Repository)  
- Target: Personal_Loan  
- Key Features: Age, Job, Marital, Education, Housing, Loan, Campaign metrics

# Approach
1. Preprocessing
   - Cleaned irrelevant fields  
   - Encoded job, marital, education using One-Hot Encoding

2. Exploratory Data Analysis (EDA)
   - Countplot of loan acceptance  
   - Boxplot of age vs job

3. Modeling
   - Used Logistic Regression
   - Evaluated with Accurancy: 87%, AUC Score: 0.85 and confusion matrix

# 🔍 Key Insights
- Campaign success is influenced by the number of contacts — customers contacted more than once showed higher conversion.
- Job type and education significantly influence acceptance — professionals and graduates were more responsive.
- Age group 30–50 showed the highest acceptance, likely due to financial stability.
- The model highlights marketing segments that can be targeted more precisely for better ROI.