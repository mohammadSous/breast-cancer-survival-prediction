# Breast Cancer Survival Classification

A machine learning classification project that predicts breast cancer patient survival outcomes using demographic and clinical data.

This project demonstrates a complete end-to-end machine learning workflow, including exploratory data analysis, data cleaning, preprocessing, feature engineering, model training, hyperparameter tuning, model evaluation, and prediction on unseen data.

## Project Overview

The dataset contains demographic and clinical information about breast cancer patients, including age, tumor characteristics, cancer stage, hormone receptor status, and lymph node information.

The objective is to predict a patient's survival status:

* Alive
* Dead

using the available patient features.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Machine Learning Workflow

### 1. Data Exploration and Visualization

* Dataset inspection using `.head()`, `.info()`, and `.describe()`
* Class distribution analysis
* Feature distribution visualizations
* Correlation heatmap analysis
* Scatter plots exploring relationships between clinical variables

### 2. Data Cleaning

* Missing value inspection
* Duplicate detection and removal
* Feature selection
* Column name standardization

### 3. Preprocessing

* Feature and target separation
* Target encoding
* Train-test split (80/20)
* One-hot encoding of categorical features
* Numerical feature scaling using StandardScaler

### 4. Model Training

Two classification algorithms were trained and evaluated:

* Logistic Regression
* Random Forest Classifier

### 5. Hyperparameter Tuning

Logistic Regression:

* Regularization tuning using different `C` values
* Class imbalance handling using `class_weight="balanced"`

Random Forest:

* Tree depth tuning using `max_depth`
* Forest size tuning using `n_estimators`
* Class imbalance handling using `class_weight="balanced"`

### 6. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Reports
* Confusion Matrices

Special attention was given to class imbalance and minority-class performance.

### 7. Model Comparison

Three final model configurations were compared:

* Logistic Regression
* Balanced Logistic Regression
* Tuned Random Forest

The comparison highlighted the trade-offs between overall accuracy and minority-class detection performance.

### 8. Prediction on New Data

The final model was used to generate predictions on synthetic patient profiles and provide prediction probabilities for each outcome class.

## Key Learning Outcomes

This project demonstrates practical experience with:

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Feature Encoding
* Feature Scaling
* Handling Imbalanced Datasets
* Logistic Regression
* Random Forest Classification
* Hyperparameter Tuning
* Model Evaluation
* Model Comparison
* Prediction Pipelines

## Disclaimer

This project is intended for educational and portfolio purposes only. The generated predictions should not be interpreted as medical advice or used for clinical decision-making.
