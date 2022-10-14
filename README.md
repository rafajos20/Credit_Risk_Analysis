![](resourcesCR/CRA0.png) 

# Credit_Risk_Analysis

# Overview
Analyze credit card risk by training six Machine Learning models and evaluating each outcome.

# Results
* All models showed poor precision scores when predicting high risk credit applications.
* All models showed >= 0.60 recall scores in predicting high risk credit applications.
* Easy Ensemble AdaBoost Classifier topped the list predicting 0.91 high risk credit applications.
## Random Oversampling

 Model Accuracy = 0.637
 
 ![](resourcesCR/CRA1.png) 
 
## SMOTE Oversampling
Model Accuracy = 0.630

 ![](resourcesCR/CRA2.png) 

## Cluster Centroids
Model Accuracy = 0.516

 ![](resourcesCR/CRA3.png) 
 
## SMOTEEN
Model Accuracy = 0.638

![](resourcesCR/CRA4.png) 

## Balanced Random Forest Classifier
Model Accuracy = 0.788

![](resourcesCR/CRA5.png) 

## Easy Ensemble AdaBoost Classifier
Model Accuracy = 0.925

![](resourcesCR/CRA6.png)
 
# Summary

With a 0.925 accuracy and 0.91 recall score, the Easy Ensemble AdaBoost Classifier produced the best results when predicting high risk credit applications.
 


