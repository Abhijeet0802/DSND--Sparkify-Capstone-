# DSND--Sparkify-Capstone-
This is for Udacity's Data Scientist Nanodegree Capstone project.

Table of Contents
Installation
Project Details
Files
Results

Installation
This project uses the following software and Python libraries:
Python
Spark
Pyspark (Both SQL and ML)
Pandas
Numpy
Matplotlib
Seaborn
SkLearn

Project Details
The objective of the project is to predict user or customer churn for a fictional music streaming app - "Sparkify".
Definition of Churn - 
A user is said to have churned if there is an event “Cancellation Confirmation” is present in one of the sessions page for a given userId.

Files
Sprakify.ipynb is the main notebook for the project and contains all the codes starting from importing libraries to data analysis, EDA, feature generation, modeling, hyper parameter tuning, model performance evaluation to improvements and final conclusion.

Result
As part of the modeling exercise we implemented 5 models: Logistic Regression, Decision Trees, RandomForest, GBT and Linear SVM and utilized model evaluation metrics — Accuracy and F1 Score to identify the best model from the 5.
The best model based on the evaluation came out to be the Logistic Regression model. On which, we used cross validation and grid search to refine the model.
The best model had an Accuracy of 0.78 and F1 score of 0.76.
The top 5 important features predicting the likelihood of a user to churn are:
No. of Days since Registration
No. of Thumbs Down or Dislikes
Maximum Session Time
No. of Songs added to the Playlist
Total Listening Time
