# Library_occupancy_ML
Explainable ML system for predicting and recommending library study spaces using an engineered XGBoost-SHAP model for KNUST smart campus decision support.


# Library Occupancy Prediction System (KNUST)

## Overview
This project develops an explainable machine learning system for predicting library occupancy levels and recommending alternative study spaces within KNUST using an engineered XGBoost-SHAP framework.

## Model
- Baseline: XGBoost, Random Forest, LightGBM
- Engineered Model: E-XGBoost-Lib (XGBoost + custom asymmetric loss + SHAP feature pruning)

## Features
- Occupancy prediction
- Study space recommendation
- Explainable AI using SHAP
- Comparative baseline evaluation

## Evaluation
- Accuracy, Precision, Recall, F1-score
- AUC-ROC, AUC-PR
- Wilcoxon Signed-Rank statistical test

## Reproducibility
- Fixed seed = 42
- 70/15/15 train/val/test split
- 5-fold cross-validation

## Status
Ongoing academic research project (KNUST)
