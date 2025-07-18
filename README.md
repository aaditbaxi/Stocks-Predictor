# 📈 Stock Price Predictor

A time-series forecasting project that uses a **Deep LSTM** network to predict future closing prices of a selected stock (TSLA) based on historical data from 2014-10-25 to 2024-11-25. Built using **NumPy**, **Pandas**, **Matplotlib**, **yfinance**, and **TensorFlow/Keras**.

## 🔍 Features

- Fetches historical daily price data via `yfinance`  
- Plots 100‑day and 200‑day moving averages for trend visualization  
- Scales and sequences data for LSTM input (windowed lookback)  
- 4‑layer LSTM architecture with Dropout regularization  
- 80/20 train‑test split for robust evaluation  

## 📚 Libraries Used

- **NumPy**  
- **Pandas**  
- **Matplotlib**  
- **yfinance**  
- **TensorFlow** (Keras)  

## 📈 Model Performance

- **Loss Function**: Mean Squared Error (MSE)  
- Trained until convergence, producing smooth predicted vs. actual price curves  
- Visual evaluation shows strong alignment between predicted and real closing prices  
