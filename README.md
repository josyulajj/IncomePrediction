# IncomePrediction

## Define the ML model objective
The main objective is to build a binary classification model that predicts the target income for individuals based on the given census data. Given the small sample size, we use the k-fold cross-validation method in Autopilot to help us improve model scoring metrics. Additionally, we use the model explainability report generated through the Autopilot job to help us understand how each feature in the dataset contributes to the model outcome.

## Public census data
For this experiment, we use the public census data (Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science) for training and validation data. The prediction task is to determine whether a person makes over $50,000 a year.

This dataset contains 14 features that cover the diversity of demographic characteristics, with 45,222 rows (32,561 for training and 12,661 for testing). The following is a summary of the features and target labels:

* Age – Age of the participant
* Workclass – Type of working class
* Fnlwgt – Number of people the census takers believe that observation represents
* Education – Education levels
* Education-num – Years of education
* Marital-status – Marital status
* Occupation – Occupation
* Relationship – Relationship
* Ethnic group – The ethnic group of the participant
* Sex – Gender
* Capital-gain – Capital gain
* Capital-loss – Capital loss
* Hours-per-week – Work hours per week
* Country – Country of origin
* Target – <=$50,000, >$50,000

## AWS SageMaker AutoPilot Screencaptures

