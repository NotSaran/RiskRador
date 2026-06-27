# 🛡️ RiskRador

A Machine Learning application that predicts whether a loan applicant is likely to default using the Home Credit Default Risk dataset.

---

## 📌 Project Overview

RiskRador is an end-to-end Machine Learning project developed as part of my Applied Machine Learning Internship.

The project analyzes customer financial information, performs extensive Exploratory Data Analysis (EDA), cleans and engineers meaningful features, trains multiple machine learning models, evaluates their performance, and finally deploys the best-performing model through a Streamlit web application.

---

## 🎯 Problem Statement

Financial institutions lose billions due to loan defaults every year.

The objective of this project is to predict whether a customer will repay or default on a loan using historical customer information.

This enables banks to make smarter lending decisions while minimizing financial risks.

---

## 📂 Dataset

**Home Credit Default Risk Dataset**

Source:
https://www.kaggle.com/competitions/home-credit-default-risk

Main Dataset:

- application_train.csv

Rows:
307,511

Features:
122

Target Variable:

TARGET

- 0 → Loan Repaid
- 1 → Loan Default

---

# Project Workflow

```
Data Collection
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Model Building
        │
        ▼
Model Evaluation
        │
        ▼
Model Explainability (SHAP)
        │
        ▼
Streamlit Deployment
```

---

# Repository Structure

```
RiskRador/
│
├── app/
│   └── streamlit_app.py
│
├── data/
│   ├── raw/
│   │   └── application_train.csv
│   │
│   └── processed/
│       ├── application_clean.csv
│       └── application_feature_engineered.csv
│
├── docs/
│   ├── design_doc.md
│   ├── tech_stack.md
│
├── models/
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Feature_Engineering.ipynb
│   ├── 04_Model_Building.ipynb
│   ├── 05_Model_Evaluation.ipynb
│   └── 06_Model_Explainability.ipynb
│
├── reports/
│
├── src/
│
├── requirements.txt
│
└── README.md
```

---

# Technologies Used

| Category | Tools |
|-----------|------|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Explainability | SHAP |
| Deployment | Streamlit |
| Version Control | Git & GitHub |
| IDE | Visual Studio Code |

---

# Completed Tasks

- Dataset Collection
- Exploratory Data Analysis
- Missing Value Analysis
- Data Cleaning
- Feature Engineering

---

# Upcoming Tasks

- Model Building
- Hyperparameter Tuning
- Model Evaluation
- SHAP Explainability
- Streamlit Application
- Deployment

---

# How to Run

Clone the repository

```
git clone https://github.com/NotSaran/RiskRador.git
```

Move into project directory

```
cd RiskRador
```

Create virtual environment

```
python -m venv .venv
```

Activate virtual environment

Windows

```
.venv\Scripts\activate
```

Install dependencies

```
pip install -r requirements.txt
```

Run the notebooks.

---

# Results

(To be updated after model training.)

---

# Future Improvements

- Hyperparameter Optimization
- Ensemble Learning
- Feature Selection
- Fairness Analysis
- Cloud Deployment
- CI/CD Pipeline

---

# Author

**Saran R**

Applied Machine Learning Internship 2026

Lovely Professional University
