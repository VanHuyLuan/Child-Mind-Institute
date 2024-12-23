﻿# [Kaggle Competition] Child Mind Institute — Problematic Internet Use

## Introduction
- This project aims to predict the level of problematic internet usage among children and adolescents using data on their physical activity and fitness.
- We develop a machine learning model to classify internet usage behavior into categories: None, Mild, Moderate, or Severe.

 ## Contributors
 Team 7
 - Văn Huy Luân _ 22028227 _ K67I-CS1
 - Trần Đại Dương _ 22028273 _ K67I-CS1
 - Hoàng Minh Đức _ 22028039 _ K67I-CS1

## Dataset
www.kaggle.com/competitions/child-mind-institute-problematic-internet-use/data

## Approach
1. Data Preprocessing
- Handling missing values using imputation.
- Scaling and encoding features for optimal model performance.
2. Exploratory Data Analysis (EDA)
- Understanding correlations between physical activity and internet usage.
- Visualizing feature distributions and target variable classes.
3. Model
- Implementing Gradient Boosting, XGBoost, and CatBoost.
- Fine-tuning hyperparameters for each model.
- Combining models through ensembling for better performance.
4. Evaluation
- Using Quadratic Weighted Kappa (QWK) to measure model accuracy.
- Optimizing thresholds for accurate classification.

## Result
- Score: 0.439
- Runtime: 3m32s
