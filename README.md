# Credit_Risk_Analysis
Supervised Machine Learning

## Project Overview
Using the credit card credit dataset from LendingClub (provided), a peer-to-peer lending services company, We oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, using a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, are compared to predict credit risk. Once finished, the performance of these models are evaluated followed by a written recommendation on whether they should be used to predict credit risk.



## Results
The purpose of this project was to demonstrate understanding of various machine learning methods and interpreting the results of the study. 
The following machine learning methods were used:
* Oversampling (Naive Random Sampling & SMOTE Oversampling)
* Undersampling (using ClusterCentroids resampler)
* Combination (Over and Under Sampling, using SMOTEENN)
* Ensemble Learners (Balanced Random Forest Classifier & Easy Ensemble AdaBoost Classifier)

The dataset was first split into testing and training sets and the values were encoded using the get_dummies() method in pandas.

The classification report generated was used to compare the performance of the algorithms.

* Oversampling: Naive Random Sampling

* Oversampling: SMOTE Oversampling

* Undersampling: CluserCentroids 

* Combination Over & Under Sampling: SMOTEENN

* Ensemble Learners: Balanced Random Forest Classifier

* Ensemble Learners: Easy Ensemble AdaBoost Classifier

## Summary
