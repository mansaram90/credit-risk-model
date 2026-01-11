# credit-risk-model
A model to predict credit risk for non-bank financial institutions

An end to end Credit Risk Modelling application built for Non Banking Financial Institution (NBFC) use cases.
This project focuses on combining credit risk domain understanding with interpretable machine learning and applied statistics to support real world lending decisions.

📌 Project Overview

The goal of this project is to simulate how credit analysts assess borrower risk by translating raw customer and loan data into a risk driven decision framework.

The application allows a credit assessor to input borrower and loan details and evaluate risk using a trained ML model that prioritises interpretability, stability and business alignment.

🏦 Credit Risk Domain Concepts Covered

This project is strongly rooted in lending and risk analytics concepts:

Loan to Income Ratio

Credit Utilisation Ratio

Delinquency Ratio and Average DPD

Loan Tenure and Loan Amount

Open Loan Accounts

Residence Type

Loan Purpose and Loan Type

The focus was on ensuring every feature has clear business meaning and mirrors how risk is assessed in real NBFC workflows.

📊 Machine Learning and Statistical Approach

Rather than using a black box model, the emphasis was on transparent and explainable modelling.

Key techniques applied:

Weight of Evidence (WOE) for feature transformation

Information Value (IV) for feature selection

Rank Ordering to validate monotonic risk behaviour

KS Statistic to measure model discriminatory power

Optuna for hyperparameter tuning and optimisation

Focus on model stability and interpretability, not just accuracy

These techniques are commonly used in regulated financial environments where explainability is critical.

🖥️ Application Interface

The application provides a simple and intuitive interface for credit assessors:

User friendly input of borrower and loan attributes

Real time risk calculation

Domain aligned terminology for non technical users

Designed with business users in mind

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit learn

XGBoost

Optuna

Streamlit (for application interface)

Applied statistics and ML best practices

🎯 Key Learning Outcomes

Stronger understanding of credit risk and lending workflows

Practical application of WOE, IV, KS and rank ordering

Building ML models aligned with business decision making

Experience converting an ML model into a usable risk assessment tool

🚀 Future Improvements

Model monitoring and stability tracking

Scorecard style risk banding

Explainability dashboards for business users

Integration with real loan origination workflows

📬 Contact

If you are interested in credit risk modelling, risk analytics or applied machine learning, feel free to connect with me on LinkedIn or reach out via GitHub.

If you want, I can also:

Add a Results and Evaluation section

Create a Project Architecture diagram

Tailor this README for banking vs fintech recruiters

Write a short version for
