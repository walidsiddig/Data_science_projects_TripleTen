# The Film Junky Union – Sentiment Analysis

## Overview
Built NLP models to classify movie reviews as positive or negative. The aim was to provide automated sentiment analysis for film feedback.

## Data
- Movie reviews text.  
- Target: Sentiment (positive/negative).  

## Approach
1. **Text Preprocessing** – lemmatization, tokenization, TF-IDF.  
2. **Modeling** – Logistic Regression, Random Forest, LightGBM.  
3. **Evaluation** – Accuracy, F1, ROC-AUC.  

## Results
- Best model achieved strong F1 and accuracy.  
- Ready for deployment in review analysis.  

## Usage
```bash
pip install -r requirements.txt
jupyter notebook "14 - The Film Junky Union.ipynb"
