# kaggle_titanic

## Overview
This repository contains code to Kaggle's [Titanic Machine Learning Challenge](https://www.kaggle.com/c/titanic/overview). 

## Structure
1. src. 
  - titanic_visualization.ipynb: This noteobook is used to perform exploratory data analysis and generate useful visualizations for feature selection and engineering.
  - titanic_model_building.ipynb: This notebook is used to perform cross-validation with different classification models and hyperparameter tuning to decide on an optimal classification model. 
  - titanic_model_predictions.ipynb: This notebook is used to fit the optimal model on the full training set and generate final predictions for the test set. 

2. data. 
  - input: This folder contains the training ('train.csv') and test ('test.csv') sets provided by Kaggle.
  - output: This folder contains the final predictions generated for submission ('submission.csv').
