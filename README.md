**Project Overview**
This project focuses on predicting loan default risk using customer financial and demographic data. The analysis includes data cleaning, feature engineering, model building, and evaluation. The goal is to provide actionable insights to improve lending decisions and minimize default rates.

**Dataset**
The dataset comprises anonymized customer profiles containing fields such as age, annual income, credit score, loan amount, employment years, debt-to-income ratio, loan purpose, and default status.

**Steps Undertaken**
1. Data Loading & Exploration
Imported data and performed exploratory data analysis (EDA)
Assessed data quality, missing values, and feature distributions

2. Feature Engineering
Created derived features like income-to-loan ratio and credit utilization
Encoded categorical variables for model compatibility

3. Model Development
Applied train-test split and trained a Random Forest Classifier
Evaluated model performance using classification metrics

4. Visualization
Performed comprehensive visual exploration including:
Credit Score distribution by default status (Boxplot)
Customer age distribution (Histogram)
Correlation heatmap for numeric features
Loan amount versus annual income by default status (Scatter Plot)
Loan purpose counts segmented by default status (Countplot)
Pairwise relationships among key variables (Pairplot)
Visualizations provide insight into feature impact and support interpretability of the model.

**5. Results**
Achieved strong predictive performance in identifying high-risk borrowers
Feature importance analysis highlighted critical factors influencing defaults

**Technologies Used**
Python: pandas, numpy, matplotlib, seaborn, scikit-learn
Google Colab
