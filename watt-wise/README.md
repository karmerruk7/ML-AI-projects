# Project Scope of Works:

## Project Overview
**Watt Wise** is a time series forecasting project aimed at predicting and analyzing building energy usage using data on temperature, humidity, occupancy, and operational factors such as HVAC and lighting usage. By leveraging temporal modeling techniques, this project will address seasonality, trends, and other time-dependent patterns in energy consumption.

Dataset: https://www.kaggle.com/datasets/mrsimple07/energy-consumption-prediction

## Project Objectives
- Timeseries analysis of historical data and analysis of trends
- Develop advanced timeseries models which fit the current data
- Deploy the model to production via a cloud service

## Workflow

### **Phase 1: EDA**
- **Data Integrity Check**
    - Load dataset; ensure timestamps are properly formatted and consistent.
    - Identify any missing or duplicated timestamps.

- **Time Series Profiling**
    - Assess data continuity and frequency of timestamps.
    - Explore seasonality, trends, and anomalies in the energy consumption over time.

- **Feature Exploration & Engineering**
    - Investigate temperature, humidity, occupancy, HVAC, lighting usage, and renewable energy over time.
    - Create time-lagged features (e.g., last-hour consumption), rolling means, or day-of-week indicators to capture temporal patterns.

- **Time Series Visualization**
    - Plot consumption trends (daily, weekly, monthly).
    - Identify peaks or dips in consumption relative to HVAC, lighting, holiday, and occupancy changes.

- **Data Preprocessing & Feature Engineering**
    - Fill or interpolate missing time periods where appropriate.
    - Create lagged features, rolling statistics, day-of-week or holiday encodings.
    - Examine potential transformations (log or Box-Cox) if needed to stabilize variance.

### **Phase 2: Model Development (2 Weeks)**

1. **Classical Models**
    - Build ARIMA/SARIMA or similar statistical models, incorporating exogenous variables (HVAC usage, occupancy, etc.).

2. **Machine Learning/Deep Learning Approaches** 
    - Evaluate hybrid methods using scikit-learn or XGBoost with time-based splitting.
    - Test LSTM/GRU neural networks 

3. **Hyperparameter Tuning & Evaluation**
    - Leverage time series cross-validation.
    - Compare performance via RMSE, MAE, MAPE, and R².