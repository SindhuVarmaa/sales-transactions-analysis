📊 Sales Transactions Analysis

Retail Sales Transactions – Fraud Detection & Performance Insights using Python and Power BI

📁 Project Overview

This project analyzes retail sales transactions to identify:
✔️ Suspicious / fraudulent activities
✔️ Sales performance patterns
✔️ Product-level revenue insights
✔️ Salesperson performance

The workflow combines Python (Pandas, Jupyter Notebook) for data cleaning + feature engineering and Power BI for dashboard visualizations.

🔧 Tools & Technologies

Python (Pandas, NumPy, Matplotlib)

Jupyter Notebook

Power BI dashboards

Git & GitHub

CSV/Excel Retail Transaction Dataset

SalesTransaction/
│
├── clean_train_for_powerbi.csv        # Cleaned dataset for Power BI
├── product_summary.csv                # Product performance summary
├── salesperson_summary.csv            # Salesperson performance summary
├── Sales Transaction Project.ipynb     # Python data cleaning & analysis notebook
│
├── Test.xlsx                          # Original test dataset
├── Train.xlsx                         # Original training dataset
│
└── README.md

🧪 Data Processing in Python

The Jupyter Notebook performs:

Data cleaning (fixing invalid values, missing fields, duplicates)

Price standardization & quantity validation

Suspicious pattern detection (Yes, No, Indeterminate)

Product-level aggregation

Salesperson performance scoring

Export of final datasets for Power BI dashboards
