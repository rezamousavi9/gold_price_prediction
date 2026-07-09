# Gold Price Prediction

A machine learning project to predict Gold Price (GLD) using historical financial data with Random Forest Regressor.

![Gold Price Prediction](https://via.placeholder.com/800x400?text=Gold+Price+Prediction) 

## 📋 Project Description

This project analyzes the relationship between gold prices and other financial indicators (S&P 500, Crude Oil, Silver, EUR/USD) and builds a high-accuracy predictive model.

R² Score achieved: 0.9896 (Very high accuracy!)

## ✨ Features

- Exploratory Data Analysis (EDA)
- Correlation analysis & heatmap
- Data visualization (distribution & actual vs predicted)
- Machine Learning model (Random Forest Regressor)
- Train/Test split & model evaluation

## 📊 Dataset

- Source: gld_price_data.csv
- Time Period: 2008 to 2018
- Columns:
  - Date
  - SPX (S&P 500)
  - GLD (Gold Price) ← Target
  - USO (Crude Oil)
  - SLV (Silver)
  - EUR/USD

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (RandomForestRegressor)
- Jupyter Notebook

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/rezamousavi9/gold-price-prediction.git
   cd gold-price-prediction
