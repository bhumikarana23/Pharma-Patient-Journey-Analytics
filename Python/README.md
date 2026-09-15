# Python Analysis

This folder contains the Python-based analysis performed for the Pharma Patient Journey Analytics project.

## Objective

The analysis focuses on understanding patient treatment journeys, identifying factors associated with therapy switching, and developing a machine learning model to predict treatment switching.

## Analysis Performed

- Data loading and validation
- Exploratory Data Analysis (EDA)
- Treatment switching analysis
- Analysis of patient demographics and disease severity
- Clinical and behavioral factor analysis
- Statistical hypothesis testing
- Patient segmentation using K-Means clustering
- Treatment switching prediction using Logistic Regression
- Random Forest model comparison
- Model evaluation using Accuracy, Precision, Recall, F1-Score, and ROC-AUC

## Machine Learning

Two classification approaches were evaluated:

- Logistic Regression
- Random Forest

A class-weighted Logistic Regression model was selected as the primary model because it provided better recall for identifying patients who switched therapy.

**Final Model Performance:**

- Accuracy: 67.40%
- Precision: 43.11%
- Recall: 69.42%
- F1-Score: 53.19%
- ROC-AUC: 0.743

## Patient Segmentation

K-Means clustering was used to segment patients based on:

- Age
- Disease duration
- Treatment duration
- Annual visits
- HbA1c
- BMI
- Medication adherence
- Treatment cost

Four patient segments were generated and compared based on their treatment-switching behavior.

## Files

| File | Description |
|------|-------------|
| `patient_journey_analysis.ipynb` | Complete Python analysis, statistical testing, machine learning, and patient segmentation |

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SciPy

## Note

The dataset used in this project is synthetic and does not contain real patient information.
