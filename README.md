# Data Science Programming Python Project
Contains an end-to-end pipeline for general machine learning applications (regression here)

## Problem Statement
The classical house prices prediction problem. For our use-case the market is Melbourne housing which has been seeing a bubble effect in terms of inflated prices. The ipynb includes :
- EDA to explore associations amidst independent variables (matplotlib, seaborn and folium for map)
- Pandas operations for data wrangling, feature engineering etc.
- Pipeline implementation to try out multitude of models viz. Decision trees, KNN, RF, LGB, XGB etc.
- Model importances with inbuilt feature importance, perturbation based techniques such as permutation-based importance and SHAP

## Key Inferences
- Location would be the highest predictor
- Bigger houses don't necessarily cost high unless it's the right one
- Mostly positive trend in rising prices, lesser seasonality

<img width="1099" alt="SHAP" src="https://user-images.githubusercontent.com/19775963/147893783-14071204-7805-4b58-a401-805d9bf200c9.png">

## Improvements
- Modularization
- Outlier treatment
- Bayesian Optimization for Hyperparameter tuning

