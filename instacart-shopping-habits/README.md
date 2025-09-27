# Instacart Insights: Cleaning Data & Exploring Customer Shopping Habits

## Project Overview
This project analyzes Instacart grocery order data to understand customer shopping habits.  
The dataset is a reduced version of the 2017 Instacart Kaggle dataset, with added missing and duplicate values.  

The goal is to:
1. Clean and preprocess the data.  
2. Explore ordering behavior by time, day, and frequency.  
3. Identify popular products and reorder patterns.  

---

## Dataset
Files used:
- `instacart_orders.csv` — order details  
- `products.csv` — product metadata  
- `aisles.csv` — aisle categories  
- `departments.csv` — department categories  
- `order_products.csv` — items in each order  

---

## Analysis Tasks
- Validate data ranges (`order_hour_of_day`, `order_dow`).  
- Plot ordering trends by hour and weekday.  
- Examine order frequency (`days_since_prior_order`).  
- Compare ordering times across days (e.g., Wednesday vs. Saturday).  
- Identify most frequently ordered and reordered products.  
- Explore shopping cart patterns (first items added, order size).
  
## Requirements
Install dependencies with:
```bash
pip install -r requirements.txt
