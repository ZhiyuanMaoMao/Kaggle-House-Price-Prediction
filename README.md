# House Price Prediction (Kaggle)

## Overview
Predicted house sale prices using the Kaggle House Prices dataset. 
Focus on feature engineering and model interpretability.

## Key Steps
- Exploratory Data Analysis (correlation heatmap, boxplots)
- Feature Engineering (created TotalSF, HouseAge, TotalBath, etc.)
- Modelling (Random Forest & Gradient Boosting)
- Model Evaluation (feature importance, actual vs predicted)

## Results
- Random Forest CV RMSE: 0.1415
- Gradient Boosting CV RMSE: 0.1265

## Key Finding
OverallQual and engineered feature TotalSF were the top 2 predictors, 
validating the feature engineering decisions driven by correlation analysis.

## Tools
Python | Pandas | Scikit-learn | Matplotlib | Seaborn
