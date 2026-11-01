# Wine Quality Multiclass Classification

## Overview

This project focuses on predicting red wine quality from physicochemical characteristics using supervised Machine Learning techniques.

The objective is to compare different classification algorithms, investigate the effects of class imbalance and synthetic noise, and evaluate the impact of dimensionality reduction on predictive performance.

The project was developed as part of a university assignment at Politecnico di Torino.

## Methodology

Three supervised learning algorithms were evaluated:

- **K-Nearest Neighbors (KNN):** distance-based classification with hyperparameter tuning.
- **Logistic Regression:** linear probabilistic classification for multiple quality categories.
- **Random Forest:** ensemble learning for modeling nonlinear relationships between wine characteristics and quality scores.

The analysis also includes:

- Exploratory Data Analysis (EDA).
- Missing-value imputation and feature scaling.
- Feature selection.
- Class imbalance handling through oversampling.
- Principal Component Analysis (PCA).
- Hyperparameter tuning and cross-validation.
- Comparison between clean and noisy datasets.

## Model Evaluation

Model performance was assessed using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion matrices

Particular attention was given to macro-averaged F1-Score due to the imbalance between wine quality classes.

## Results

The experimental analysis highlights the challenges of multiclass classification with imbalanced data.

Random Forest showed promising performance compared with the other evaluated approaches, while PCA did not consistently improve classification accuracy.

The experiments also demonstrate the importance of considering class-specific performance rather than relying exclusively on overall accuracy.
