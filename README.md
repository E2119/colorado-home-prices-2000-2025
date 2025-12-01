Colorado Home Prices (2000–2025)

This project analyzes Colorado home values using Zillow’s ZHVI dataset.
It includes Exploratory Data Analysis (Notebook A) and a simple prediction model (Notebook B).

   Files

Notebook A: colorado-average-house-prices-2000-2025.ipynb

Data cleaning

Yearly averages

Visualizations

Comparison with Washington and Texas

Notebook B: modeling-colorado-home-prices-2000-2025.ipynb

Feature engineering

Linear Regression model

Train/test split

Evaluation and predictions

  Dataset

Source: Zillow ZHVI (Kaggle)

Monthly home values

Years used: 2000–2025

States examined: Colorado (+ WA, TX for comparison)

 Key Insights (EDA)

Colorado home prices increased strongly after 2012

Peak growth in 2020–2022

Colorado now behaves more like Washington (fast-growing, high-cost)

   Model Summary

Model: Linear Regression

Features: Year, Year_Index

Train: 2000–2019

Test: 2020–2025

Metrics used: MAE, RMSE, R²

   Results

Model struggled with rapid price increases after 2020

Good for long-term trend, not sudden jumps

   Future Work

Add more features (population, income, interest rates)

Test non-linear models

Predict individual Colorado cities

   Author

Ermiyas Hailu
