# Banking Analytics Project - Customer Subscription Prediction

## Overview
This project uses a real banking dataset to predict customer subscription behavior for term deposits. It demonstrates data cleaning, EDA, feature analysis, and machine learning modeling using Python.  

We compare two Random Forest approaches:  
1. **RF Balanced** – balances classes in model training  
2. **RF SMOTE** – oversamples minority class to handle imbalance  

## Dataset
- Source: `bank-full.csv`  
- Contains customer demographics, account info, and campaign responses.

## Key Steps
1. Data Loading & Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Training: Random Forest (Balanced & SMOTE)  
5. Evaluation: Confusion Matrix, Classification Report  
6. Metric Comparison Visualizations  

## Key Findings
- RF Balanced: High precision but low recall for subscribers  
- RF SMOTE: Higher recall for subscribers, slightly lower precision  
- SMOTE helps handle class imbalance and improves detection of minority class

## Visualizations
- Screenshot of metric comparison bar chart: `Metrics_Comparison.png`  
- EDA visuals included in notebook  

## How to Run
1. Open `Banking_Analytics_RF.ipynb` in Jupyter Notebook  
2. Ensure `bank-full.csv` is in the same folder  
3. Run all cells to reproduce the analysis  

## Author
Neliswa Sanzo Zwelandile Mkhwanazi
