# Bank Loan Default Prediction

**AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026**  
**BharatCares x AICTE — Project**  
**Author: Deep Debnath**

## Project Overview

This project analyses loan application data and uses **Logistic Regression** to estimate whether a loan applicant may default. It also provides an interactive dashboard where users can explore the data, view model results and review applicant risk scores.

The project uses the `Loan_Default.csv` dataset, which contains 148,670 loan application records.

## Project Objectives

- Analyse loan applicant information.
- Identify patterns related to loan defaults.
- Clean and prepare the dataset for analysis.
- Train a machine learning model to predict loan default.
- Display analysis, model results and risk scores in an interactive dashboard.

## Dataset

- **File name:** `Loan_Default.csv`
- **Records:** 148,670
- **Columns:** 34
- **Target column:** `Status`
  - `0` = No Default
  - `1` = Default
- **Dataset source:** [Kaggle — Loan Default Dataset](https://www.kaggle.com/datasets/yasserh/loan-default-dataset)

Keep `Loan_Default.csv` in the same folder as the Python file before running the project.

## Tools and Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- Plotly
- Dash

## Project Files

```text
Bank-Loan-Default-Prediction/
│
├── BankLoanDefaultPrediction.py   # Main Python application
├── report.docx                    # Project report
├── requirements.txt               # Required Python libraries
├── README.md                      # Project information and instructions
└── Loan_Default.csv                # Dataset required to run the application
```

## Project Workflow

1. **Data loading:** Read the loan dataset into Python.
2. **Data cleaning:** Handle missing values and remove the ID column.
3. **Data analysis:** Explore default patterns using charts and summary statistics.
4. **Data preparation:** Convert categorical information into numerical values.
5. **Model training:** Train a Logistic Regression model using an 80:20 train-test split.
6. **Model evaluation:** Review accuracy, precision, recall and the confusion matrix.
7. **Risk scoring:** Estimate default probabilities and group applicants into Low, Medium and High risk categories.

## Dashboard Features

The application opens an interactive dashboard with five sections:

- **Overview:** Summary of the dataset and key information.
- **EDA Charts:** Visual analysis of loan defaults, income, region, credit score and numerical relationships.
- **Model Evaluation:** Model performance metrics and confusion matrix.
- **Risk Scoring:** Applicant risk levels and a list of applicants with the highest predicted risk.
- **Raw Data:** Searchable and sortable dataset preview.

## How to Run the Project

### 1. Install Python

Use Python 3.10 or a compatible newer version.

### 2. Keep the project files together

Make sure these files are in the same folder:

- `BankLoanDefaultPrediction.py`
- `Loan_Default.csv`
- `requirements.txt`

### 3. Install the required libraries

Open a terminal in the project folder and run:

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python BankLoanDefaultPrediction.py
```

### 5. Open the dashboard

Open this address in your browser:

```text
http://127.0.0.1:8050
```

Keep the terminal running while using the dashboard. Press `Ctrl+C` in the terminal to stop the application.

## Author

**Deep Debnath**  
AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026

## Acknowledgements

- [IBM SkillsBuild](https://skillsbuild.org/)
- [BharatCares](https://bharatcares.org/)
- [AICTE](https://www.aicte-india.org/)
- [Kaggle](https://www.kaggle.com/) — dataset source

---

*This project is developed for educational and analytical purposes. Its predictions should not be used as the sole basis for real loan approval or rejection decisions.*
