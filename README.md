🩺 Sepsis Detection System – Machine Learning Models
📌 Overview

This project implements a Sepsis Detection System using machine learning techniques applied to patient physiological data. The goal is to identify early signs of sepsis by training and evaluating multiple predictive models on clinical time-series data.

The notebook is designed to run in Google Colab and uses data stored in Google Drive.

📂 Dataset

Source: PhysioNet Sepsis Challenge 2019

Format: .psv files (one file per patient)

Data Type: Time-series physiological and clinical measurements

Key preprocessing steps:

Combined multiple patient files into a single dataset

Standardized column names

Converted categorical features to binary

Removed irrelevant columns (e.g., HospAdmTime)

Handled missing values using appropriate imputation strategies

Standardized numerical features for model compatibility

🛠️ Models Implemented

The notebook prepares data suitable for training and evaluating the following models:

Logistic Regression

LightGBM

XGBoost

The dataset is standardized to ensure consistent performance across all models.

⚙️ Workflow

Mount Google Drive

Load and merge patient data

Data cleaning & feature engineering

Missing value handling

Feature scaling and standardization

Dataset export for modeling

A standardized dataset is saved for downstream model training and evaluation.

💾 Output

Standardized dataset:
sepsis_standardized.csv (saved to Google Drive)

▶️ How to Run

Open the notebook in Google Colab

Mount your Google Drive when prompted

Update dataset path if required

Run all cells sequentially

📈 Use Case

This project demonstrates:

End-to-end ML pipeline development

Healthcare data preprocessing

Feature scaling for ML models

Practical application of ML in clinical decision support

🧠 Skills Demonstrated

Python (Pandas, NumPy, Scikit-learn)

Data preprocessing & cleaning

Machine learning for healthcare
