# Unveiling the Android App Market — OIBSIP Data Analytics (Level 2, Task 4)

## 📌 Objective
Perform a comprehensive data analysis of the Google Play Store ecosystem — cleaning
messy real-world data, exploring app categories, analysing ratings and pricing trends,
and conducting sentiment analysis on user reviews.

## 🛠 Tech Stack
- Python
- pandas, numpy
- matplotlib, seaborn
- VADER Sentiment (vaderSentiment)
- Jupyter Notebook (Google Colab)

## 📂 Files in this folder
- `Play_Store_Analysis.ipynb` — full notebook covering data cleaning, category/ratings/
  pricing analysis, and sentiment analysis on user reviews.
- `README.md` — this file.

## 📥 Dataset Setup
1. Download from Kaggle — search **"Google Play Store Apps"** (dataset by `lava18`).
2. Get both files: `googleplaystore.csv` and `googleplaystore_user_reviews.csv`.
3. Upload both to your Colab session.
4. Open `Play_Store_Analysis.ipynb` and run all cells top to bottom.

## 📊 What the Notebook Covers
- Loading both the apps dataset and the user reviews dataset
- Data cleaning: fixing incorrect data types (e.g., "Installs" stored as "10,000+"
  strings), handling nulls, removing duplicates
- Category analysis: which categories are most saturated
- Ratings analysis: distribution of ratings, average rating by category
- Size vs installs analysis: correlation check
- Pricing analysis: free vs paid split, price distribution, estimated revenue by category
- Sentiment analysis on user reviews using VADER (positive/negative/neutral)
- Sentiment by category: which categories have the most satisfied/dissatisfied users
- Conclusion: 3 data-driven insights for a developer planning to launch a new app

## 🔑 Key Findings
- **FAMILY** is the most saturated category with 1,832 apps, indicating high competition.
- **92.17%** of apps on the Play Store are free; only 7.83% are paid.
- The **FAMILY** category generates the highest estimated revenue among paid apps,
  followed by LIFESTYLE and GAME.
- The **GAME** category shows the most positive user sentiment, while **MEDICAL** and
  **FINANCE** show the most negative sentiment — suggesting room for improvement
  in those spaces.

## 🔗 Submission Checklist (per OIBSIP guidelines)
- [x] Pushed to `OIBSIP` GitHub repo as:
      `OIBSIP/DataAnalytics-L2-PlayStoreAnalysis/`
- [ ] Post on LinkedIn tagging Oasis Infobyte with `#oasisinfobyte`
- [ ] Complete peer evaluation on at least 2 other interns' posts
- [ ] Submit via the Task Submission Form with GitHub repo link

## Author
Nishant Tyagi — Data Analytics Intern, Oasis Infobyte
