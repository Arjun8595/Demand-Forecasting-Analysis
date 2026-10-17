# Demand Forecasting Analysis

Forecasting daily product demand using Python and machine learning.

## Dataset
Historical Product Demand (Kaggle). `data.csv` is not included because of its size. Download it from Kaggle and place it in the project folder.

## What I did
- Cleaned the data (date parsing, negative values written in brackets, missing dates)
- Aggregated transactions into daily total demand
- Built features: calendar features, lag features, rolling statistics
- Compared 4 models on a time-based train/test split

## Models
Linear Regression, Decision Tree, Random Forest, XGBoost

## Result
Random Forest performed best (R2 around 0.45).

## Tech
Python, pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Seaborn

## Run it
pip install -r requirements.txt
