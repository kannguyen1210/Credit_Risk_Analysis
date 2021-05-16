# Credit_Risk_Analysis

# Project Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Finally, I’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results

## Naive Random Oversampling
![alt text](/images/Naive_Random_Oversampling.png)

## SMOTE Oversampling
![alt text](/images/SMOTE_Oversampling.png)

## Undersampling
![alt text](/images/Undersampling.png)

## SMOTEENN Sampling
![alt text](/images/SMOTEENN_Sampling.png)

## Random Forest Ensemble
![alt text](/images/Random_Forest.png)

## Easy Ensemble
![alt text](/images/EasyEnsemble.png)

# Summary
Based on the results above, we can see that among the 6 models, we can see that the Easy Ensemble model yielded the best results in term of accuracy score, precisions, recall and F1 score. Although all the model have the low_risk precision very high, it is misleading because the number of low risk records are extremely high compare to the low risk records. Therefore, taking into consideration recall and F1 Score, the Random Forest and Easy Ensemble have the best metrics here. 

Finally, looking at the precision of 0.88 and 0.9 F1 Score of 0.94 vs 0.95 between Random Forest and Easy Ensemble respectively, we can conclude that the Easy Ensemble would yield the best result for Credit Risk Analysis.
