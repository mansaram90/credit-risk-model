# Credit Risk Prediction | Machine Learning & Deployment Project

This project is an end to end Machine Learning application that predicts credit risk using customer demographic and financial data, deployed as an interactive Streamlit web app.

The focus of this project is not only model building, but also production readiness, deployment debugging, and engineering best practices, similar to what is expected in real industry ML workflows.

🔗 Live Application
https://credit-risk-model-manish-mllearning.streamlit.app/

Business Problem

Financial institutions must assess credit risk accurately to reduce defaults while maintaining customer accessibility.
This application demonstrates how machine learning can support data driven credit decisions by evaluating multiple customer attributes in real time.

What This Project Demonstrates
Machine Learning Skills

Feature engineering and preprocessing pipelines

Handling numerical and categorical data consistently

Logistic Regression based credit risk classification

Model persistence using joblib

Ensuring feature parity between training and inference

Engineering and Deployment Skills

Building a user facing ML application using Streamlit

Debugging model loading and dependency conflicts in cloud environments

Managing Python and library version compatibility

Using requirements.txt and runtime.txt for reproducible builds

Reading and interpreting deployment logs to resolve failures

Structuring ML projects for clean separation of UI, logic, and artifacts

Version Control and Collaboration

Using Git and GitHub for source control

Handling push conflicts and rebasing safely

Maintaining a clean, deployable repository structure

Tech Stack

Python

pandas, numpy

scikit-learn

joblib

Streamlit

Git, GitHub

Project Structure
credit-risk-model/
│
├── artifacts/
│   ├── trained_model.joblib
│   ├── scaler.joblib
│
├── main.py                 # Streamlit UI
├── prediction_helper.py    # Inference & preprocessing logic
├── requirements.txt        # Dependency management
├── runtime.txt             # Python version pinning
├── README.md
└── .gitignore

Key Learnings

Production ML requires strict consistency between training and deployment environments

Version mismatches can silently break deployed models

Deployment debugging is a core ML engineering skill

Reproducibility and environment control are as important as model accuracy

Why This Matters

This project reflects how ML systems are built and deployed in practice, not just in notebooks. It demonstrates the ability to:

Translate a business problem into an ML solution

Build reliable, deployable systems

Troubleshoot real world deployment issues

Author

Manish Pareek
Machine Learning and Data Science Enthusiast
GitHub: https://github.com/mansaram90


