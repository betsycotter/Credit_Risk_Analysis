# Credit Risk Analysis

## Overview

Fast Lending has asked for our help in using Machine Learning to determine credit risk for their potential borrowers. This peer-to-peer lending company would like to predict outcomes for a quicker and more reliable lending experience. We will help them determine the best machine learning model to use to more accurately decide on loan approvals, ideally leading to fewer loans going into default. Overall, they would like to have a great experience for all of their customers. 

## Results

We have tried six different machine learning models. Below are the results for accuracy, precision, and recall scores for each model: 

Accuracy scores: 
- RandomOverSampler: 0.646

![RandomOverSampler_accuracy](https://user-images.githubusercontent.com/116031639/222334871-8d8bf766-46bd-4ed1-8653-18050159a46b.png)

- SMOTE: 0.623

![SMOTE_accuracy](https://user-images.githubusercontent.com/116031639/222334947-4540f04f-9504-4bb7-9d1e-d0a911a9d8ac.png)

- ClusterCentroids: 0.517

![ClusterCentroids_accuracy](https://user-images.githubusercontent.com/116031639/222334993-762b6db7-f2ec-4cbc-93a8-04908deabb56.png)

- SMOTEENN: 0.640

![SMOTEENN_accuracy](https://user-images.githubusercontent.com/116031639/222335009-7fb3339a-be4b-4cae-af34-a350f77bd801.png)

- BalancedRandomForestClassifier: 0.788

![BalancedRandomForestClassifier_accuracy](https://user-images.githubusercontent.com/116031639/222335031-4c867949-12b3-463e-a1c6-7f0916791174.png)

- EasyEnsembleClassifier: 0.925

![EasyEnsembleClassifier_accuracy](https://user-images.githubusercontent.com/116031639/222335058-a310eefb-4182-472c-aaac-0ed88809e7e2.png)

Precision and recall scores: 
- RandomOverSampler: 

![RandomOverSampler_classification](https://user-images.githubusercontent.com/116031639/222335285-56407dc8-ff92-4241-8d6d-62169f819c52.png)

- SMOTE: 

![SMOTE_classification](https://user-images.githubusercontent.com/116031639/222335302-a2ccf470-6755-4465-80f4-f776af5707bf.png)

- ClusterCentroids: 

![ClusterCentroids_classification](https://user-images.githubusercontent.com/116031639/222335314-27896ce5-b94b-4678-8dea-977eaab56c2d.png)

- SMOTEENN: 

![SMOTEENN_classification](https://user-images.githubusercontent.com/116031639/222335350-fe5f71e4-7843-46da-8403-87eb5972500f.png)

- BalancedRandomForestClassifier: 

![BalancedRandomForestClassifier_classification](https://user-images.githubusercontent.com/116031639/222335362-9608f624-44bd-4277-9ae2-b0d5b8768d1b.png)

- EasyEnsembleClassifier: 

![EasyEnsembleClassifier_classification](https://user-images.githubusercontent.com/116031639/222335381-e6e2c978-1dec-4ecb-8707-d5f02ae46cdd.png)

## Summary

From the information above, we see that the EasyEnsembleClassifier model has the best accuracy score. In general, this is a good result for this model, however it can indicate that the model might be overfitting. 

Regarding the precision and recall scores, the EasyEnsembleClassifier model delivered the best results. Typically, precision and recall scores are important for assessing credit risk. With these models, the low risk precision was all at 100%, so we needed to look further into the results. The EasyEnsembleClassifier model also had the highest recall scores, as well. As a result, we would likely recommend this model to Fast Lending. 

Because this is a peer-to-peer lending service, we would like to encourage future lending. While potential borrowers that have been rejected from receiving a loan may be disappointed, we need the lenders to be satisfied with their experience, as well. With that being said, it is likely better to ensure that loans are repaid to the lenders to maintain our reputation as a reputable lending establishment. 
