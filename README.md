# 📈 Stock Price Prediction using LSTM  

Predicting stock prices with the power of deep learning — this project uses a **Long Short-Term Memory (LSTM)** neural network to forecast future stock closing prices based on historical market data.  

---

## 🧠 Overview  

Stock price prediction is one of the most challenging tasks in finance due to its high volatility and dependency on numerous factors.  
This project applies an **LSTM model**, a type of recurrent neural network (RNN), to capture long-term dependencies and non-linear relationships in stock price data.

The model is trained on **Apple Inc. (AAPL)** stock data retrieved from **Yahoo Finance** and demonstrates high predictive accuracy with an **R² score of 0.9968**.

---

## 🚀 Features  

✅ Fetches real-time historical stock data using **yfinance**  
✅ Preprocesses data with **MinMaxScaler** for normalization  
✅ Builds and trains an **LSTM deep learning model** using TensorFlow/Keras  
✅ Evaluates model using MSE, RMSE, MAE, and R² metrics  
✅ Visualizes **Actual vs Predicted stock price trends**  

---

## Model Performance (Test set)

| Metric | Value |
|:------:|:-----:|
| Mean Squared Error (MSE) | 9.9035 |
| Root Mean Squared Error (RMSE) | 3.1470 |
| Mean Absolute Error (MAE) | 1.7879 |
| R² Score | 0.9968 |
