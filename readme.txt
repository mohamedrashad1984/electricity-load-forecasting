# Electricity Load Forecasting

## Project Overview
Forecast electricity consumption using machine learning and deep learning models (Random Forest, LSTM, Hybrid).

## Dataset
- **Source:** Household Power Consumption Dataset  
- **Features:** Global_active_power, Voltage, etc.  
- **Period:** 2006–2010  

## Project Steps
1. Exploratory Data Analysis (EDA)  
2. Data Cleaning and Handling Missing Values (`ffill`)  
3. Feature Engineering (hourly aggregation, sequences for LSTM)  
4. Modeling
   - Random Forest Regression
   - LSTM Neural Network
   - Hybrid Model
5. Evaluation using RMSE and MAE  
6. Forecasting next 24 hours  

## Key Results
- Random Forest: RMSE = 0.484, MAE = 0.338  
- LSTM: RMSE = 0.564, MAE = 0.450  
- Hybrid: RMSE = 0.594, MAE = 0.441  

## Insights
- LSTM captures temporal patterns better than Random Forest.  
- Random Forest is a fast baseline.  
- Hybrid model combines both approaches.

## Next Steps
- Include external features (temperature, holidays).  
- Hyperparameter tuning.  
- Deploy dashboard using Power BI or Streamlit.
