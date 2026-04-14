# Cancer Diagnosis Prediction (Decision Tree + Random Forest)

This project trains and evaluates machine learning models to predict a binary `diagnosis` outcome using common risk and lifestyle features. It includes a simple training workflow, model evaluation (classification report + confusion matrix), feature importance, and saving the trained Random Forest model for later use.

## What this repo contains

- A notebook (`notebooks/cancer_prediction.ipynb`) that:
  - loads `cancer_data.csv`
  - selects features and target
  - splits the dataset into train/test
  - trains a Decision Tree and a Random Forest model
  - prints a classification report
  - plots a confusion matrix using Seaborn + Matplotlib
  - calculates feature importance (Random Forest)
  - saves the trained model using `joblib`


## Dataset

Find the dataset at:
Kaggle: https://www.kaggle.com/datasets/rabieelkharoua/cancer-prediction-dataset

## Features used:
- `age`
- `gender`
- `bmi`
- `smoking`
- `genetic_risk`
- `physical_activity`
- `alcohol_intake`
- `cancer_history`

## Target:
- `diagnosis` (typically 0/1)

## Findings:
- Built and compared Decision Tree and Random Forest classifiers.
- Identified key predictive features including: age, BMI, alcohol intake, physical activity, cancer history.
- Delivered interpretable insights into risk factors influencing cancer diagnosis.



