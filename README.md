# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:

The purpose of this analysis is to predict credit risk by using the credit card credit dataset from LendingClub which is a peer-to-peer lending services company. We will conduct the oversampling and undersampling strategies by using the RandomOverSampler and SMOTE algorithms, and the ClusterCentroids algorithm techniques. Then, the combinatorial approach of over- and undersampling using the SMOTEENN algorithm will take place. Finally, we will predict the credit risk by comparing two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results:

### Naive Random Oversampling

<img width="797" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/107653012/195470273-8cb6068d-d551-4708-ba02-a4bb376989da.png">

° The naive accuracy score is 0.6447 meaning that this model accurately predicts credit risk 64.47% of the time

° The precision of the high risk apllicants is 0.01 and 1.00 for low risk applicants.  meaning that 100% of the predicted low risk applicants are actually low risk, but only 1% of the predicted high risk applicants are actually high risk.

° According to recall 70% of high risk applicants are classified as high risk and 59% of low risk applicants are classified as low risk.

## Summary:
There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
