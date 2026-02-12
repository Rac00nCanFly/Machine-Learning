# Machine Learning Exercises – Opossum Age Prediction

This repository contains exercises from a Machine Learning course.  
The main project in this repo is a **regression model predicting opossum age from physical measurements**.

---

## Overview

The goal of the exercise is to:

- explore a real-world biological dataset of opossums,  
- build a **Linear Regression** model to predict age from physical features,  
- apply **regularization (Lasso, Ridge)** and compare their impact on the model.

This fits well with my bioinformatics background – combining biology with data science and ML.

---

## Dataset

The dataset contains measurements of opossums, such as:

- skull dimensions and weight  
- body length and other physical features  
- age (target variable)

The task is to predict **age** based on these features.

---

## Methods

Models and techniques used:

- **Linear Regression** as a baseline
- **Lasso Regression** (L1 regularization)
- **Ridge Regression** (L2 regularization)
- **Train / validation split**
- Hyperparameter experiments with different penalty values (regularization strengths)

Evaluation:

- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- \( R^2 \) score  
- Visual comparison of predictions vs true age

---

## Tech Stack

- **Language**: Python 3  
- **Libraries**:  
  - `pandas` – data loading and preprocessing  
  - `numpy` – numerical operations  
  - `scikit-learn` – linear models, train/test split, metrics  
  - `matplotlib`, `seaborn` – plots and visualization  
- **Environment**: Jupyter Notebook (`Machine_Learning_exercise.ipynb`)

---

## Files

- `Machine_Learning_exercise.ipynb` – main notebook with:
  - data loading and basic EDA,
  - model training (Linear, Lasso, Ridge),
  - metrics and comparisons.

- `possum.csv` – dataset with opossum measurements and age.  

- `README.md` – project description.

---

## How to Run

1. Start Jupyter and open the notebook:

    ```
    jupyter notebook Machine_Learning_exercise.ipynb

    ```
2. Run all cells to:

- load the dataset,

- train Linear, Lasso, and Ridge models,

- compare their performance.

## What I practised in this project
 - End-to-end ML workflow on a tabular dataset:
    - loading data, cleaning, selecting features,
    - splitting into train/validation sets,
    - training and evaluating regression models.

 - Understanding how L1 and L2 regularization:
    - affect model coefficients,
    - help control overfitting,
    - change performance metrics.

 - Using Python ML stack (pandas + scikit-learn) in a reproducible notebook.
## Possible Extensions
- Add cross-validation and more systematic hyperparameter search
- Try non-linear models (Random Forest, Gradient Boosting) for comparison
- Perform more feature engineering and domain-based analysis of which measurements matter most
