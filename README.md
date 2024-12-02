Auto Loan Credit Decisioning Analysis
This repository contains the code and report for the development of a predictive model to assess auto loan applications. The project focuses on building an accurate and fair machine-learning model to make data-driven lending decisions while ensuring fairness across demographic groups.

Project Overview
The project uses advanced data preprocessing and machine learning techniques to predict auto loan approvals based on various applicant attributes such as credit scores, income, loan details, and demographic information. The objective is to achieve high predictive accuracy while adhering to ethical standards for fairness.

Key Highlights:
Fairness Evaluation: Assessing bias across gender and racial groups.
Machine Learning Models: Implementation of Logistic Regression and Gradient Boosting.
Model Metrics: Precision, Recall, F1 Score, and AUC-ROC.
Recommendations: Deployment strategies for real-world use.

Features of the Project
1. Data Preprocessing
Handled missing values with imputation.
One-hot encoding for categorical variables.
Standardization of numerical features.
Removed multicollinearity through correlation analysis.
2. Model Development
Baseline Model: Logistic Regression for interpretability.
Advanced Model: Gradient Boosting for capturing non-linear relationships.
3. Fairness Analysis
Statistical and visual analysis to detect potential biases in predictions.
Bias evaluation using Chi-square tests for demographic groups.
4. Model Evaluation
Performance metrics: AUC-ROC, Precision, Recall, F1 Score.
Visualization of results through plots and confusion matrices.
How to Use
Prerequisites:
Python 3.8+
Libraries: pandas, numpy, matplotlib, seaborn, sklearn

Results
Gradient Boosting Model outperformed Logistic Regression with an AUC of 0.84.
No significant gender or racial bias detected in predictions.
