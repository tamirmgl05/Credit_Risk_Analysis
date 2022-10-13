# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:

The purpose of this analysis is to predict credit risk by using the credit card credit dataset from LendingClub which is a peer-to-peer lending services company. We will conduct the oversampling and undersampling strategies by using the RandomOverSampler and SMOTE algorithms, and the ClusterCentroids algorithm techniques. Then, the combinatorial approach of over- and undersampling using the SMOTEENN algorithm will take place. Finally, we will predict the credit risk by comparing two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results:

### Naive Random Oversampling

<img width="797" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/107653012/195470273-8cb6068d-d551-4708-ba02-a4bb376989da.png">

° The naive accuracy score is 0.6447 meaning that this model accurately predicts credit risk 64.47% of the time.

° The precision of the high risk apllicants is 0.01 and 1.00 for low risk applicants.  meaning that 100% of the predicted low risk applicants are actually low risk, but only 1% of the predicted high risk applicants are actually high risk.

° According to recall 70% of high risk applicants are classified as high risk and 59% of low risk applicants are classified as low risk.

### SMOTE Oversampling

<img width="803" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/107653012/195471889-dad6a100-ba5f-4dc1-a036-8421f9c7a827.png">

° The SMOTE accuracy score is 0.6623 meaning that this model accurately predicts credit risk 66.23% of the time.

° The precision is exact the same as naive.

° The recall is 0.63 for high risk applicants and 0.69 for low risk applicants. Thus, 63% of high risk applicants are classified as high risk and 69% of low risk applicants are classified as low risk.

### Cluster Centroids Undersampling

<img width="796" alt="Screen Shot 2022-10-12 at 9 10 20 PM" src="https://user-images.githubusercontent.com/107653012/195475968-4b16a552-2ffd-4762-b500-8742cb456fc1.png">

° The accuracy score is 0.6531 meaning that this model accurately predicts credit risk 65.31% of the time.

° The precision is exact the same as both models above.

° The recall is 0.73 for high risk applicants and 0.57 for low risk applicants. Thus, 73% of high risk applicants are classified as high risk and 57% of low risk applicants are classified as low risk.

### SMOTEENN (Combination Sampling)

<img width="781" alt="Screen Shot 2022-10-12 at 9 33 51 PM" src="https://user-images.githubusercontent.com/107653012/195478480-71b59c92-a309-492b-b6d2-2f2eca71104e.png">


° The accuracy score is 0.6511 meaning that this model accurately predicts credit risk 65.11% of the time.

° The precision is still the same.

° The recall is 0.74 for high risk applicants and 0.56 for low risk applicants. Thus, 74% of high risk applicants are classified as high risk and 56% of low risk applicants are classified as low risk.

### Balanced Random Forest Classifier

<img width="774" alt="Screen Shot 2022-10-12 at 9 43 54 PM" src="https://user-images.githubusercontent.com/107653012/195479505-2ea6d72b-e449-4a17-8de8-d75bef33dc1f.png">

The accuracy score is 0.7620 meaning that this model accurately predicts credit risk 76.2% of the time. It is pretty high compared to the other models. 

° The precision of the high risk apllicants is 0.03 and 1.00 for low risk applicants. Thus, only 3% of the predicted high risk applicants are actually high risk.

° The recall is 0.63 for high risk applicants and 0.89 for low risk applicants. The highest recall for the low risk applicants compared to the previous models. 

### Easy Ensemble AdaBoost Classifier

<img width="777" alt="Screen Shot 2022-10-12 at 9 44 08 PM" src="https://user-images.githubusercontent.com/107653012/195479961-db37eb29-2b44-4511-92ed-39ef63d3be73.png">

° This model actually predicts the credit risk 91.78% of the time. 

° The precision for high_risk applicants is 0.09 meaning that this model identifies high risk applicants 9% of the time. 

° The recall shows that 89% of the high risk and 94% of the low risk applicants are correctly classified. 

## Summary:

In conclusion, the Easy Ensemble AdaBoost Classifier model is the best model to use for predicting credit risk since not only the accuracy score was the highest but also it can better identify high risk applicants. 
