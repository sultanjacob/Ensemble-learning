# Ensemble Learning with Iris Dataset
This project demonstrates the implementation of Ensemble Learning techniques—specifically Bagging and Boosting—using the classic Iris dataset. It utilizes Python and the scikit-learn library to show how combining multiple models can improve predictive performance. 


# Project Overview
The goal of this project is to implement and compare two fundamental ensemble algorithms:


Bagging (Bootstrap Aggregating): Uses multiple Decision Trees trained on different subsets of data to reduce overfitting. 


Boosting (AdaBoost): Sequentially trains weak learners (decision stumps) to correct the errors of previous models. 

# Key Features
Data Preprocessing:

Loads the Iris dataset (features and target labels). 

Splits the data into training (80%) and testing (20%) sets to ensure valid evaluation. 

Bagging Implementation:


Base Model: Decision Tree Classifier. 


Ensemble: BaggingClassifier with 10 estimators (trees). 

Boosting Implementation:


Base Model: Decision Tree Stump (max_depth=1). 


Ensemble: AdaBoostClassifier with 50 estimators and a learning rate of 1.0. 

Evaluation:

Calculates and prints the Accuracy Score for both models using the test data. 


Prerequisites
To run this notebook, you need Python installed with the following library:


scikit-learn 


You can install it via pip:

Bash

pip install scikit-learn
# How to Run
Open ensemble learning.ipynb in Jupyter Notebook or JupyterLab.

Run the cells sequentially to:

Load and split the data. 

Train the Bagging model and view its accuracy. 


Train the AdaBoost model and view its accuracy. 

# Results
The notebook outputs the accuracy metrics for both classifiers, providing a direct comparison of how Bagging and Boosting perform on the same dataset.
