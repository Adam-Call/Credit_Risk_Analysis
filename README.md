# Credit_Risk_Analysis

## Overview of Project
For this project we will be taking data provided from LendingClub and building different machine learning models so we can compare the models and find which will be the best model to use for predicting credit risk. We will be using the imbalanced-learn and skikit-learn libraries to build and evaluate models using resampling. 

First model will be trying to oversample the data using the _RandomOverSampler_ and _SMOTE_ algorithms. Second model will undersample the data using _ClusterCentroids_. Next using _SMOTEENN_ algorithm to try a combination appproach of over and undersampling. Lastly using _BalancedRandomForestClassifier_ and _EasyEnsembleClassifier_ to reduce bias from the data.

## Results

- ![random_sampling](https://user-images.githubusercontent.com/80363261/125189004-c8fd0c80-e1fb-11eb-8c0c-49e2ff12ebda.png)

- ![smote_sampling](https://user-images.githubusercontent.com/80363261/125189010-ce5a5700-e1fb-11eb-9d69-84ddb9b4f306.png)

- ![undersampling](https://user-images.githubusercontent.com/80363261/125189014-d31f0b00-e1fb-11eb-9190-3de16377ade1.png)

- ![smoteen](https://user-images.githubusercontent.com/80363261/125189019-d7e3bf00-e1fb-11eb-8f37-a447eced821d.png)

- ![random_forest](https://user-images.githubusercontent.com/80363261/125189024-dc0fdc80-e1fb-11eb-8c7f-5e880db3d639.png)

- ![ensemble](https://user-images.githubusercontent.com/80363261/125189026-e03bfa00-e1fb-11eb-9592-9fe7342580c7.png)


## Summary

The random oversampling provides a strong first attempt at predicting the credit card risk with an accuracy score of 66%. Using the SMOTE oversampling there is a reduction in accuracy. Under sampling the split data set further reduces the accuracy of the machine learning model. The combination (over and under) sampling using the SMOTEEN model has a similar accuracy to the random oversampling model used. Both of the ensemble learning models work extremely well providing nearly 100% accuracy. Using the ensemble models with a high number of estimators, 100, we see why the accuracy is so much higher. 

Based on the results we had the machine learning model recommended for future use is the _EasyEnsembleClassifier_ as it had the highest accuracy. 
