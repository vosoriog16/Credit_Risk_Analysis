# Credit_Risk_Analysis

## Overview

The purpose of the this project was to apply machine learning to review credit card risk. We used data provided by LendingClub, we tested various algorythims for acccuracy to see which bests predicts low and high risk applicants.

# Results

## Naive Random Oversampling

![Naive Random Oversampling](https://user-images.githubusercontent.com/88119288/149676566-ae8ff929-a5bc-4485-83fe-bb8400587401.PNG)
-The balanced accuracy score was 0.5646.
-The precision scores for high risk are .01 and sensititvity .50; for low risk are 1 and sensitivity.63

## SMOTE Oversampling
![SMOTE Oversampling](https://user-images.githubusercontent.com/88119288/149676700-c1bb359c-d1dc-4ece-9bc6-939b783911cb.PNG)
-The balanced accuracy score was 0.6734.
-The precision scores for high risk are .01 and sensititvity .71; for low risk are 1 and sensitivity.64

## Undersampling
![Undersampling](https://user-images.githubusercontent.com/88119288/149676705-76a216e4-c598-4681-84cb-54c57c3d5f44.PNG)
-The balanced accuracy score was 0.4890.
-The precision scores for high risk are .01 and sensititvity .60; for low risk are .99 and sensitivity.38


## Combination (Over and Under) Sampling
![Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/88119288/149676680-33df9b4e-ef31-4f6a-828f-ddb291c214e7.PNG)
-The balanced accuracy score was 0.6054.
-The precision scores for high risk are .01 and sensititvity .68; for low risk are 1 and sensitivity.53


## Balanced Random Forest Classifier
![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/88119288/149676677-59f8ae06-f5b1-4cf4-b460-dffeef6bd7b2.PNG)
-The balanced accuracy score was 0.8905.
-The precision scores for high risk are .03 and sensititvity .74; for low risk are 1 and sensitivity.89


## Easy Ensemble AdaBoost Classifier
![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/88119288/149676685-9cf53975-c3f5-40c3-b085-a608ed83e896.PNG)
-The balanced accuracy score was 0.8905.
-The precision scores for high risk are .03 and sensititvity .74; for low risk are 1 and sensitivity.89

## Summary
From all models, both the balanced random forest classifier and easy ensemble had the highest accuracy score at 89%. Out of all methods, the one with least accuracy was undersampling with .48 accuracy. 
