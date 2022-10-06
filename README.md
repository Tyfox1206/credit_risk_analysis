# credit_risk_analysis

## Overview

this analysis is to understand how to use machine learning to make predictions usind different algorithms. This challenge was based on supercised learning. and used 5 difffernt algorithms to process the data.

## Results

### Naive Random Oversampling
![oversampling](https://github.com/Tyfox1206/credit_risk_analysis/blob/main/images/oversampling.PNG)

* Accuracy - 66%
* high risk - precision 0.01 recall .72
* low risk - precision 1 recall .60

### SMOTE Oversampling
![smote](https://github.com/Tyfox1206/credit_risk_analysis/blob/main/images/smote_oversampling.PNG)

* Accuracy - 66%
* high risk - precision 0.01 recall .62
* low risk - precision 1 recall .69

### Undersampling
![undersampling](https://github.com/Tyfox1206/credit_risk_analysis/blob/main/images/undersampling.PNG)

* Accuracy - 54%
* high risk - precision 0.01 recall .69
* low risk - precision 1 recall .40

### Combination (Over and Under) Sampling
![over-under](https://github.com/Tyfox1206/credit_risk_analysis/blob/main/images/under_over_sampling.PNG)

* Accuracy - 64%
* high risk - precision 0.01 recall .72
* low risk - precision 1 recall .57

### Balanced Random Forest Classifier
![ensemble](https://github.com/Tyfox1206/credit_risk_analysis/blob/main/images/ensemble.PNG)

* Accuracy - 79%
* high risk - precision .04 recall .67
* low risk - precision 1 recall .91

### Easy Ensemble AdaBoost Classifier
![easy-ensemble](https://github.com/Tyfox1206/credit_risk_analysis/blob/main/images/easy_ensemble.PNG)

* Accuracy - 93%
* high risk - precision 0.07 recall .91
* low risk - precision 1 recall .94

## Summary

the machine mearning model with the closest to 1 balanced accuracy is the best model to use and in this set it would be the Easy Ensemble AdaBoost Classifier. since it had an accuracy of 93% and all the rest had a accuracy of below 80%. the model that has a recall score closer to 1 is the ebst model to use. This means that the Easy Ensemble AdaBoost Classifier is the best choice on this criteria. so over all the model to use is the Easy Ensemble AdaBoost Classifier model. 
