# Titanic-Exploratory-Data-Analysis-and-Prediction

Overview

This repository contains an exploration of the Titanic dataset along with machine learning predictions to determine passenger survival. The data is divided into two sets: the training set (train.csv) and the test set (test.csv). The training set includes the outcomes (0 = No, 1 = Yes) for each passenger, while the test set lacks this information. The goal is to build machine learning models using features such as gender and class to predict survival on the Titanic.

Dataset Description

Data Files

train.csv: The training set used to build machine learning models.

test.csv: The test set for evaluating the model's performance on unseen data.

gender_submission.csv: A sample set of predictions assuming that all and only female passengers survive.

Data Dictionary

survival: Survival (0 = No, 1 = Yes)

pclass: Ticket class (1 = 1st, 2 = 2nd, 3= 3rd)

sex: Gender

age: Age in years (fractional if less than 1)

sibsp: # of siblings / spouses aboard the Titanic

parch: # of parents / children aboard the Titanic

ticket: Ticket number

fare: Passenger fare

cabin: Cabin number

embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Variable Notes

pclass: A proxy for socio-economic status (SES)

1st = Upper

2nd = Middle

3rd = Lower

age: Age is fractional if less than 1, and estimated ages are in the form of xx.5

sibsp: Defines family relations

Sibling = brother, sister, stepbrother, stepsister

Spouse = husband, wife (mistresses and fiancés were ignored)

parch: Defines family relations

Parent = mother, father

Child = daughter, son, stepdaughter, stepson

Some children traveled only with a nanny, so parch=0 for them.

Usage

The provided Jupyter notebooks and Python scripts explore the dataset, perform data analysis, and build machine learning models for predicting Titanic passenger survival.
