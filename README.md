# Insurance Claim Prediction

## Project Overview
This project builds a machine learning model to predict whether a building will have at least one insurance claim during its insured period.

## Target Variable
- `Claim = 1`: At least one claim
- `Claim = 0`: No claim

## Steps Performed
1. Data Cleaning & Missing Value Handling
2. Exploratory Data Analysis (EDA)
3. Feature Engineering & Encoding
4. Model Training (Logistic Regression, Random Forest, Gradient Boosting)
5. Recall Optimization using Threshold Tuning
6. Model Evaluation using ROC-AUC and Classification Report

## Best Model
- Random Forest Classifier
- Optimized for recall
- ROC-AUC ≈ 0.68
- Recall (Claim = 1) ≈ 0.55

## Files
- `notebooks/insurance_claim_model.ipynb`
- `models/insurance_claim_model.pkl`

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Author
Emmanuel U Bassey