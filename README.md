# Predict the Success of Bank Telemarketing

This project aims to predict the success of bank telemarketing campaigns using machine learning techniques. The analysis is performed using Jupyter Notebooks.

## Project Overview

This repository contains the code to build and evaluate machine learning models to predict the success of telemarketing campaigns.

### Project Steps

1. **Exploratory Data Analysis (EDA)**: Understand and summarize the main characteristics of a dataset before diving into modeling.
2. **Data Preprocessing**: Prepare raw data for analysis or machine learning models by cleaning, transforming, and organizing it. 
3. **Feature Engineering**: Transform and enrich the raw dataset into a format better suited for predictive modeling.

## Modeling

1. **Logistic Regression**: A statistical model used for binary or multi-class classification problems, predicting probabilities of categories based on input features.
2. **K-Nearest Neighbours**: A simple, non-parametric algorithm used for classification and regression. It works by identifying the 'k' nearest data points to a query point and assigning the most common class among them.
3. **Random Forest Classifier**: A robust ensemble learning method that combines multiple decision trees to improve classification accuracy and prevent overfitting.
4. **HistGradientBoostingClassifier**: A high-performance implementation of gradient boosting, designed for faster training on large datasets by binning continuous features into discrete bins. It builds decision trees sequentially, where each tree corrects the errors of the previous ones, making it effective for complex datasets.

## Choosing the Best Model
Based on the F1 score, Random Forest Classifier with hyperparameters tuned using RandomizedSearchCV is chosen for the final submission.
