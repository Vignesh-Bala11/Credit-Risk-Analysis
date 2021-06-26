# Credit-Risk-Analysis

## Overview
Given a dataset to asses credit card risk, our goal was to determine which superivsed machine-learning model would provide the assessment in determining credit card risk

## Results 

## Naive Random Oversampling:
- Accuracy: 67.4%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Rish: 66%
- Recall Low Risk: 69%

## SMOTE Oversampling
- Accuracy: 68.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Rish: 70%
- Recall Low Risk: 66%

## Cluster Centroid Undersampling 
- Accuracy: 51.1%
- Precision High Risk: 0%
- Precision Low Risk: 100%
- Recall High Rish: 58%
- Recall Low Risk: 44%

## SMOTEENN Sampling 
- Accuracy: 68.1%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Rish: 76%
- Recall Low Risk: 60%

## Balanced Random Forest Classifying 
- Accuracy: 64.8%
- Precision High Risk: 56%
- Precision Low Risk: 100%
- Recall High Rish: 30%
- Recall Low Risk: 100%

## Easy Ensemble Classifying 
- Accuracy: 92.3%
- Precision High Risk: 6%
- Precision Low Risk: 100%
- Recall High Rish: 91%
- Recall Low Risk: 94%

## Summary 
In order to determine if loan is high risk or not, we need a model that lets the least amount of high risk loans pass undected. This pass through is represented via the recall metric .The models that had the highest recall for high risk are the Easy Ensemble Classifier, SMOTEENN Sampling Model and the Naive random oversaampling model. The other metric to take into account is the recall for low risk as this shows the amount of low risk laons that are flagged as as high risk. The models that had the best recall low risk scores are the Easy Ensemble Classifier and the Random Forest Classifier. The final metric to take into account is the accuracy score of the model as it depicts how well the model performs generally. The models that had the highest accuracy score are the Easy Ensemble Classifier, The SMOTEENN Sampling Model and the Random Forest Classifier.

Taking into account all the factors, the model I would recommend to flag credit risks is the Easy Ensemble Classifier 

