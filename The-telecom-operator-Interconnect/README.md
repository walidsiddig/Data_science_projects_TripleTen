# Interconnect – Telecom Tariff Recommendation

## Overview
This project develops a machine learning model to recommend the most suitable telecom tariff plan for customers. By aligning tariffs with customer behavior, the company can reduce churn and increase satisfaction.

## Data
- Customer activity data: calls, SMS, and internet usage.  
- Target variable: Chosen tariff plan.  

## Approach
1. **Data Preparation** – cleaned usage logs and formatted features.  
2. **Exploratory Analysis** – compared usage across tariff groups.  
3. **Modeling** – trained Logistic Regression, Decision Tree, Random Forest, and LightGBM models.  
4. **Evaluation** – assessed models using accuracy and F1 score.  

## Results
- Achieved strong classification accuracy.  
- LightGBM performed best, making it the final model of choice.  

## Usage
```bash
pip install -r requirements.txt
jupyter notebook "17-The telecom operator Interconnect.ipynb"
