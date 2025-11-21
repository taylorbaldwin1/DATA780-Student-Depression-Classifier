# DATA780-Student-Depression-Classifier

Repository: DATA780-Student-Depression-Classifier
Authors: Taylor Baldwin, Neha Bhattacharya, Troy Elbert, Shaneel Patel
Course: DATA780 - Machine Learning

📋 Project Overview

This project aims to build machine-learning classifiers to identify students at risk of depression using survey, demographic, and behavioural features. The objective is to explore patterns, train various models, compare performance of the models, and evaluate their performance in predicting depression status among students.

🗂️ Dataset & Pre-processing

The Training data was sourced from Kaggle: https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset/data

The dataset contains student responses, including demographics (age, gender, academic year), behavioral indicators (sleep patterns, extracurricular involvement, time spent studying), mental-health-related survey items, and a binary label indicating whether the student is depressed or not (or their risk level).

Shape: 141,000 records, 18 columns

Data cleaning steps: handle missing values, remove duplicates, clean column names.

Pre-processing

Encoding: One-hot encoding for categorical features

Feature scaling: continuous features (e.g. hours studied, sleep hours) are normalized or standardized.

Train/test split: e.g. 70% training, 30% test, with fixed random seed for reproducibility.

🧠 Modeling Approach

Several classification algorithms are implemented and compared: Bagging, Decision Tree, Random Forest, and XGBoost.

Feature Importance Analysis using SHAP values (for Tree-Based Models).

Evaluation metrics: accuracy, precision, recall, F1-score, confusion matrices, ROC/AUC.

Best-performing model selected and its performance reported on a held-out test set.
