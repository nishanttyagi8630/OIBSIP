# Predicting House Prices with Linear Regression

## Objective
Build and evaluate a linear regression model that predicts house prices 
based on features such as area, location, number of rooms, and age.

## Tech Stack
Python, pandas, scikit-learn, matplotlib, seaborn, Google Colab

## Dataset
House Price Prediction Dataset (2000 rows, 10 columns) — sourced from Kaggle.

## Key Steps
- EDA (data types, missing values, price distribution)
- Correlation heatmap of numeric features
- One-Hot Encoding of categorical features (Location, Condition, Garage)
- Train/test split (80/20)
- Linear Regression model training
- Evaluation using MSE, RMSE, and R² score
- Actual vs Predicted scatter plot and residual analysis
- Coefficient analysis

## Key Findings
The model achieved an R² score of approximately -0.007, indicating no 
meaningful relationship between the features and Price in this dataset. 
Correlation analysis confirmed weak/near-zero correlations across all 
numeric features. This suggests the dataset is synthetically generated 
without embedded real-world housing market relationships.

## Key Learning
Not every dataset yields a predictive model — identifying weak 
correlations through EDA before modeling is a critical step, and a 
low R² score is itself a valid and important finding.

## Author
Nishant Tyagi — Data Analytics Intern, Oasis Infobyte
