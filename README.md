# Credit-Card-Fraud-Detection
Introduction

The objective in this project is to build machine learning models to classify or identify fraudulent card transactions from a given card transactions data.

Data Description

The dataset contains two-days credit card transactions made in September 2013 by European cardholders. The dataset is highly unbalanced with a low percentage of fraudulent transactions within several records of normal transactions. The positive class (frauds) account for 0.172% (492 frauds out of 284,807 transactions) of all transactions.
Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. Feature 'Class' is the target variable with value 1 in case of fraud and 0 otherwise


During model building I covered almost all data science concepts such as data load and cleaning, feature scaling,modelling  etc

Algorithm implemented :

ISOLATION FOREST :Isolation Forest is an unsupervised anomaly detection algorithm that uses the two properties “Few” and “Different” of anomalies to detect their existence. Since anomalies are few and different, they are more susceptible to isolation
Local Outlier Factor :The Local Outlier Factor (LOF) algorithm is an unsupervised anomaly detection method which computes the local density deviation of a given data point with respect to its neighbors.

Naive Bayes

Technology and tools wise this project covers,

Python
Numpy and Pandas for data cleaning
Matplotlib for data visualization
Sklearn for model building
Jupyter notebook, visual studio code

