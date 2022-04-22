# Credit_Risk_Analysis

## Overview of the analysis: 

* The purpose of this analysis was to use different machine learning techniques to assess credit card risk. Using data provided from the client, we oversampled and undersampled it using "RandomOverSampler", "SMOTE" and "ClusterCentroids" algorithms. Additionally, we over- and undersampling the same data using the "SMOTEENN"  algorithm. Lastly, we compared two models which are "BalancedRandomForestClassifier" and "EasyEnsembleClassifier" that would reduce bias in our results to predict credit risk.

## Results: 

* Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Balanced Accuracy Score:

* **Naive Random Oversampling** (RandomOverSampler)
    * 0.6821854112176693
* **SMOTE Oversampling** (SMOTE)
    * 0.6617843650101715
* **Undersampling** (ClusterCentroids)
    * 0.5103601371413837
* **Over and Under Sampling** (SMOTEENN)
    * 0.6218026195454673
#### Ensemble Learners
* BalancedRandomForestClassifier
    * 0.7623909988052127
* EasyEnsembleClassifier
    * 0.9316600714093861

## Summary: 

* Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
