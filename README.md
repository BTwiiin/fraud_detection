# Credit Card Fraud Detection

An exploratory machine learning project for the Kaggle [Playground Series — Season 6, Episode 11](https://www.kaggle.com/competitions/playground-series-s6e11/overview). The goal is to predict the probability that a transaction is fraudulent (`is_fraud`) from tabular data. Submissions are evaluated using **ROC-AUC**.

## What This Project Explores

The project examines transaction details, customer activity, authentication methods, merchant characteristics, and geographic and behavioral signals associated with fraud. It focuses on data analysis, feature engineering, model error analysis, and ensembling.

## Current Progress

- EDA and feature interaction analysis;
- a CatBoost baseline with 5-fold cross-validation — OOF ROC-AUC: `0.946094`;
- feature engineering and feature selection experiments;
- analysis of difficult false-positive and false-negative cases;
- comparison of CatBoost, LightGBM, and XGBoost;
- a three-model blend — OOF ROC-AUC: `0.946414`, with a submission file ready.

The work is organized as a sequence of numbered notebooks in [`notebooks/`](notebooks).
