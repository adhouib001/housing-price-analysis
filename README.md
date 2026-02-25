# Housing Price Analysis – Kaggle Regression Project

## Overview
End-to-end regression project using Kaggle’s House Prices dataset. Includes data cleaning, exploratory analysis, feature engineering, and a baseline model to predict SalePrice.

## Dataset
Kaggle: House Prices – Advanced Regression Techniques
Files used:
- data/train.csv
- data/test.csv
- data/data_description.txt

## Project Structure
housing-price-analysis/
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── data_description.txt
├── housing_analysis.ipynb
└── README.md

## Workflow
1. Load dataset + quick sanity checks
2. Handle missing values (numeric + categorical)
3. Explore distributions and correlations with SalePrice
4. Encode categorical variables
5. Train a baseline regression model (Ridge / Linear Regression)
6. Evaluate with RMSE (and compare improvements)

## Tools
Python, Pandas, NumPy, Matplotlib, scikit-learn

## Status
In progress (baseline model + first insights completed)
