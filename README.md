# XGBoost Regression House Price Prediction

## Overview
Predicting house sale prices using the Ames Housing dataset from Kaggle.

## Score
Public Leaderboard: **0.12810** (RMSLE)

## Dataset
[House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

## Approach
- Exploratory Data Analysis (EDA)
- Missing value imputation
- Feature Engineering (TotalSF, TotalBath, HouseAge, etc.)
- Label Encoding for categorical variables
- XGBoost Regressor with 5-Fold Cross Validation
- Log transformation on target variable

## Results
| Model | CV RMSE | Public Score |
|---|---|---|
| XGBoost | 0.1240 | 0.1281 |

## Kaggle Notebook
[View on Kaggle](https://www.kaggle.com/code/hilalzerk/xgboost-regression-house-price-prediction)

## Libraries
- pandas, numpy, matplotlib, seaborn
- scikit-learn, xgboost
