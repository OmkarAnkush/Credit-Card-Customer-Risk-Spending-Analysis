# Credit Card Customer Risk & Spending Analysis

## Project Overview

This project focuses on analyzing credit card customer behavior using Machine Learning techniques. The objective is to predict customer credit limits, classify default risk, identify high-risk customers, and compare the performance of different machine learning models.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison.

---

## Project Objectives

* Predict Customer Credit Limits using customer demographics and financial history.
* Classify Default Risk by identifying customers likely to default on their payments.
* Segment High-Risk Customers for targeted interventions and personalized action plans.
* Compare multiple machine learning models and evaluate their performance.

---

## Dataset

Dataset: Credit Card Default Dataset

The dataset contains customer demographic information, credit history, bill amounts, payment amounts, and repayment status records.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Imbalanced-Learn (SMOTE)
* Joblib
* Jupyter Notebook

---

## Machine Learning Models

### Linear Regression

Used to predict customer credit limits.

### Logistic Regression

Used to classify customers as likely to default or not.

### Support Vector Machine (SVM)

Used to identify high-risk customers and perform risk segmentation.

---

## Project Workflow

1. Data Loading
2. Dataset Overview
3. Data Cleaning
4. Missing Value Analysis
5. Duplicate Value Analysis
6. Target Variable Analysis
7. Outlier Detection & Treatment
8. Correlation Analysis
9. Feature Engineering
10. Linear Regression
11. Logistic Regression
12. SMOTE Balancing
13. SVM Classification
14. Hyperparameter Tuning
15. Model Comparison
16. Sample Prediction
17. Model Saving

---

## Results

### Linear Regression

* R² Score ≈ 0.39

### Logistic Regression

* Accuracy ≈ 64%

### Support Vector Machine (SVM)

* Accuracy ≈ 77%

### Best Performing Model

Support Vector Machine (SVM)

---

## Saved Models

* linear_regression_model.pkl
* logistic_regression_model.pkl
* svm_model.pkl
* regression_scaler.pkl
* classification_scaler.pkl

---

## Repository Structure

```text
Credit-Card-Risk-Analysis
│
├── Credit_Card_Risk_Analysis.ipynb
├── README.md
├── requirements.txt
│
├── linear_regression_model.pkl
├── logistic_regression_model.pkl
├── svm_model.pkl
│
├── regression_scaler.pkl
└── classification_scaler.pkl
```

---

## Future Improvements

* Random Forest Classifier
* XGBoost
* LightGBM
* Streamlit Web Application
* Real-Time Risk Prediction System

---

## Author

Omkar Ankush

Diploma in Artificial Intelligence & Machine Learning

Ajeenkya DY Patil School of Engineering
