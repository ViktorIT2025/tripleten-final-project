# TripleTen Final Project – Customer Churn Prediction

## Overview
End-to-end data science capstone project focused on predicting customer churn for a telecommunications provider using multiple data sources.

## Data
The project uses four datasets:
- `contract.csv` – contract and tenure information
- `personal.csv` – customer demographics
- `internet.csv` – internet service usage
- `phone.csv` – phone service usage

## Approach
- Data cleaning and preprocessing using scikit-learn pipelines
- Feature engineering (including customer tenure)
- Handling class imbalance with class-weighted models
- Model comparison: Logistic Regression, Random Forest, Gradient Boosting
- Threshold optimization to maximize F1 score

## Results
- Best model: Logistic Regression (class-weighted)
- Validation ROC-AUC: **0.84**
- Test ROC-AUC: **0.85**
- Optimized F1 score: **0.63** at threshold **0.52**
- Recall: **~73%** of churners identified

## Files
- `final_project_tripleten.ipynb` – full analysis and modeling
- CSV files – raw datasets used in the analysis

## How to run

1. Clone the repository:
   ```bash
   git clone https://github.com/ViktorIT2025/tripleten-final-project.git
   cd tripleten-final-project