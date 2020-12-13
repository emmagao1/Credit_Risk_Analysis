# Credit_Risk_Analysis

## Overview

Purpose of the analysis is to employ different techniques to train and evaluate models with unbalanced classification and to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

The data is from credit card credit dataset from LendingClub, a peer-to-peer lending services company. We have oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Then, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Results

1. Naive Random Oversampling

Naive random oversampling has a avg. 0.63 accuracy, f1 of 0.81, precision of 0.99 and a recall score of 0.68.

![Native Random Oversampling](https://github.com/emmagao1/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling.PNG)

2. SMOTE Oversampling

SMOTE oversampling has a avg. 0.65 accuracy, f1 of 0.77, precision of 0.99 and a recall score of 0.63.

![SMOTE Oversampling](https://github.com/emmagao1/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling.PNG)


3. Undersampling

Undersampling has a avg. 0.50 accuracy, f1 of 0.58, precision of 0.99 and a recall score of 0.41.

![Undersampling](https://github.com/emmagao1/Credit_Risk_Analysis/blob/main/Images/Undersampling.PNG)

4. Oversampling and Undersampling

Combination sampling has a avg. 0.63 accuracy, f1 of 0.73, precision of 0.99 and a recall score of 0.57.

![Combination sampling](https://github.com/emmagao1/Credit_Risk_Analysis/blob/main/Images/Combination%20sampling.PNG)

5. Balanced Random Forest

Balanced Random Forest has a avg. 0.78 accuracy, f1 of 0.95, precision of 0.99 and a recall score of 0.91.

![Balanced sampling](https://github.com/emmagao1/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest%20Classifier.PNG)

6. Easy Ensemble Classifier

Easy Ensemble Classifier has a avg. 0.93 accuracy, f1 of 0.97, precision of 0.99 and a recall score of 0.94.

![Easy sampling](https://github.com/emmagao1/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost%20Classifier.PNG)



## Summary

In conclusion, 6 machine learning models are good with predicting risks with varying degress of accuracy and efficiency. Overall, seems like Easy Ensemble Classifier has the highes accuracy, f1, precision and recall scores.
