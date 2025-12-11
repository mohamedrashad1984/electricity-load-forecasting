# electricity-load-forecasting
Short-term electricity load forecasting using Random Forest, LSTM, and hybrid models.
# Electricity Load Forecasting

## Project Overview
This project forecasts electricity consumption using machine learning and deep learning models.  
We explore **Random Forest**, **LSTM neural networks**, and a **hybrid approach** combining both.

## Dataset
- **Source:** [Household Power Consumption Dataset](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)  
- **Features:** Global_active_power, Global_reactive_power, Voltage, etc.
- **Period:** 2006–2010  
- **Format:** CSV / TXT

## Project Steps
1. **Exploratory Data Analysis (EDA)**
   - Checked null values and trends.
   - Visualized time-series patterns.
2. **Data Cleaning**
   - Handled missing values using forward-fill (`ffill`).
   - Aggregated data hourly.
3. **Feature Engineering**
   - Created sequences for LSTM.
   - Selected relevant features for Random Forest.
4. **Modeling**
   - Random Forest regression
   - LSTM neural network
   - Hybrid model (RF + LSTM)
5. **Evaluation**
   - RMSE and MAE metrics
   - Comparison of model performance
6. **Forecasting**
   - Predicted next 24 hours electricity consumption
   - Visualized predictions

## Key Results
- **Random Forest:** RMSE = 0.484, MAE = 0.338
- **LSTM:** RMSE = 0.564, MAE = 0.450
- **Hybrid:** RMSE = 0.594, MAE = 0.441

## Insights
- LSTM captures temporal patterns better than Random Forest.
- Random Forest provides a simple, fast baseline.
- Hybrid model balances both approaches.

