# Introduction

## Overview

This project focuses on building a robust **Machine Learning pipeline** for predicting **loan default probabilities**. The pipeline leverages advanced models, interactive tools, and cloud-based deployment to provide an end-to-end solution for real-time loan risk assessment.

## Objectives

The main goals of this project are:
- **Loan Default Prediction**: Develop models to classify whether a customer is likely to default on their loan based on historical data.
- **Interactive Application**: Provide an intuitive interface for users to input loan-related features and get real-time predictions.
- **Scalable Deployment**: Deploy the machine learning models using **FastAPI**, **Docker**, and **Streamlit**, making the application accessible to end-users.
- **End-to-End Workflow**: Enable reproducibility and transparency by integrating tools like **MLflow/DagsHub** for experiment tracking and version control.

## Key Features

- **Data Processing**: The pipeline handles diverse feature types, including numerical, categorical, and binary variables, ensuring accurate predictions.
- **Model Training**: A combination of techniques, including Random Forest and XGBoost, are used to maximize predictive performance.
- **Interactive Frontend**: A user-friendly Streamlit app allows users to input data dynamically and view predictions with explanations.
- **Deployment**: 
  - FastAPI powers the backend for predictions.
  - Docker ensures containerized, portable deployment.
  - Streamlit provides a seamless frontend experience.
  - The app is deployed on **DigitalOcean**, making it accessible worldwide.