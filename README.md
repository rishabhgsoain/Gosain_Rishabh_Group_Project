# SmartRetail: Walmart Sales Forecasting

This project analyzes Walmart’s historical weekly sales data to build forecasting models, detect anomalies, and study the impact of holidays and economic factors. The workflow includes data cleaning, feature engineering, statistical modeling, machine learning models, and evaluation.

---

## Overview

The goal of this project is to:

- Forecast weekly sales at the store level  
- Compare ARIMA, Prophet, XGBoost, and LSTM models  
- Analyze seasonality, trends, and holiday effects  
- Build engineered features such as lags, rolling windows, and economic indicators  

All work is performed in Python using Jupyter notebooks.

---

## Methods Used

### Data Preparation
- Merging sales, features, and store metadata  
- Handling missing values  
- Creating calendar, holiday, lag, and rolling features  
- Scaling economic indicators per store  

### Forecasting Models
- ARIMA (classical time-series baseline)  
- Prophet (trend and seasonality model)  
- XGBoost Regressor (feature-based machine learning)  
- LSTM (neural network for sequential learning)

### Evaluation Metrics
- RMSE  
- MAE  

---

pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
prophet
pmdarima
tensorflow
Results Summary

Prophet typically achieved the lowest RMSE, followed by XGBoost and ARIMA.
The LSTM model performed worse due to limited historical data for training.
Plots and tables comparing the models are included in the notebook.

