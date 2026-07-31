# Chronic Disease Risk Prediction Using Machine Learning
## Project Overview
This capstone project investigates whether machine learning models can predict chronic disease risk using lifestyle, demographic, and health indicators. Three healthcare datasets were analyzed to compare supervised and unsupervised learning techniques.
## Research Question
Can machine learning models identify individuals at risk for Type 2 diabetes, obesity, and heart disease, and which factors most consistently predict disease risk across these conditions?
## Datasets
- CDC Diabetes Health Indicators (≈230,000 observations)
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
- Gradient Boosting achieved the strongest overall supervised performance.
- K-Means identified meaningful clusters in the Obesity and Heart Disease datasets.
- Across multiple supervised models, the CDC Diabetes dataset consistently plateaued near a macro F1 score of 0.40, suggesting limitations in the available survey-based features rather than the algorithms themselves.
## Technologies
- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Jupyter Notebook
## Repository Structure
Week1–Week11 notebooks demonstrate the progression of the capstone project from linear models through clustering methods.
## Author
Ranjana Kumari
Boston University
M.S. Data Science
