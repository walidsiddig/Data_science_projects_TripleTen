# Telecom Operator Customer Churn Prediction

## Project Overview
This project focuses on predicting customer churn for a telecom operator using multiple datasets, including contract, demographic, and service usage information. The goal is to identify which customers are likely to leave and provide actionable insights to reduce churn and improve retention strategies.

## Objectives
- Analyze customer behavior across contract, internet, phone, and demographic data.  
- Identify factors that drive customer churn.  
- Build and evaluate machine learning models to predict churn.  
- Provide business recommendations to support customer retention.  

## Tools & Technologies
- Python  
- pandas, numpy – data manipulation & preprocessing  
- matplotlib, seaborn – data visualization  
- scikit-learn – preprocessing, baseline models, evaluation  
- LightGBM – gradient boosting model  

## Key Steps
1. Data Preparation  
   - Merged contract, personal, internet, and phone datasets.  
   - Handled missing values, corrected data types, and engineered features (e.g., tenure).  

2. Exploratory Data Analysis (EDA)  
   - Examined churn by contract type, payment method, internet service, and tenure.  
   - Identified high-risk churn groups.  

3. Feature Engineering  
   - Encoded categorical features (one-hot encoding).  
   - Scaled numerical features.  
   - Addressed class imbalance using class weights.  

4. Modeling & Evaluation  
   - Trained multiple models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, LightGBM.  
   - Evaluated using ROC-AUC as the main metric.  

## Results
- Best model: LightGBM  
- Validation ROC-AUC: 0.996  
- Test ROC-AUC: 0.998  
- Provided insights into contract type, tenure, and payment methods as key churn drivers.  

## Business Impact
The model enables the telecom operator to:  
- Accurately identify customers at risk of leaving.  
- Design targeted retention campaigns.  
- Optimize marketing spend and improve customer loyalty.  

 ## Usage
```bash
pip install -r requirements.txt
jupyter notebook "17-The telecom operator Interconnect.ipynb"
