#Project - Capstone
#Predicting Customer Churn using Pyspark : Sparkify

# Table of Contents:

1)Dependencies

2)Project Motivation

3)Files Description

4)Results

5)Acknowledgements


# Dependencies:
Below listed libraries are needed to implement this project:

1)Python
2)Pandas
3)Matplotlib
4)Seaborn
5)PySpark
6)Spark
7)Numpy


# Project Motivation:
This project is a part of the Udacity's Data Scientist Nanodegree program analyzing the behaviour of users for an app called Sparkify 
to predict user churn. Sparkify is an app similar to Spotify and the dataset contains user behaviour log for the past few months. 
It contains some basic information about the users as well as information about a particular action they have taken. 
A user can have multiple actions which leads to multiple entries for a user, we can identify when a user churned through the action 
of account cancellation.

# Files Description:
Sparkify.ipynb is the main notebook where end to end Model implementation to predict customer churn is done.

# Results:
We used three different Machine Learning algorithms on the dataset which are Random Forest, Logistic Regression and Gradient Boosted Trees to train the model for customer churn respectively. We compared the performance between the three models and observed that 
Random Forest outperformed the rest two algorithms. The metric we used to evaluate performance is F-1 Score as that gives us a better representation of the model performance on a small dataset as well.

The final metrics for our Random Forest Classifier are as follows:

A)The F-1 Score is 0.836

B) The accuracy is 0.812


# Acknowledgements
Must give credit to Udacity for this project. 
