# Credit Risk Analysis Report

## Project Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, there is a need to employ different techniques to train and evaluate models with unbalanced classes. Imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling will be tried to address the issue.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, oversampling of the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm will be used. Then, the use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm will be tested. Next, a comparison between the two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk will be performed. Lastly, an evaluation of the performance of these models and the preperation of a written recommendation on whether they should be used to predict credit risk will stated.

---

## Results

Resampling Summary Table:
|Screenshot|ML Name|Disscusion|
|----------|-------|----------|
|![Capture 184](https://user-images.githubusercontent.com/59425631/138581068-3d695f79-7971-4d4e-b410-2b03a7014694.PNG) -![Capture 185](https://user-images.githubusercontent.com/59425631/138581195-254735d1-670d-4091-a1dc-235d1d2a4338.PNG) -![Capture 186](https://user-images.githubusercontent.com/59425631/138581199-3451b18b-cc8c-4839-bdb0-cb377f800df9.PNG) -![Capture 187](https://user-images.githubusercontent.com/59425631/138581187-39bb6005-53fe-4508-9b2b-f851e65399e3.PNG)|Naive Random Oversampling, SMOTE Oversampling, Undersampling, Combination (Over and Under) Sampling, respectively |The accurecy score is low to average. Regarding the the precession and sensitivity, they are bad for the high risk borrowers, and high for the low risk borrwers| 

Ensemble Summary Table:
|Screenshot|ML Name|Disscusion|
|----------|-------|----------|
|![Capture 188](https://user-images.githubusercontent.com/59425631/138581261-5fa2bae1-4fa9-40a4-ad7b-0c10cfc467d1.PNG) -![Capture 188](https://user-images.githubusercontent.com/59425631/138581268-806eca88-3ef4-449d-98c7-11a2b78fefe1.PNG)|-Balanced Random Forest Classifier, Easy Ensemble AdaBoost Classifier, respectively|The accurecy score is average to high. Regarding the the precession and sensitivity, they are bad for the high risk borrowers, and high for the low risk borrwers|

---

## Summary

In summary:

- The performance of all  resampling machine learning models is similar and leads to almost the same results. 
- Ensemble machine learnign models outperformed resamling models in terms of higher accuracy, and higher recall and percession values for the class of high risk borrowers. 
- The developed models are not recommended to be used as they don't high percession in identifying the high risk loans. 
