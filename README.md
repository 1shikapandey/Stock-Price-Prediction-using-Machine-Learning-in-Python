# Stock Price Prediction using Machine Learning in Python

## Overview
This project applies **machine learning regression models** to predict future stock prices using historical market data.  
It demonstrates the use of time-series analysis, feature engineering, and model evaluation to forecast stock trends for informed decision-making.

---

## Dataset
- **Source:** CSV historical data
- **Features:** Date, Open, High, Low, Close, Volume
- **Target:** Closing Price prediction

---

## Methodology
1. **Data Collection**
   - Load historical stock data from CSV or Yahoo Finance API
2. **Data Preprocessing**
   - Handle missing values
   - Feature scaling
   - Train-test split
3. **Feature Engineering**
   - Moving averages
   - Technical indicators (e.g., RSI, MACD)
4. **Model Building**
   - Linear Regression, Random Forest, XGBoost, or LSTM
5. **Model Evaluation**
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score
6. **Visualization**
   - Historical vs. predicted prices plot
   - Residual analysis

---

## Results
- **RMSE:** ~2.5 (varies by model and dataset)
- **Observation:** LSTM and ensemble models perform better for capturing trends compared to basic regression.

---

## Requirements
```bash
pip install numpy pandas matplotlib seaborn scikit-learn yfinance

▶️ How to Run
git clone https://github.com/1shikapandey/Stock-Price-Prediction-using-Machine-Learning-in-Python.git
cd Stock-Price-Prediction-using-Machine-Learning-in-Python
python Stock-Price-Prediction-using-Machine-Learning-in-Python.py


