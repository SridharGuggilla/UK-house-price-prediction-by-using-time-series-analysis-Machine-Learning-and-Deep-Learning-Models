# UK House Price Forecasting using Time Series, Machine Learning and Deep Learning Models

This project focuses on forecasting UK house prices using classical time-series models and machine learning techniques. The aim is to compare model performance and understand why simpler models can outperform complex deep learning approaches on highly autocorrelated economic data.

---

##  Project Overview

- Dataset: UK House Price Index (UK HPI)
- Frequency: Monthly
- Period: 1978 – 2024
- Target Variable: Average House Price (£)
- Scope: United Kingdom (national-level analysis)

---

##  Models Implemented

- Linear Regression with Lag Features (Autoregressive)
- ARIMA
- SARIMA
- LSTM (Deterministic setup)

Each model is trained and evaluated on the same train–test split to ensure fair comparison.

---

##  Methodology

1. Data Cleaning & Preprocessing  
   - Filtering UK-level data  
   - Handling missing values  
   - Log transformation for variance stabilisation  

2. Feature Engineering  
   - Lag-based features for Linear Regression  
   - Time-aware train/test split  

3. Model Training  
   - ARIMA & SARIMA using statsmodels  
   - LSTM using TensorFlow/Keras with deterministic configuration
   - Linear Regression

4. Evaluation  
   - RMSE  
   - MAE  
   - MSE  
   - R²  

5. Forecasting  
   - Recursive multi-step forecasting  
   - 12–24 month horizon  

---

##  Key Findings

- Linear Regression with lag features achieved the lowest RMSE
- SARIMA captured seasonality but struggled with long-term trend
- LSTM learned patterns effectively but did not outperform simpler models
- High autocorrelation and strong trend in UK house prices favour low-variance models

---

##  Technologies Used

- Python
- Pandas, NumPy
- scikit-learn
- statsmodels
- TensorFlow
- Matplotlib & Plotly

---



