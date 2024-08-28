This project aims to analyze employee turnover using logistic regression and random forest classifiers. The goal is to identify the key factors that influence whether an employee stays with the company or leaves, and to visualize the performance of the predictive models using confusion matrices.

Project Structure
The project is organized as follows:

notebooks/: Jupyter notebooks with the full analysis, including data preprocessing, model training, and evaluation.
README.md: This file, providing an overview of the project and instructions for usage.
Analysis Workflow
Data Loading and Preprocessing:
The dataset is loaded and preprocessed to handle missing values, encode categorical variables, and normalize numerical features.

Feature Selection:
Recursive Feature Elimination (RFE) is used with a logistic regression model to select the top 10 most important features influencing employee turnover.

Model Training:

A Logistic Regression model is trained on the training data to predict employee turnover.
A Random Forest model is also trained for comparison.
Model Evaluation:

Predictions are made on the test dataset.
Confusion matrices are generated to evaluate the performance of both models. The confusion matrices are visualized using heatmaps to provide clear insights into model accuracy.
Results
Logistic Regression Model
Confusion Matrix:

Interpretation:
The logistic regression model's performance is summarized in the confusion matrix. The model correctly identifies employees who are likely to leave the company (Left) and those who will stay (Stayed).

Random Forest Model
Confusion Matrix:

Interpretation:
The random forest model is evaluated similarly, providing a comparison with the logistic regression model to understand which model performs better in predicting turnover.
