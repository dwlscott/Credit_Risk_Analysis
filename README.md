# Credit_Risk_Analysis
Module 17 Machine Learning 
## Overview of analysis

The assignment is to analyze credit card risk. Here we are tasked with taking our knowledge of supervised learning and applying it. Since credit card risk is basically an unbalanced classification problem. We are going to use the different techniques to train and evaluate the models. 

For this entire assignment we are going to be using two libraries evaluated imbalanced-learn and scikit-learn as a basis of our analysis. Since we were given a data set to work with. The data is going to be oversampled with RandomdomOverSampler, SMOTE, then ClusterCentroids. Followed by SMOTEEN which is a combination approach for part one of the assignment. Then for part two, we are then going to compare two machine learning models, BalancedRandomForestClassifier and EasyEnsembleClassifier to reduce bias and predict one's risk. 


## Results:

Random over sampling had an accuracy score of 64%, precision was 0.99, recall was 0.68 and the F1 was 0.80

<img width="583" alt="Random_over_sampling " src="https://user-images.githubusercontent.com/102453818/180616892-a60ebd5f-b8d0-4e6f-a29c-e76390dee956.png">

SMOTE accuracy score was 66%, precision was 0.99, and the recall was 0.69, and the F1 was 0.81

<img width="548" alt="SMOTE" src="https://user-images.githubusercontent.com/102453818/186325332-7208a112-404d-4b6f-a7be-c44e9ec9d77d.png">


ClusterCentroids undersampling had an accuracy score of 54% precision was 0.99 the recall was 0.40 and the F1 0.56

<img width="564" alt="Undersampling " src="https://user-images.githubusercontent.com/102453818/186325352-34483b70-bf10-4f4f-84df-f750da0e6282.png">


SMOTEE had a accuracy score of 64%, a precision score of 0.99, and the recall was 0.58 and the F1 score was 0.71

<img width="724" alt="Screen Shot 2022-08-23 at 21 55 22" src="https://user-images.githubusercontent.com/102453818/186325438-bccffb2f-03a9-44e2-8392-587cbcdc8921.png">


Balanced Random Forest Classifier had an accuracy score of of 78% with and precision score of 0.99, a recall score of 0.87, and a F1 score of 0.93

<img width="614" alt="Balanced Random forrest " src="https://user-images.githubusercontent.com/102453818/180616939-b8a711a9-f282-4451-b27a-a88f71a5e1d4.png">

Easy Ensemble AdaBoost Classifier had An accuracy score of 99% a precision score of 0.99, a recall score of 0.94 and an F1 score of 0.97

<img width="627" alt="AdaBoostClassifer" src="https://user-images.githubusercontent.com/102453818/180616963-fc1a2790-8857-477a-8c7b-d8abba1dacc1.png">

## Summary: 
Due to some technical issue. The code to run deliverable three, Balanced Random forest and Easy Ensemble are correct, however, it will not run. The provided analysis is based on the given data for the module challenge. That being said, out of all the machine learning models, the Easy Ensemble model is going to be the best predictor of credit card risk. It had a really good success rate of 99% accuracy, and a F1 score of 0.97. Now the worst model for prediction risk was ClusterCentroids undersampling. It had the worst accuracy score of 54% and an F1 score 0.73
