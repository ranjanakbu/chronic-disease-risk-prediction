# Chronic Disease Risk Prediction Using Machine Learning

## Project Overview

This capstone project investigates whether machine learning models can predict chronic disease risk using lifestyle, demographic, and health indicators. Three healthcare datasets were analyzed to compare supervised and unsupervised machine learning techniques for predicting diabetes, obesity, and heart disease.

## Research Question

Can machine learning models identify individuals at risk for Type 2 diabetes, obesity, and heart disease, and which factors most consistently predict disease risk across these conditions?

## Datasets

- CDC Diabetes Health Indicators (~230,000 observations)
- UCI Obesity Level Estimation (2,087 observations)
- Cleveland Heart Disease (303 observations)

## Machine Learning Models

### Supervised Learning

- Linear Regression
- Regularized Regression
- Logistic Regression
- Support Vector Machines
- Decision Trees
- Random Forest
- K-Nearest Neighbors
- Gradient Boosting

### Unsupervised Learning

- K-Means Clustering
- DBSCAN
- Hierarchical Agglomerative Clustering

## Key Results

- Compared 11 machine learning algorithms across three healthcare datasets.
- Random Forest identified BMI and Income as important nonlinear predictors of diabetes risk.
- Gradient Boosting achieved the strongest overall supervised performance.
- K-Means identified meaningful clusters in the Obesity and Heart Disease datasets.
- Across multiple supervised models, the CDC Diabetes dataset consistently plateaued near a macro F1 score of 0.40, suggesting limitations in the available survey-based features rather than the algorithms themselves.
- Results across multiple supervised models demonstrated consistent performance trends, providing evidence that feature quality had a greater impact than algorithm selection for the CDC Diabetes dataset.

## Technologies

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Jupyter Notebook

## Repository Structure

The repository contains notebooks documenting the progression of the capstone project from Week 1 through Week 11, covering linear regression, regularization, feature selection, classification, ensemble learning, and clustering techniques, along with the Milestone 1 and Milestone 2 summary reports.

## Author

Ranjana Kumari

Boston University

M.S. Data Science
