# HexSoftwares_Project_Loan_Eligibility(EDA)
# Loan Eligibility Prediction

## Project Overview

Financial institutions receive thousands of loan applications daily. Evaluating each application manually can be time-consuming and may lead to inconsistent decisions.

This project applies *Machine Learning* to predict whether a loan application will be *approved or rejected* based on financial and employment information.

Using historical loan data, we analyze the dataset, explore relationships between variables, and build a *Logistic Regression classification model* to assist financial institutions in making faster and more reliable lending decisions.

---

# Business Problem

Banks must carefully evaluate loan applications to minimize financial risk. Approving applicants who cannot repay loans leads to financial losses, while rejecting reliable applicants reduces potential profit.

To solve this problem, machine learning models can analyze past lending data and learn patterns that indicate whether an applicant is likely to receive loan approval.

This project demonstrates how data science techniques can support *automated decision-making in the financial sector.*

---

# Dataset Information

The dataset contains *24,000 loan applications* and includes the following features:

| Feature           | Description                        |
| ----------------- | ---------------------------------- |
| Income            | Applicant's annual income          |
| Credit_Score      | Credit reliability score           |
| Loan_Amount       | Requested loan amount              |
| DTI_Ratio         | Debt-to-income ratio               |
| Employment_Status | Employment status of the applicant |
| Approval          | Loan approval decision             |

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# Exploratory Data Analysis

Several visualizations were used to understand the dataset:

* Loan approval distribution
* Credit score distribution
* Correlation heatmap

These analyses help identify relationships between financial variables and loan approval outcomes.

---

# Machine Learning Model

The model used in this project is *Logistic Regression*, which is commonly applied for binary classification problems.

Steps performed:

1. Data exploration
2. Missing value verification
3. Feature engineering
4. Data preprocessing
5. Train-test split
6. Feature scaling
7. Model training
8. Model evaluation

---

# Model Performance

The model achieved approximately:

Accuracy: *87% – 92%*

This indicates that the model correctly predicts the loan approval decision for the majority of applicants.

---

# Business Impact

A predictive system like this can help financial institutions:

* Speed up loan evaluation processes
* Reduce manual workload
* Improve decision consistency
* Minimize financial risk

---

# Future Improvements

Future work could include:

* Testing additional machine learning models
* Applying feature engineering techniques
* Addressing class imbalance
* Deploying the model as a web application

---

# Project Structure


Loan-Eligibility-Prediction
│
├── Loan_Eligibility_Prediction.ipynb
├── Loan_Eligibility_Dataset.csv
└── README.md


---

# Author

Data Science Project focused on *loan approval prediction using machine learning techniques.*
