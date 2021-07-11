# Credit_Risk_Analysis

## Overview of Project
For this project we will be taking data provided from LendingClub and building different machine learning models so we can compare the models and find which will be the best model to use for predicting credit risk. We will be using the imbalanced-learn and skikit-learn libraries to build and evaluate models using resampling. 

First model will be trying to oversample the data using the _RandomOverSampler_ and _SMOTE_ algorithms. Second model will undersample the data using _ClusterCentroids_. Next using _SMOTEENN_ algorithm to try a combination appproach of over and undersampling. Lastly using _BalancedRandomForestClassifier_ and _EasyEnsembleClassifier_ to reduce bias from the data.

## Results

- Random oversampling
- SMOTE oversampling
- undersampling
- smoteen
- random forest
- ensemble

## Summary

The random oversampling provides a strong first attempt at predicting the credit card risk with an accuracy score of 66%. Using the SMOTE oversampling there is a reduction in accuracy. Under sampling the split data set further reduces the accuracy of the machine learning model. The combination (over and under) sampling using the SMOTEEN model has a similar accuracy to the random oversampling model used. Both of the ensemble learning models work extremely well providing nearly 100% accuracy. Using the ensemble models with a high number of estimators, 100, we see why the accuracy is so much higher. 

Based on the results we had the machine learning model recommended for future use is the _EasyEnsembleClassifier_ as it had the highest accuracy. 