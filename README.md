# Module-17-Credit_Risk_Analysis

## Overview
The purpose of the analysis is to use different techniques (such as RandomOverSampler, SMOTE, and ClusterCentroids for undersampling) and two machine learning models (BalancedRandomClassfier and EasyEnsembleClassifier) that reduce bias to predict credit risk for loans.

## Results

### RandomOverSampling
![Image](https://github.com/cstern28/Module-17-Credit_Risk_Analysis/blob/main/Screenshots/Random_Oversampling.png)

### SMOTE Oversampling
![Image](https://github.com/cstern28/Module-17-Credit_Risk_Analysis/blob/main/Screenshots/SMOTE_Oversampling.png)

### Undersampling
![Image](https://github.com/cstern28/Module-17-Credit_Risk_Analysis/blob/main/Screenshots/Undersampling.png)

### SMOTEENN (Over & Under) Sampling
![Image](https://github.com/cstern28/Module-17-Credit_Risk_Analysis/blob/main/Screenshots/SMOTEENN_OverandUnderSampling.png)

### Balanced Random Forest Classifier
![Image](https://github.com/cstern28/Module-17-Credit_Risk_Analysis/blob/main/Screenshots/Balanced_Random_Forest_Classifier.png)

### Features Sorted
![Image](https://github.com/cstern28/Module-17-Credit_Risk_Analysis/blob/main/Screenshots/Features_Sorted.png)

This shows the features sorted in descending order by which factors are most important to the model.

### Easy Ensemble Classifier
![Image](https://github.com/cstern28/Module-17-Credit_Risk_Analysis/blob/main/Screenshots/Easy_Ensembler_Classifier.png)

## Summary
The results show the following Accuracy Score (A), Precision (P), and Recall (R) for each model. High (H) Low (L)
1. RandomOverSampling 
  - A: 62.5%
  - P: H: 1%  L: 100%
  - R: H: 60% L: 65%
2. SMOTE Oversampling
  - A: 65.1%
  - P: H: 1%  L: 100%
  - R: H: 64% L: 66%
3. Undersampling
  - A: 52.9%
  - P: H: 1%  L: 100%
  - R: H: 61% L: 45%
4. SMOTEENN (Over & Under) Sampling
  - A: 63.8%
  - P: H: 1%  L: 100%
  - R: H: 70% L: 57%
5. Balanced Random Forest Classifier
  - A: 78.7%
  - P: H: 4%  L: 100%
  - R: H: 67% L: 91%
6. Easy Ensemble Classifier
  - A: 92.5% 
  - P: H: 7%  L: 100%
  - R: H: 91% L: 94%
  
## Conclusion
Based on the results, the most accurate model is using Easy Ensemble Classifier, with balanced accuracy score of 92.5% (meaning ratio of the total number of correct predictions and the total number of predictions), precision of 7% meaning of all the loans with high risk, 7% of the loan population were classfied correctly as high risk and almost 100% of low risk loans were classified correctly, and recall was 91% (high), meaning all high risk loans were 91% correct in identifying true positives and 94% correct in identifying true low risk loans.



