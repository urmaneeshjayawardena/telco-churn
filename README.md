# Telco Customer Churn – KNN, Logistic Regression, Random Forest
CM2604 Machine Learning – Coursework Part 01

## Setup
1. `pip install -r requirements.txt`
2. Download the "Telco Customer Churn" CSV from Kaggle and save it as
   `data/WA_Fn-UseC_-Telco-Customer-Churn.csv`
3. `jupyter notebook churn_classification.ipynb` and run all cells.

## Outputs
- `figures/` – EDA and evaluation plots
- `results/` – tuning and test-set metric tables (CSV)

## Experimental settings
- A: baseline on the original imbalanced data
- B: SMOTE applied inside each CV fold (training folds only)
