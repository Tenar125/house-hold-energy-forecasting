# ⚡ Household Energy Consumption Forecasting

## 📊 Project Overview
This project focuses on forecasting short-term household energy consumption using time series analysis and machine learning models. The goal is to analyze historical energy usage patterns and predict future consumption.


## 📁 Dataset
Household Power Consumption Dataset  
(Contains minute-level energy usage data collected from a household)


## 🎯 Objectives
- Parse and preprocess time series data
- 
- Perform resampling (daily/weekly trends)
- 
- Engineer time-based features (hour, weekday, weekend)
- 
- Train and compare multiple forecasting models:
- 
  - ARIMA
  - 
  - Prophet
  - 
  - XGBoost
  - 
- Evaluate models using MAE and RMSE
- 
- Visualize actual vs predicted results

## ⚙️ Workflow

### 1. Data Preprocessing
- Converted Date & Time into datetime format
- 
- Handled missing values
- 
- Resampled data to daily averages

### 2. Feature Engineering
- Hour of day
- 
- Day of week
- 
- Month
- 
- Weekend indicator

### 3. Models Used
- ARIMA (Statistical model)
- 
- Prophet (Seasonality-based model)
- 
- XGBoost (Machine Learning model)
- 
## 📊 Model Evaluation

Models are evaluated using:

- MAE (Mean Absolute Error)
- 
- RMSE (Root Mean Squared Error)


## 📈 Results Visualization

- Actual vs Predicted plots for all models
- 
- Comparison of forecasting performance


## 🏆 Key Insights
- Energy consumption shows strong time-based patterns
- 
- Prophet handles seasonality better
- 
- XGBoost performs best with engineered features
- 
## 🚀 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Prophet
- XGBoost
