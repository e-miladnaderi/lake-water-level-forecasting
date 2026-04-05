# Lake Water Level Forecasting

> Time series forecasting of lake water levels using LSTM deep learning models.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Time Series](https://img.shields.io/badge/Time%20Series-Forecasting-blue?style=flat)

---

## Overview

This project develops a deep learning model to forecast lake water levels using historical time series data. Long Short-Term Memory (LSTM) networks are used to capture temporal dependencies and seasonal patterns in water level measurements, providing accurate multi-step ahead predictions.

---

## Features

- Time series data preprocessing and feature engineering
- LSTM-based deep learning model for sequential forecasting
- Sliding window approach for multi-step prediction
- Hyperparameter tuning for optimal model performance
- Visualization of actual vs predicted water levels
- Model evaluation: MAE, RMSE, R² score

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| PyTorch | LSTM model implementation |
| Pandas | Time series data handling |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Results visualization |
| Scikit-learn | Preprocessing & evaluation metrics |

---

## Model Architecture

```
Input (Historical Water Levels)
    ↓
Data Normalization
    ↓
Sliding Window Sequences
    ↓
LSTM Layer(s)
    ↓
Fully Connected Layer
    ↓
Forecasted Water Level
```

---

## Results

- Model successfully captured seasonal and trend patterns in water level data
- Low RMSE and MAE on test set
- Visualizations confirm strong alignment between predicted and actual values

---

## Project Structure

```
lake-water-level-forecasting/
├── data/               # Time series dataset
├── notebooks/          # Jupyter notebooks
├── src/                # Model and training scripts
├── results/            # Plots and metrics
├── requirements.txt
└── README.md
```

---

## Author

**Milad Naderi Beni** - MSc Data Science, University of Naples Federico II
