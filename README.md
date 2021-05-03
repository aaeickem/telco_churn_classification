Telco Churn Classification Modeling Examples
================
Andrew Eickemeyer -
5/3/2021

This repo contains classification modeling examples written in R and
Python using the [Telco Churn
dataset](https://www.kaggle.com/blastchar/telco-customer-churn) found on
[Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn).

## XGBoost Example

The notebook
[xgboost\_example.ipynb](https://github.com/aaeickem/telco_churn_classification/blob/main/xgboost_example.ipynb)
performs exploratory data analysis on the [Telco Churn
dataset](https://www.kaggle.com/blastchar/telco-customer-churn), splits
the data into training, validation, and test sets, performs
cross-validation hyperparameter tuning for a gradient boosting model
using
[xgboost](https://xgboost.readthedocs.io/en/latest/python/python_intro.html),
chooses a classification cutoff based on the validation set, and reports
performance metrics for the model on the test set.
