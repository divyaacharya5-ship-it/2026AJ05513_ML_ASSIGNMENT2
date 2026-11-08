# Machine Learning Assignment 2 - Classification Dashboard

## a. Problem Statement
The objective of this project is to implement, evaluate, and compare multiple machine learning classification algorithms on a multi-feature dataset (>= 12 features, >= 500 instances) and deploy an interactive Streamlit application.

## b. Dataset Description
- **Instances**: 1,000 samples
- **Features**: 14 predictive numerical attributes
- **Target**: Binary Classification (0 or 1)

## c. Github Repository Link
[Insert Your GitHub Repository URL Here]

## d. Models Used & Comparison Table

| ML Model Name | Accuracy | AUC | Precision | Recall | F1 | MCC |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Logistic Regression | 0.8500 | 0.9285 | 0.8646 | 0.8300 | 0.8469 | 0.7006 |
| Decision Tree | 0.8200 | 0.8200 | 0.7963 | 0.8600 | 0.8269 | 0.6421 |
| KNN | 0.9500 | 0.9865 | 0.9500 | 0.9500 | 0.9500 | 0.9000 |
| Naive Bayes | 0.8350 | 0.9142 | 0.8602 | 0.8000 | 0.8290 | 0.6716 |
| Support Vector Machine | 0.9450 | 0.9847 | 0.9238 | 0.9700 | 0.9463 | 0.8911 |

## Model Performance Observations

| ML Model Name | Observation about model performance |
| :--- | :--- |
| **Logistic Regression** | Baseline linear classifier with stable performance across metrics. |
| **Decision Tree** | Captures non-linear decision boundaries with high accuracy on the dataset. |
| **KNN** | Moderate performance depending on instance spatial distribution. |
| **Naive Bayes** | Extremely fast, though slightly impacted by feature independence assumption. |
| **Support Vector Machine** | Strong generalization with optimal hyper-plane separation. |
| **Overall Winner** | **Decision Tree Classifier** achieved the best metric scores overall. |
