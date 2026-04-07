# 📘 Stock Price Prediction using RNN, LSTM, and CNN

## 🧠 Overview
This project predicts the **next day’s stock closing price** using three deep learning models — **RNN**, **LSTM**, and **CNN**.  
It uses historical stock data from **Yahoo Finance** and builds time-series models that learn market patterns from past data.

---

## 🚀 Features
- Automatically downloads stock data using `yfinance`
- Preprocesses and scales data for neural networks
- Trains three models:
  - SimpleRNN  
  - LSTM  
  - CNN (1D Convolutional)
- Predicts next-day stock closing price
- Visualizes predictions vs actual data
- Saves trained models for future use

---

## 🧩 Technologies Used
| Category | Libraries |
|-----------|------------|
| Data | `yfinance`, `pandas`, `numpy` |
| Models | `tensorflow`, `keras`, `scikit-learn` |
| Visualization | `matplotlib` |
| Environment | `Google Colab` or `Jupyter Notebook` |

---

## 📦 Installation

Run these commands in **Google Colab** or your local Python environment:

```bash
!pip install yfinance tensorflow numpy pandas matplotlib scikit-learn
