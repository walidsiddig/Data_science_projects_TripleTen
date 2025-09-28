# Sweet Lift Taxi – Demand Forecasting

## Overview
Forecasted hourly taxi orders using time series models. The goal was to improve operational efficiency and meet demand proactively.

## Data
- Historical hourly taxi order counts.  
- Target: Number of future orders.  

## Approach
1. **Resampling** – aggregated orders by hour.  
2. **Feature Engineering** – lags, rolling averages.  
3. **Modeling** – regression and ARIMA-style forecasting.  
4. **Evaluation** – RMSE (target ≤ 48).  

## Results
- Achieved RMSE within business requirement.  
- Provided actionable demand forecasts.  

## Usage
```bash
pip install -r requirements.txt
jupyter notebook "13 - Sweet Lift Taxi company.ipynb"
