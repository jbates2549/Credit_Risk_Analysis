# Credit_Risk_Analysis
Credit Risk Using Machine Learning

## Overview
In this analysis, we used machine learning in Jupyter Notebook to assess credit risk. We first compared resampling methods using logistic regression models. Then we evaluated the performances of some ensemble classifiers and made recommendations. As we all know credit risk is an unbalanced classification problem that many companies face. As the number of good loans easily outnumber the number of risky loans, many different techniques are applied to train and evaluate models with unbalanced classes.

## Objectives
Evaluate and implement the performance of machine learning models.
Balanced Random Forest Classifier, combines resampling ad model training in a single step.
Easy Ensemble Classifier, combines resampling ad model training in a single step.
Use resampling to attempt to address class imbalance.
Oversample the data using the RandomOverSampler and SMOTE algorithms.
Use a combination approach with the SMOTEENN algorithm.

## Analysis

First we have the analysis using oversampling method.
![image_name](https://github.com/jbates2549/Credit_Risk_Analysis/blob/main/Oversampling_classification.PNG)

The next analysis is for SMOTE oversampling
![image_name](https://github.com/jbates2549/Credit_Risk_Analysis/blob/main/SMOTE_oversampling.PNG)

We then use the undersampling method
![image_name](https://github.com/jbates2549/Credit_Risk_Analysis/blob/main/SMOTE_oversampling.PNG)

This is followed by SMOTE undersampling
![image_name](https://github.com/jbates2549/Credit_Risk_Analysis/blob/main/SMOTE_Undersampling.PNG)

We then use combination oversampling and undersampling
![image_name](https://github.com/jbates2549/Credit_Risk_Analysis/blob/main/combination_over_under.PNG)

The next method is logistic regression classifier using SKLEARN
![image_name](https://github.com/jbates2549/Credit_Risk_Analysis/blob/main/logistic_regression_classifier_sklearn.PNG)

Finally we use the easy ensemble method classifier.
![image_name](https://github.com/jbates2549/Credit_Risk_Analysis/blob/main/easy_ensemble_classifier.PNG)



## Summary of Results

Summary of precision and recall scores.
* Random Oversampling: precision 99%, recall 58%, F1 73%.
* SMOTE Oversampling: precision 99%, recall 68%, F1 81%.
* Undersampling: precision 99%, recall 41%, F1 58%.
* Combination: precision 99%, recall 57%, F1 72%.
* SKLEARN
* Easy Ensemble Classifier


SMOTE oversampling in my opinion is the most ideal as it has the highest balanced accuracy score of all the overall models.
