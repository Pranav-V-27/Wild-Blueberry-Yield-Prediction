# Wild Blueberry Yield Prediction

## Overview

This repository contains code for predicting wild blueberry yield based on the Wild Blueberry Pollination Simulation Model. The dataset used for predictive modeling includes information on wild blueberry plant spatial traits, bee species composition, and weather conditions. The goal is to build machine learning models for early prediction of blueberry yield.

## Dataset

- The dataset consists of 777 records, each representing an average of 100 simulation runs.
- The target feature is "yield," which is a continuous variable.
- The dataset provides valuable information for researchers in the field of wild blueberry pollination.

## Problem Statement

The task is to classify the yield variable based on the other 17 features, and the evaluation metric used is the Root Mean Squared Error (RMSE) score.

## Files

- `WildBlueberryPollinationSimulationData.csv`: The dataset used for training and testing.
- `X_test_rf_df.csv`: CSV file containing the features of the test set used in the Random Forest model.
- `X_train_rf.joblib`: Joblib file containing the features of the training set used in the Random Forest model.
- `y_test.joblib`: Joblib file containing the target variable of the test set.
- `randomforest_blueberry_pollination_tuned_model.joblib`: Joblib file containing the tuned Random Forest model.

## Code

The Jupyter Notebook `Wild Blueberry Yield Prediction_Pranav.ipynb` includes the entire data analysis, preprocessing, feature selection, and model training process.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- catboost
- lightgbm

Install the required dependencies using:

pip install -r requirements.txt
