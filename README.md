# Insurance Charges Prediction using Regularized Regression Models

## Project Overview

This project explores the Medical Cost Personal Dataset and aims to predict individual insurance charges using Linear Regression and regularized regression techniques.

The primary objective was to compare the performance of Linear Regression, Ridge Regression, Lasso Regression, and Elastic Net Regression and investigate the effect of regularization on predictive performance.

---

## Dataset

The dataset contains demographic and health-related information about insurance beneficiaries, including:

* Age
* Sex
* BMI
* Number of Children
* Smoking Status
* Region
* Insurance Charges (Target Variable)

---

## Project Workflow

The project was completed through the following stages:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Preprocessing and Feature Encoding
* Correlation Analysis
* Train-Test Split
* Linear Regression
* Ridge Regression
* Lasso Regression
* Elastic Net Regression
* Hyperparameter Tuning
* Model Comparison and Conclusions

---

## Exploratory Data Analysis

The following analyses were performed:

* Distribution of Insurance Charges
* Distribution of Numerical Features
* Distribution of Categorical Features
* Age vs Charges Analysis
* BMI vs Charges Analysis
* Smoking Status vs Charges Analysis
* Correlation Analysis

---

## Machine Learning Models

The following models were implemented:

1. Linear Regression
2. Ridge Regression (L2 Regularization)
3. Lasso Regression (L1 Regularization)
4. Elastic Net Regression (L1 + L2 Regularization)

---

## Hyperparameter Tuning 

The alpha parameter was evaluated for:

* Ridge Regression
* Lasso Regression
* Elastic Net Regression

The impact of regularization strength on model performance was analyzed using multiple alpha values. 

--- 

## Best Model Performance

| Model                  | Best Alpha | R² Score |
| ---------------------- | ---------- | -------- |
| Linear Regression      | N/A        | 0.8069   |
| Ridge Regression       | 0.001      | 0.8069   |
| Lasso Regression       | 0.001      | 0.8069   |
| Elastic Net Regression | 0.001      | 0.8068   |

Linear Regression, Ridge Regression, and Lasso Regression achieved nearly identical predictive performance, 
while Elastic Net Regression produced slightly lower performance.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Key Findings

* Smoking status was identified as the strongest predictor of insurance charges.
* Age and BMI exhibited moderate positive relationships with medical expenses.
* Linear Regression, Ridge Regression, and Lasso Regression achieved nearly identical predictive performance.
* Elastic Net Regression was more sensitive to regularization strength.
* Strong regularization generally reduced predictive accuracy.
* The dataset does not exhibit substantial overfitting or severe multicollinearity.

---

## Conclusion 

The results demonstrate that regularization provides limited additional benefit for this dataset. 
Simple linear models already achieve strong predictive performance, indicating that the underlying relationships can be captured effectively without aggressive coefficient penalization. 

---

## Future Improvements

Possible future improvements include:

* Cross-Validation
* GridSearchCV Hyperparameter Optimization
* Random Forest Regression
* Gradient Boosting Regression
* XGBoost Regression
* Feature Importance Analysis
