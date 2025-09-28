# Mobile Carrier Megaline Plan Recommendation

## Description
This project develops a classification model to recommend whether a subscriber should use the "Smart" or "Ultra" plan based on their monthly behavior.

## Dataset
The dataset includes information about customer usage:  
- Calls  
- Minutes  
- Messages  
- Internet data usage  

## Methodology
- **Data Preprocessing**: Cleaned and standardized user activity data.  
- **Modeling**: Trained Decision Trees, Random Forests, and Logistic Regression.  
- **Evaluation**: Compared models using accuracy and cross-validation.  

## Results
- Achieved accuracy ≥ 0.75.  
- Best-performing model selected for final evaluation.  

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook "7 - Mobile carrier Megaline.ipynb"
