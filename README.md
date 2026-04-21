**# ml-stock-classifier**

# Stock Price Direction Classifier

Predicts whether AAPL will close up or down the next trading day using machine learning.

## Tech Stack
Python, scikit-learn, pandas, yfinance, Google Colab

## Features Used
- 5-day and 20-day moving averages
- Price momentum
- Volatility (10-day rolling std dev)
- Volume change

## Model
Random Forest Classifier (100 estimators)

## Results
- Out-of-sample accuracy: XX%
- Test period: 2023 (1 year held out)
- Training data: 2019–2022 AAPL daily OHLCV

## How to Run
Open the notebook directly in Google Colab:
(https://colab.research.google.com/drive/1zF-WmMwIvHFIp8xgbgo-8cMGZhGoAecO?usp=sharing)
