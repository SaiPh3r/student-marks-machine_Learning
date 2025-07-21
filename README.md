# 🎓 Student Grade Prediction with Machine Learning

This project focuses on predicting the final grades of students (on a scale of 1–10) using real-world data and supervised learning techniques. The goal is to build a regression model that can estimate students' academic performance based on various academic and socio-demographic features.

---

## 📌 Project Overview

- **Dataset**: [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/student+performance)
- **Target Variable**: `G3` (Final grade, range: 1–10)
- **Features Used**: Academic history, study time, failures, absences, school, family background, and more
- **Problem Type**: Regression

---

## 🧠 Machine Learning Approach

- **Preprocessing**:
  - Handled categorical variables using label encoding and one-hot encoding where appropriate
  - No missing values were present in the dataset
  - Normalized/standardized numeric features (where required)

- **Models Trained**:
  - Ridge Regression
  - Lasso Regression
  - **Random Forest Regressor** ✅ *(Best Performing)*
  - Hyperparameter tuning using `GridSearchCV`

- **Evaluation Metrics**:
  - MAE (Mean Absolute Error)
  - R² (Coefficient of Determination)











