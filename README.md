# 📈 Stock Market Price Prediction using SVR

This project demonstrates a **simple stock price prediction model** using **Support Vector Regression (SVR)** with a **synthetic dataset**. It shows how stock prices might be modeled based on sequential daily data and how future values can be predicted.

---

## 🔍 Overview

- 🔢 Generates synthetic stock prices using cumulative random noise.
- 🧪 Trains an SVR model to fit and predict stock prices.
- 📉 Evaluates performance using Mean Squared Error (MSE).
- 📊 Visualizes training data, test data, and future predictions.
- 📦 Built using popular Python libraries such as `scikit-learn`, `matplotlib`, and `pandas`.

---

## 🧠 Machine Learning Model

- **Model**: `SVR (Support Vector Regression)`
- **Kernel**: `Linear`
- **Scaler**: `MinMaxScaler`
- **Train/Test Split**: 80% / 20%

---

## 🛠️ Requirements

Install the necessary dependencies with:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## 🚀 How to Run
Clone the repo or copy the script.

Run the Python script:

```
python stock_market_prediction.py
```
The script will:

Generate a synthetic stock price dataset.

Fit an SVR model to training data.

Predict stock prices for the next 10 days.

Show a matplotlib plot of all data.

---

## 
