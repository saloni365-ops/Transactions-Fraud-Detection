# Transactions Fraud Detection System

A real-time fraud detection system using a hybrid machine learning approach. It combines **Random Forest** (supervised) and **Isolation Forest** (unsupervised) to detect fraudulent transactions and make automated decisions.

## Overview

The system detects fraud by:
- Learning known patterns (**Random Forest**)
- Identifying anomalies (**Isolation Forest**)
- Applying a tiered decision system

Each transaction is classified as:
- Auto-Allow
- Manual Review
- Auto-Block

## Key Features
- Real-time fraud risk scoring (0–100)
- Dual-model ensemble
- Automated decision engine
- Interactive Streamlit dashboard
- Feature importance and analytics

## Model Performance
| Metric          | Value   |
|-----------------|---------|
| Accuracy        | 85%     |
| Precision       | 83.2%   |
| Recall          | 80.2%   |
| F1 Score        | 0.818   |
| ROC-AUC         | 0.8317  |

## Test Summary:
- 99,887 transactions processed
- 80.2% fraud detection rate
- 61.6% automated decisions made

## Tech Stack
- Python, scikit-learn, Pandas, NumPy
- Streamlit, Plotly
- Random Forest, Isolation Forest

## Project Structure
default:
| File/Folder      | Description                        |
|------------------|------------------------------------|
| app.py           | Dashboard                          |
| model/           | Trained models                     |
| data/            | Dataset                            |
| notebooks/       | Training & Exploratory Data Analysis (DA)
|
## How to Run
git clone https://github.com/saloni365-ops/Transactions-Fraud-Detection 
git cd Transactions-Fraud-Detection 
pip install -r requirements.txt 
streamlit run app.py 

## Key Takeaway
tThis project demonstrates a production-style fraud detection system with machine learning, decision logic, and a user-facing dashboard.

## Future Improvements
dAPI deployment,
Real-time streaming,
Advanced models (XGBoost, deep learning),
and Explainability (SHAP/LIME)
