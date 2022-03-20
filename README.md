# Unit 11 - Risky Business
 
![Risk](Images/risk.png)

## Background

This repository evaluates several machine learning models to predict credit risk using data from peer-to-peer lending services. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so we employ different techniques for training and evaluating models with imbalanced classes. I used the imbalanced-learn and Scikit-learn libraries to build and evaluate models using resampling and ensemble learning.

- - -

## Resampling Results

* Simple Logistic Regression Balanced Accuracy Score = 0.9893

* Naive Random Oversampling Balanced Accurcy Score = 0.9946

* SMOTE Oversammpling Balanced Accurcy Score = 0.9947

* Undersampling Balanced Accurcy Score = 0.9948

* Combination SMOTEENN Balanced Accurcy Score = 0.9948

## Resampling Questions

*Which model had the best balanced accuracy score?*

Both undersampling and combination SMOTEEN had the best accurcy score of 0.9948.

*Which model had the best recall score?*

They all have a recal score of 0.99.

*Which model had the best geometric mean score?*

They all had a geo score of 0.99.

- - -

## Ensemble Learning Results 

* Balanced Random Forest Classifier Balanced Accurcy Score = 0.7493

* Easy Ensemble Classifier Balanced Accurcy Score = 0.9309

## Ensemble Questions

*Which model had the best balanced accuracy score?*

The Easy Ensemble Classifier had the best accuracy score of 0.9309.

*Which model had the best recall score?*

The Easy Ensemble Classifier had the best recall score of 0.94.

*Which model had the best geometric mean score?*

The Easy Ensemble Classifier had the best geo score of 0.93.

*What are the top three features?*

The top three features are total_rec_prncp, last_pymnt_amnt and total_pymnt_inv.

- - -

## Files

[Resampling Notebook](My_Code/credit_risk_resampling.ipynb)

[Ensemble Notebook](My_Code/credit_risk_ensemble.ipynb)

- - -

## Built With

* python

* pandas

* pathlib

* sklearn

* collections

* imblearn

- - -