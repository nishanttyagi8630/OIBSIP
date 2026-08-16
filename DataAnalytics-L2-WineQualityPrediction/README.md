# Wine Quality Prediction — OIBSIP Data Analytics (Level 2, Task 2)

## 📌 Objective
Train and compare multiple classification models to predict the quality of wine based on
its physicochemical properties (acidity, density, alcohol content, etc.), using the
UCI Wine Quality dataset.

## 🛠 Tech Stack
- Python
- pandas, numpy
- scikit-learn (RandomForestClassifier, SGDClassifier, SVC)
- seaborn, matplotlib
- Jupyter Notebook (Google Colab)

## 📂 Files in this folder
- `Wine_Quality_Prediction.ipynb` — full notebook with EDA, class imbalance discussion,
  feature engineering, model training, evaluation, and conclusion.
- `winequality-red.csv` — dataset (UCI Wine Quality - Red Wine).
- `README.md` — this file.

## 📊 What the Notebook Covers
- Data loading & structure inspection (class distribution of quality scores)
- EDA: distribution plots for all chemical features, correlation heatmap
- Discussion of class imbalance and its effect on modelling
- Feature engineering: binning quality into 3-class (low/medium/high) categories
- Stratified train/test split to preserve class ratios
- Training 3 classifiers: Random Forest, SGD, and SVC
- Evaluation: accuracy, classification report, confusion matrix for each model
- Feature importance chart (Random Forest)
- Side-by-side model comparison table
- Conclusion on which model is most deployment-ready and why

## 🔑 Key Findings
- Alcohol content shows the strongest positive correlation with wine quality (+0.48).
- Volatile acidity shows the strongest negative correlation with quality (-0.39).
- The dataset is heavily imbalanced: most wines fall in the "medium" quality class,
  with very few "low" quality samples — this was addressed using stratified splitting
  and evaluation via precision/recall/F1 rather than accuracy alone.

## 🔗 Submission Checklist (per OIBSIP guidelines)
- [x] Pushed to `OIBSIP` GitHub repo as:
      `OIBSIP/DataAnalytics-L2-WineQualityPrediction/`
- [ ] Post on LinkedIn tagging Oasis Infobyte with `#oasisinfobyte`
- [ ] Complete peer evaluation on at least 2 other interns' posts
- [ ] Submit via the Task Submission Form with GitHub repo link

## Author
- Nishant Tyagi — Data Analytics Intern, Oasis Infobyte
