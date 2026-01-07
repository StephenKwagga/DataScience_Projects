# Task 4: Predicting Insurance Claim Amounts (Regression)

# Objective
Predict medical insurance charges based on personal attributes using regression.

# Dataset
- Source: Medical Insurance Cost Dataset  
- Target: charges  
- Features: Age, BMI, Smoking Status, Children, Region, Sex

# Approach
1. Preprocessing
   - Encoded categorical features (e.g., smoker, region)  
   - Checked for correlations

2. Exploratory Data Analysis (EDA)
   - Scatter Plots – Charges vs Age and Charges vs BMI, colored by smoker status.
   - Correlation Heatmap – To assess relationships between features like age, BMI, and charges.

These visualizations revealed that smoking status, age, and BMI strongly influence medical charges.


2. Modeling
   - Trained Linear Regression Model  
   - Evaluated using MAE and RMSE

3. Performance
   - MAE: $4160  
   - RMSE: $6319

# 🔍 Key Insights
- Smokers are charged significantly higher premiums — up to 3x more than non-smokers.
- BMI above 30 (obese) increases charges noticeably, especially for smokers.
- Age is positively correlated with charges — older individuals tend to claim more.
- Despite a good model fit, the RMSE of $6,319 suggests more advanced models (like Random Forest or XGBoost) could reduce error.