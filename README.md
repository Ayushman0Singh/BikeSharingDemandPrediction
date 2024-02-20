# BikeSharingDemandPrediction

## Overview

Bike-sharing systems automate the process of renting and returning bicycles through a network of locations in a city. This project focuses on predicting the demand for shared bikes using supervised machine learning regression techniques. The goal is to model how demand varies with different features, allowing the management to adjust business strategies accordingly and understand the demand dynamics in a new market.

## Problem Statement

The task involves modeling the demand for shared bikes as a regression problem, predicting a continuous variable. The project addresses the challenge of understanding how demand varies with independent variables and how management can adapt strategies to meet customer expectations.

## Exploratory Data Analysis (EDA)

- Examined individual distributions of variables.
- Applied transformations for normal distribution.
- Conducted hypothesis-driven EDA to verify business-critical hypotheses.

## Data Preparation

- Null-value treatment.
- Feature engineering.
- Encoding categorical columns.
- Standardizing numeric features.

## Model Training

- Split data into train and test sets.
- Applied various machine learning models for predicting rented_bike_count:
  - Linear Regression
  - Regularized LR
  - Decision Tree
  - Random Forest
  - Ada-Boost
  - GBM (Gradient Boosting Machine)

## Model Evaluation

- Hyperparameter tuning for all algorithms.
- Best hyperparameters considered for model training.
- Model Performance:
  - GBM: R-square value of 0.88 (Best performer).
  - Random Forest: R-square value of 0.84.
  - Decision Tree Regressor: R-square value of 0.76.
  - Ada-Boost: R-square value of 0.58 (Least performer).

## Conclusion

This project successfully addresses the regression problem of predicting bike-sharing demand. The Gradient Boosting Machine (GBM) model demonstrated the best performance, achieving an R-square value of 0.88. Further improvements could involve exploring additional features or trying advanced regression techniques.
