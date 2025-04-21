# 📈 Sainsbury’s Stock Price Prediction

---

## 🧠 Project Overview

This project aims to forecast the stock prices of **Sainsbury's**, a leading UK retail company, using **Recurrent Neural Networks (RNN)** and **Long Short-Term Memory (LSTM)** models. By analyzing historical stock data, we designed a deep learning approach to predict future trends and support investment decisions.

---

## 🏢 About Sainsbury's

Sainsbury’s is one of the UK’s largest supermarket chains, with over **1400 locations**. It offers groceries, merchandise, and clothing under brands like **Sainsbury's, Argos, and Habitat**.

---

## 📊 Data Collection

- **Source**: Yahoo Finance (`yfinance`)
- **Duration**: ~12 years of daily stock prices
- **Processing**: Data split into 80% training and 20% testing
- **Tools Used**: `pandas`, `keras`, `numpy`, `matplotlib`

---

## 🛠️ Models Used

### 🔁 RNN Model
- Architecture: 3 layers of `SimpleRNN` with units 40, 90, and 70
- Output: Single-unit `Dense` layer
- Optimizer: `adam`

### ⏳ LSTM Model
- Layers: 3 LSTM layers (units: 10, 50, 120), 1 Dropout (0.02), and 1 Dense layer
- Known for capturing long-term dependencies in sequential data

---

## 🔮 Forecasting Approach

- Used a `predict_future_days()` function to forecast 45 future days using the trained LSTM model
- Plotted historical vs predicted prices
- Saved visualization as **`Future_prediction.png`**

---

## 📈 Results

- Forecasted future trends in Sainsbury’s stock prices
- Clear visualization with well-labeled axes and legends
- Ready for comparison with actual stock prices to assess model performance

---

## 🧾 Requirements

- Python 3.x
- TensorFlow / Keras
- yfinance
- matplotlib
- pandas
- scikit-learn
