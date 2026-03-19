# california-housing-ml
California Housing Price Prediction: End‑to‑End Machine Learning Project
Author: Sadique Amin
Degree: MSc Data Science & Analytics, Cardiff University
Book Reference: Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow (3rd Ed.)
Project Type: Portfolio

## Project Overview
This project builds an end‑to‑end machine learning pipeline to predict median house prices in California districts using the well‑known California Housing Dataset.
It follows a full ML workflow:

1. Data acquisition & loading
2. Exploratory data analysis (EDA)
3. Geographical visualization
4. Feature engineering
5. Data cleaning & preprocessing
6. Encoding categorical attributes
7. Scaling numerical features
8. Custom transformers
9. Pipeline + ColumnTransformer
10. Model training
11. Cross‑validation
12. Hyperparameter tuning
13. Feature importance analysis
14. Confidence intervals
15. Model persistence (saving .pkl)

The goal is to demonstrate practical, real‑world machine learning skills using Scikit‑Learn.

## Dataset
The dataset is sourced from:
https://github.com/ageron/data/raw/main/housing.tgz

It contains district‑level data such as:

Longitude / Latitude
Housing median age
Total rooms
Total bedrooms
Population
Median income
Ocean proximity
Median house value (target)

This dataset is frequently used for demonstrating regression modelling techniques.

## Key Machine Learning Concepts Demonstrated:

Exploratory Data Analysis

Summary statistics
Histograms
Geographical scatter plots
Correlation matrix
Scatter matrix

Feature Engineering

rooms_per_house
bedrooms_ratio
people_per_house
Log transforms
RBF similarity features (custom)

Data Preparation

Median imputation
One‑Hot Encoding
Standard scaling
Creating custom transformers
ColumnTransformer for mixed data

Model Training & Evaluation

Linear Regression
Decision Tree Regressor
Random Forest Regressor
RMSE evaluation
K‑Fold cross‑validation

Hyperparameter Tuning

Grid Search
Randomized Search with distributions
Best estimator selection

Final Analysis

Feature importances
Test set evaluation
95% confidence interval for RMSE
Saving and loading the trained model

## Technologies Used

Programming - Python
Data Handling - Pandas, NumPy
Visualization - Matplotlib
Machine Learning - Scikit‑Learn
Model Persistence - Joblib
Statistics - SciPy

## Model Performance (Example)
You can update these values after running your script:

Final model: RandomForestRegressor
Test RMSE: (insert value)
95% Confidence Interval: (insert lower) - (upper)

## Project Purpose
This project is part of my MSc Data Science & Analytics journey at Cardiff University, and serves as:

A hands‑on exercise in full ML pipelines
A demonstration of practical data science skills
A portfolio project for employers and recruiters
A way to revisit and deepen understanding of ML fundamentals

## Contact
If you have questions or suggestions, feel free to reach out:
GitHub: https://github.com/sadiqueamin-1999





























CategoryToolsProgrammingPythonData HandlingPandas, NumPyVisualizationMatplotlibMachine LearningScikit‑LearnModel PersistenceJoblibStatisticsSciPy
