# Weather Data Analysis and Predictive Modelling

## Overview

This project explores weather observations from multiple Australian locations using statistical analysis and machine learning techniques.

It investigates temperature relationships, rainfall prediction, model validation, and nonlinear patterns in weather data.

## Objectives

- Explore and analyse weather observations across multiple locations.
- Investigate relationships between temperature and other weather variables.
- Develop regression models to estimate maximum temperature.
- Build classification models to predict next-day rainfall.
- Compare model performance using different validation techniques.
- Investigate nonlinear relationships using polynomial regression, splines, and Generalized Additive Models (GAMs).

## Analysis and Methodology

### 1. Temperature Analysis and Regression
- Exploratory analysis of weather variables.
- Simple and multiple linear regression.
- Investigation of data leakage.
- Location-based regression interactions.

### 2. Rainfall Prediction and Classification
- Baseline classification.
- Logistic regression.
- Linear Discriminant Analysis (LDA).
- Quadratic Discriminant Analysis (QDA).
- Classification thresholds and ROC-AUC evaluation.

### 3. Model Validation
- Random and temporal train-test splits.
- Polynomial degree selection.
- Cross-validation.
- Leave-One-Station-Out validation.

### 4. Nonlinear Modelling
- Polynomial regression.
- Natural cubic splines.
- Smoothing splines.
- Generalized Additive Models.
- Temporal performance comparison.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- SciPy
- Scikit-learn
- Statsmodels

## Repository Structure

```text
weather-data-analysis/
│
├── Weather_Data_Analysis_and_Predictive_Modelling.ipynb
├── README.md
├── requirements.txt
└── data/
```

## How to Run

1. Clone this repository.
2. Install the dependencies listed in `requirements.txt`.
3. Open the notebook using Jupyter Notebook or JupyterLab.
4. Ensure the required dataset is available.
5. Run the notebook cells sequentially.

## Academic Background

This project originated as an academic applied project and has been organized for presentation as part of my data science portfolio. The analysis and results are presented in the accompanying notebook.

Original datasets and third-party materials remain subject to their respective ownership and usage permissions.

## Author

**Mukund Verma**

GitHub: [Your GitHub Profile](https://github.com/YOUR_USERNAME)
