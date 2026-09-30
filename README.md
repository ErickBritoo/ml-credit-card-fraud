# Credit Card Fraud Detection

This repository contains a machine learning project focused on detecting fraudulent credit card transactions, with a special emphasis on handling highly imbalanced data.

## Project Overview

The objective of this project is to build and evaluate machine learning models capable of identifying frauds. Since fraudulent transactions represent a tiny fraction of the data, this project highlights the danger of relying on accuracy alone. 

Instead of traditional metrics, the analysis focuses on Precision, Recall, F1-Score, and optimizing decision thresholds using the Precision-Recall (PR) Curve to find the best trade-off between catching frauds and avoiding false alarms.

The following models were implemented and compared:

- Dummy Classifier (Baseline)
- Support Vector Machine (SVM)
- Random Forest
- XGBoost

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Project Structure

```text
.
├── data/
│   └── credit_card_fraud_2026.csv
├── .gitignore
├── credit_card_fraud_detection.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/ErickBritoo/ml-credit-card-fraud.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

## Dataset

Dataset used in this project:

- Credit Card Fraud Dataset (2026)
- Source: https://www.kaggle.com/datasets/uditjain13/credit-card-fraud-detection-2026

All credits for the dataset belong to the original author.

## Author

Erick Alves

GitHub: https://github.com/ErickBritoo

LinkedIn: www.linkedin.com/in/erick-alvess
