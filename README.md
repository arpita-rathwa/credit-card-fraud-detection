# Credit Card Fraud Detection 🔍

## Overview
A machine learning project to detect fraudulent credit card transactions 
using Random Forest classifier with SMOTE for handling imbalanced data.

## Dataset
- Source: Kaggle — Credit Card Fraud Detection (MLG-ULB)
- 284,807 transactions over 2 days
- Only 492 fraud cases (0.17%) — highly imbalanced

## Approach
1. Exploratory Data Analysis (EDA)
2. Data preprocessing and normalization
3. Handling imbalanced data using SMOTE
4. Built and compared two models:
   - Logistic Regression
   - Random Forest

## Results

| Model | Precision | Recall | F1 Score | False Positives |
|-------|-----------|--------|----------|-----------------|
| Logistic Regression | 6% | 92% | 0.11 | 1,509 |
| Random Forest | 87% | 83% | 0.85 | 12 |

**Random Forest significantly outperformed Logistic Regression.**

## Key Findings
- V10, V14 and V4 are the strongest fraud indicators
- Transaction amount alone is NOT a reliable fraud signal
- SMOTE effectively balanced the dataset from 394 to 227,451 fraud cases

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

## Author
**Arpita Rathwa** — EEE Undergrad @ NIT Calicut  
[LinkedIn](https://linkedin.com/in/arpita-rathwa-677b6837a)
