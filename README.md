# Credit Wise Loan System

A machine learning project focused on predicting whether a loan application should be approved based on applicant information and loan characteristics.

## Overview

This repository contains a mini data science and machine learning workflow for a credit-risk/loan-approval use case. The project uses a structured dataset containing financial and demographic attributes such as income, credit score, debt-to-income ratio, employment type, loan amount, and property area.

The workflow includes:

- Data loading and inspection
- Missing value handling
- Exploratory data analysis (EDA)
- Feature encoding for categorical variables
- Model training for loan approval prediction
- Evaluation and interpretation of results

## Dataset

The project uses `DataSet.csv`, which contains applicant-level records with features related to loan eligibility and approval outcomes.

Key features include:

- Applicant income
- Co-applicant income
- Credit score
- Loan amount and term
- DTI ratio
- Savings and collateral value
- Employment status
- Marital status
- Education level
- Property area
- Loan purpose
- Gender and employer category

## Goal

The main objective is to build a predictive model that identifies whether a loan will be approved (`Yes`/`No`) based on historical applicant data.

## Repository Structure

- `Model.ipynb` - Jupyter notebook containing the complete data analysis and machine learning workflow
- `DataSet.csv` - dataset used for training and analysis
- `Problem_statement.pdf` - project statement and problem definition
- `README.md` - project documentation

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Workflow

1. Load the dataset
2. Inspect and clean missing values
3. Analyze relationships between features and loan approval
4. Encode categorical variables for model compatibility
5. Train a classification model
6. Evaluate model performance and summarize findings

## How to Run

1. Open the project in a Python environment.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `Model.ipynb` and run the cells in sequence.

## Notes

This is a beginner-friendly mini project designed to demonstrate end-to-end data science work for a loan approval prediction problem.

## License

This project is intended for educational and learning purposes.

## Author

Prithvikatkar17
