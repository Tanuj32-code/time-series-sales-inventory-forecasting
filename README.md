## Time-Series-Sales-Inventory-Forecasting

# Overview
This project focuses on time-series forecasting of retail sales and inventory using multiple statistical and machine learning models. The goal is to improve demand prediction, inventory planning, and replenishment scheduling with high accuracy and actionable insights.

# Models Implemented
- ARIMAX – captures seasonality and external regressors
- Prophet – robust forecasting with trend/seasonality decomposition
- LSTM (Deep Learning) – sequence modeling for complex patterns
- XGBoost – gradient boosting for tabular time-series features

# Key Results
- Forecast Accuracy: 98.76%
- Stockout Risk Alerts: 100% detection
- Inventory Turnover: 7.33K units
- XGBoost achieved the lowest error (MAPE ≈ 1.58%)

# Dashboard (Power BI)
Interactive dashboard includes:
- Actual vs Forecasted Sales
- Inventory Levels & Replenishment Cycles
- Stockout Risk & Turnover Metrics
- Model Comparison (ARIMAX, Prophet, LSTM, XGBoost)
(Dashboard PDF included in repo for quick viewing)

# How to Run
1. Clone the repository:
   '''bash git clone https://github.com/Tanuj32-code/time-series-sales-inventory-forecasting.git
2. Open the notebook in Google Colab or Jupyter.
3. Install required libraries:
   '''bash pip install pandas numpy matplotlib xgboost prophet statsmodels
4. Run cells sequentially to generate forecasts.
5. Open the Power BI dashboard for visualization.

# Business Impact
- Improved forecast accuracy reduces overstock/understock situations.
- Automated replenishment planning ensures smoother supply chain operations.
- Dashboard provides executive-level insights for decision-making.
