# ML-Student-Performance-Prediction-and-Model-Evaluation

## Overview
This project analyzes a Student Performance dataset and builds two machine learning models:

1. **Linear Regression** to predict `exam_score`.
2. **Logistic Regression** to classify students as **Pass** or **Fail** using 50 marks as the passing threshold.

## Workflow
1. Exploratory Data Analysis (EDA)
2. Missing value and duplicate checking
3. Distribution and correlation analysis
4. Outlier inspection
5. Feature and target selection
6. Train-test splitting
7. Numerical and categorical preprocessing
8. Linear Regression
9. Regression evaluation
10. Pass/Fail classification
11. Logistic Regression
12. Confusion matrix and classification metrics
13. Training vs testing comparison
14. Identification of overfitting or underfitting
15. Five data-driven insights

## Evaluation Metrics
### Regression
* MAE
* RMSE
* R² Score

### Classification
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Data Leakage Prevention
Preprocessing is performed using a Scikit-learn pipeline. Imputation, scaling, and categorical encoding are fitted only on the training data and then applied to the testing data.

## Tools Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Learning Outcome
After completing this assignment, I learned how to perform a complete machine learning workflow, from EDA and preprocessing to regression and classification. I also learned how to evaluate models using appropriate metrics and compare training and testing performance to identify possible overfitting or underfitting.

## Author
**Name:** Sukhmanpreet Kaur
