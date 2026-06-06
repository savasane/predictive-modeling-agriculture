# Predictive Modeling for Agriculture

A multi-class classification project that predicts the optimal crop type for a given field based on soil measurements.

## Overview

This project uses Logistic Regression to determine which crop should be planted in a field given the soil's nitrogen (N), phosphorus (P), potassium (K), and pH levels. Additionally, the model identifies which single soil feature has the strongest predictive performance.

## Dataset

`soil_measures.csv` contains the following columns:
- `N`: Nitrogen content ratio in the soil
- `P`: Phosphorus content ratio in the soil
- `K`: Potassium content ratio in the soil
- `pH`: pH value of the soil
- `crop`: Target variable, categorical crop names

## Methods

- Data loading and preparation with pandas
- Train/test split (80/20) using sklearn
- Multinomial Logistic Regression trained on each individual feature
- Performance evaluation via F1 score per feature
- Identification of the best predictive feature

## Technologies

- Python 3
- pandas
- scikit-learn

## Author

Alp Savaşan — Wirtschaftswissenschaften student at TU Dortmund
