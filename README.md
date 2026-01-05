# UK-house-price-prediction-by-using-time-series-analysis-Machine-Learning-and-Deep-Learning-Models
This project focuses on forecasting UK house prices using multiple statistical and machine-learning models. The goal is to analyse long-term price behaviour, identify underlying patterns, and evaluate which model offers the highest predictive accuracy.

---

## Project Summary
This project predicts future UK house prices using monthly data from the UK House Price Index (1995–2024).  
Several models were built and evaluated to identify the most accurate forecasting approach.

**Models Implemented**
- ARIMA  
- SARIMA  
- LSTM  
- Linear Regression with lag features  

**Outcome:**  
Despite being the simplest model, **Linear Regression delivered the highest accuracy**, outperforming ARIMA, SARIMA, and even LSTM.

---

##  Dataset
Source: UK House Price Index (HPI)  
- Monthly data from 1995 to 2024  
- Nationwide average house prices  
- Cleaned, imputed, log-transformed (where required)  
- Split using time-aware chronological order  

---

##  Models & Key Results

### **1️⃣ Linear Regression (Best Performer)**
- Uses engineered lag features (lag-1 to lag-12)
- Most stable and accurate model  
 

---

### **2️⃣ LSTM**
- Learns long-term and non-linear patterns  
- Smooth convergence and no overfitting  
 

---

### **3️⃣ ARIMA**
- Captures linear & short-term dependencies  
- Tuned via ACF/PACF  
 

---

### **4️⃣ SARIMA**
- Adds seasonality on top of ARIMA  
- Better seasonal pattern capture  
- Moderate accuracy  

---

**Winner: Linear Regression**  
Feature engineering > Complex models.

---

##  Forecasting
Forecast horizons explored:
- **12 months**
- **24 months**


Forecasts visualized using Plotly (interactive graphs).

---

