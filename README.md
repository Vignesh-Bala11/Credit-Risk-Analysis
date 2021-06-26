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

![Naive-Random-OS](https://user-images.githubusercontent.com/57723459/123528573-4e3dd880-d6b6-11eb-8856-e6ed8a04a07b.png)


## SMOTE Oversampling
- Accuracy: 68.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Rish: 70%
- Recall Low Risk: 66%

![SMOTE-OS](https://user-images.githubusercontent.com/57723459/123528577-539b2300-d6b6-11eb-8fe0-b7cb14032921.png)


## Cluster Centroid Undersampling 
- Accuracy: 51.1%
- Precision High Risk: 0%
- Precision Low Risk: 100%
- Recall High Rish: 58%
- Recall Low Risk: 44%

![UnderSampling](https://user-images.githubusercontent.com/57723459/123528579-572eaa00-d6b6-11eb-8dee-de6ea54b3c01.png)


## SMOTEENN Sampling 
- Accuracy: 68.1%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Rish: 76%
- Recall Low Risk: 60%

![SMOTEEN](https://user-images.githubusercontent.com/57723459/123528581-5a299a80-d6b6-11eb-9beb-803a4c8b3d38.png)


## Balanced Random Forest Classifying 
- Accuracy: 64.8%
- Precision High Risk: 56%
- Precision Low Risk: 100%
- Recall High Rish: 30%
- Recall Low Risk: 100%

![RandomForest](https://user-images.githubusercontent.com/57723459/123528584-5e55b800-d6b6-11eb-82db-f86c1b2be369.png)


## Easy Ensemble Classifying 
- Accuracy: 92.3%
- Precision High Risk: 6%
- Precision Low Risk: 100%
- Recall High Rish: 91%
- Recall Low Risk: 94%

![EasyEnsemble](https://user-images.githubusercontent.com/57723459/123528585-61e93f00-d6b6-11eb-9496-5ab1ad1f4c82.png)


## Summary 
In order to determine if loan is high risk or not, we need a model that lets the least amount of high risk loans pass undected. This pass through is represented via the recall metric .The models that had the highest recall for high risk are the Easy Ensemble Classifier, SMOTEENN Sampling Model and the Naive random oversaampling model. The other metric to take into account is the recall for low risk as this shows the amount of low risk laons that are flagged as as high risk. The models that had the best recall low risk scores are the Easy Ensemble Classifier and the Random Forest Classifier. The final metric to take into account is the accuracy score of the model as it depicts how well the model performs generally. The models that had the highest accuracy score are the Easy Ensemble Classifier, The SMOTEENN Sampling Model and the Random Forest Classifier.

Taking into account all the factors, the model I would recommend to flag credit risks is the Easy Ensemble Classifier 

