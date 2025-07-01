# 📈 Real-Time Stock Trend Forecasting

This project forecasts short-term stock prices using a Bidirectional GRU model that combines historical stock data with real-time news sentiment.

## 🔍 Features
- 5 years of Apple Inc. (`AAPL`) stock data from Yahoo Finance
- Real-time sentiment scoring via NewsAPI
- Deep learning model using Bidirectional GRU
- Evaluation with RMSE, MAE, and prediction plotting
- 5-day future price forecast using a rolling window

## 🧠 Why GRU?
GRU/LSTM models are effective for modeling noisy, short-term sequences like stock prices. They help learn temporal dependencies that static models cannot.

## 📦 Requirements
See [`requirements.txt`](./requirements.txt) for dependencies.

## 🚀 How to Use
1. Clone this repo and open `Solution.ipynb` in Jupyter or Google Colab.
2. Replace `YOUR_NEWSAPI_KEY` in the notebook with your [NewsAPI](https://newsapi.org/) key.
3. Run the notebook step by step — it will:
   - Download 5-year stock data
   - Fetch today’s sentiment
   - Train a GRU model
   - Predict & plot the next 5-day prices

## 📜 License
MIT – feel free to use and modify.

---
> ✨ Sidequest project to demonstrate forecasting + NLP sentiment fusion in real-time financial prediction.
