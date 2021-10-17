# Credit_Risk_Analysis

# Resources
1. Data Source: LoanStats_2019Q1.csv
2. Software: Jupyter Notebook, Python

# Purpose:

# Deliverable 1: Use Resampling Models to Predict Credit Risk
Using the imbalanced-learn and scikit-learn libraries, we’ll evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, we’ll use the oversampling RandomOverSampler and SMOTE algorithms, and then we’ll use the undersampling ClusterCentroids algorithm. Using these algorithms, we’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

# Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
Using the imbalanced-learn and scikit-learn libraries, we’ll use a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. Using the SMOTEENN algorithm, we’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

# Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
Using the imblearn.ensemble library, we’ll train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using both algorithms, we’ll resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

# Summary:
In the first four models we undersampled, oversampled and did a combination of both to try and determine which model is best at predicting which loans are the highest risk. The next two models we resampled the data using ensemble classifiers to try and predict which which loans are high or low risk. In our first four models our accuracy score is not as high as the ensemble classifiers and the recall in the oversampling/undersampling/mixed models is low as well. Typically in your models you want a good balance of recall and precision which is why I recommend the ensemble classifiers over the first four models. It appears that the Easy Ensemble had the best balance of all the models because of it's high accuracy score and good balance of precision and recall scores.

# Overview:
This project takes on the challenge of assessing credit risk by using machine learning algorithms on the LoanStats_2019Q1.csv data to determine whether individuals are at low or high risk for loans. For this project, these are the following machine learning models/algorithms used to predict credit risk:

Deliverable 1: Resampling
Deliverable 2: SMOTEENN Algorithm
Deliverable 3: Ensemble Classifiers
To determine which is the most accurate model at predicting which loans are a high risk the data will be undersampled, oversampled and a combination of both.
