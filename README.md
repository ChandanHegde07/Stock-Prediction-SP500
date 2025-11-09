# S&P 500 Stock Price Prediction

This project focuses on building a machine learning model to predict **daily stock price movement direction** (up or down) of companies listed in the **S&P 500 index**. Using historical stock data and calculated technical indicators, we aim to classify whether the stock will rise or fall on the next trading day. The final model achieves an accuracy of **57%**, which, despite sounding modest, can be meaningful in the context of financial markets where even a slight edge can be profitable with the right strategy.

The project covers the **end-to-end pipeline**:
- Data collection from Yahoo Finance
- Feature engineering with technical indicators
- Model training and evaluation
- Predictive performance analysis

The ultimate goal is to develop a **proof-of-concept** for machine learning-based stock direction forecasting using publicly available data and tools.

---

## Project Goal

The main objective is to create a predictive model that can help forecast the **next-day movement** (up or down) of a stock price based on its historical trends and derived features.

Key goals:
- Collect and preprocess financial time series data
- Generate meaningful features (like moving averages, returns, RSI, etc.)
- Build a classification model to predict the direction of price change
- Evaluate the model using metrics such as accuracy and confusion matrix

Although this model is not optimized for live trading, it offers a foundational approach for understanding how machine learning can be applied to stock market prediction.

---

## Technologies Used

This project uses the following technologies and libraries:

- **Python 3.12+**  
  The primary programming language for data analysis, modeling, and scripting.

- **yfinance**  
  Used to download historical stock data for companies in the S&P 500. It simplifies accessing open, high, low, close, volume (OHLCV) data directly from Yahoo Finance.

- **pandas**  
  A powerful data manipulation and analysis library used to clean and process stock data into a usable format.

- **scikit-learn**  
  A machine learning library used to build and evaluate classification models. In this project, models like Logistic Regression, Random Forest, or Support Vector Machines (SVMs) may be used.

- Optional tools (not required, but can be added):
  - `matplotlib`, `seaborn` for visualizations
  - `numpy` for numerical calculations
  - `ta` for technical analysis indicators

---
