# Credit Risk Analysis
## Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. In this project, I use different techniques to train and evaluate models with unbalanced classes. 

## Resources
Dataset: [LendingClub](https://www.lendingclub.com/)
<br> Libraries:
- [imbalanced-learn](https://imbalanced-learn.org/stable/) 0.9.1
- [scikit-learn](https://scikit-learn.org/stable/) 1.1.2

## Results
### Model 1: RandomOverSampler ![]()
  - Balanced Accuracy: 65%
  - Precision:
  - Recall: 
### Model 2: SMOTE![]()
  - Balanced Accuracy: 62%
  - Precision:
  - Recall: 
### Model 3: Undersampling ![]()
  - Balanced Accuracy: 62%
  - Precision:
  - Recall: 
### Model 4: Combination Over & Under Sampling ![]()
  - Balanced Accuracy: 51%
  - Precision:
  - Recall: 
### Model 5: BalancedRandomForestClassifier ![]()
  - Balanced Accuracy: 79%
  - Precision:
  - Recall: 
### Model 6: EasyEnsembleClassifier![]()
  - Balanced Accuracy: 79%
  - Precision:
  - Recall: 

## Summary
Based on accuracy rating (the number of times the ML model was correct overall), the best performing model was The EasyEnsembleClassifier.


Precision tells us how good the model is at predicting a specific category, in this case, high-risk loans. 

Recall tells us how many times the model was able to detect a specific category. 
I would recommendation banks use the [X] model.
