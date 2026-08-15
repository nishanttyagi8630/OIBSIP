# Cleaning Data — Titanic Dataset

## Objective
Take a deliberately messy dataset (Titanic) and systematically clean it 
into an analysis-ready dataset, documenting every decision.

## Tech Stack
Python, pandas, numpy, matplotlib, Google Colab

## Dataset
Titanic Dataset (891 rows, 10 columns) — sourced from Kaggle.

## Key Steps
- Data quality report (nulls, duplicates, dtypes)
- Missing value handling: Age column filled with median
- Data type correction (categorical columns: Survived, Pclass, Sex)
- Outlier detection using IQR method (Fare column)
- Outlier handling: capped extreme Fare values at upper bound
- Before vs after summary comparison table
- Saved cleaned dataset to new CSV file

## Key Decisions
1. Used median (not mean) to fill missing Age values — more robust to outliers
2. Capped (not removed) Fare outliers — preserved genuine high-value data
   while controlling extreme skew

## Author
Nishant Tyagi — Data Analytics Intern, Oasis Infobyte
