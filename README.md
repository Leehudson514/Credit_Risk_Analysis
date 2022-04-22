# Credit_Risk_Analysis

## Overview of the analysis: 

* The purpose of this analysis was to use different machine learning techniques to assess credit card risk. 
* Using data provided from the client, we oversampled and undersampled it using "RandomOverSampler", "SMOTE" and "ClusterCentroids" algorithms. Additionally, we over- and undersampling the same data using the "SMOTEENN"  algorithm. Lastly, we compared two models which are "BalancedRandomForestClassifier" and "EasyEnsembleClassifier" that would reduce bias in our results to predict credit risk.

## Results: 
### Balanced Accuracy Score:

* **Naive Random Oversampling** (RandomOverSampler)
    * 0.6821854112176693
       * 68% BAS
       * 99% percision for low risk credit
       * 1% percision for high risk credit

![goals](https://github.com/Leehudson514/Credit_Risk_Analysis/blob/main/Resources/RandomOverSampler.png)

* **SMOTE Oversampling** (SMOTE)
    * 0.6617843650101715 
       * 66% BAS
       * 99% percision for low risk credit
       * 1% percision for high risk credit

![goals](https://github.com/Leehudson514/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)

* **Undersampling** (ClusterCentroids)
    * 0.5103601371413837
       * 51% BAS
       * 99% percision for low risk credit
       * 1% percision for high risk credit

![goals](https://github.com/Leehudson514/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.png)

* **Over and Under Sampling** (SMOTEENN)
    * 0.6218026195454673
       * 62% BAS
       * 99% percision for low risk credit
       * 1% percision for high risk credit 

![goals](https://github.com/Leehudson514/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.png)

#### Ensemble Learners
* **BalancedRandomForestClassifier**
    * 0.7623909988052127
       * 76% BAS
       * 100% percision for low risk credit
       * 3% percision for high risk credit
       
![goals](https://github.com/Leehudson514/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifier.png)

* **EasyEnsembleClassifier**
    * 0.9316600714093861
       * 93% BAS
       * 100% percision for low risk credit
       * 9% percision for high risk credit
       
![goals](https://github.com/Leehudson514/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleClassifier.png)

## Summary: 

* After performing multiple test with differebt models, we can see from the results that the ensemble learner techniques are the most reliable for predicting credit risk especially the easy ensemble classifier which had the highest accuracy score overall. Overall, the resampling techniques of RandomOverSampler, SMOTE, ClusterCentroids and SMOTEENN had far worse balanced accuracy score than the ensemble learner models and should not be considered to predict credit risk.
* My recommendation would be to use the easy ensemble classifier model to predict credit risk because of its high accuracy and precision score that was superior to the other sampling techniques.
