# Wine Quality Analysis using Semi-Supervised Learning

## Overview

This project investigates machine learning techniques for wine classification and wine quality prediction using physicochemical measurements.

The project is divided into two parts:

- Semi-Supervised Learning for predicting missing wine types.
- Regression and model evaluation for predicting wine quality.

The workflow includes exploratory data analysis, feature engineering, model evaluation, hyperparameter tuning, and cross-validation.

---

## Datasets

Two datasets are used:

### 1. wine-missing.csv

Contains wine samples where some values of the **type** attribute are unknown.

The objective is to predict whether each unknown sample corresponds to **red** or **white** wine using Semi-Supervised Learning.

### 2. wine-full.csv

Contains complete information for all wine samples.

This dataset is used to predict wine quality scores through supervised regression.

---

## Project Workflow

### Part 1 – Semi-Supervised Learning

- Data exploration
- Missing label analysis
- Data preprocessing
- Random Forest classification
- Model evaluation
- Class balancing
- Confidence-based pseudo-labeling
- Iterative self-training

### Part 2 – Wine Quality Prediction

- Quality distribution analysis
- Comparison between red and white wines
- Sweet vs dry wine analysis
- Decision Tree Regression
- Model evaluation using MAE
- Multiple random seed evaluation
- Hyperparameter tuning
- Validation set comparison
- GridSearchCV
- Cross-validation
- Decision Tree visualization
- Feature importance analysis

---

## Machine Learning Techniques

- Semi-Supervised Learning
- Self-Training
- Random Forest Classifier
- Decision Tree Regressor
- Hyperparameter Tuning
- Cross Validation
- GridSearchCV

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Evaluation Metrics

Classification:

- Accuracy
- Precision
- Recall
- F1-score

Regression:

- Mean Absolute Error (MAE)

---

## Repository Structure

```
├── Assignment4_SemiSupervisedLearning.ipynb
├── wine-missing.csv
├── wine-full.csv
└── README.md
```

---

## Author

Georgia Takatzoglou

M.Sc. Data and Web Science

Physics Graduate | Machine Learning | Data Science
