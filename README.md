# Credit Risk Analysis Report

## Project Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, there is a need to employ different techniques to train and evaluate models with unbalanced classes. Imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling will be tried to address the issue.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, oversampling of the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm will be used. Then, the use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm will be tested. Next, a comparison between the two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk will be performed. Lastly, an evaluation of the performance of these models and the preperation of a written recommendation on whether they should be used to predict credit risk will stated.

