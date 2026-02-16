# Ridge_and_lasso_regression_using_house_price_prediction
# 📌 Project Overview

This project builds a Machine Learning model to predict house prices based on multiple features such as area, number of rooms, house age, and location.The objective is to : Apply feature engineering, Prevent overfitting using regularization, Compare Ridge and Lasso regression models, Evaluate model performance using multiple metrics.
# 🎯 Problem Statement

Real estate companies need accurate house price predictions to make informed business decisions.This project aims to build a regression model that predicts house prices using structured data.
# 🛠️ Technologies Used

Python ,
Pandas ,
NumPy ,
Matplotlib ,
Scikit-learn .
# 🔄 Machine Learning Workflow

1. Data Loading
2. Data Cleaning
3. Feature Engineering
4. Feature Encoding
5. Feature Scaling
6. Model Training
7. Cross Validation
8. Model Evaluation
# 🔍 Feature Engineering

Created new feature: house_age ,
Applied One-Hot Encoding for categorical variables ,
Removed redundant columns ,
Standardized numerical features using StandardScaler .
# 🤖 Models Used
# 1️⃣ Ridge Regression (L2 Regularization)

Reduces overfitting ,
Keeps all features .
# 2️⃣ Lasso Regression (L1 Regularization)

Performs feature selection ,
Shrinks some coefficients to zero .
# 📊 Model Evaluation Metrics

| Metric   | Ridge      | Lasso      |
| -------- | ---------- | ---------- |
| MAE      | 61052      | 64500      |
| MSE      | 3861495844 | 4020000000 |
| R2 Score | 0.82       | 0.79       |
# 📈 Visualization

Actual vs Predicted Price Scatter Plot .
# 🧠 Key Learnings

Importance of feature engineering ,
Handling multicollinearity ,
Preventing overfitting using regularization ,
Using cross-validation for reliable performance estimation .
# 🚀 Future Improvements

Hyperparameter tuning using GridSearchCV ,
Add Random Forest and Gradient Boosting models ,
Deploy model using Flask or Streamlit .


