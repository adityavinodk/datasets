# Titanic Problem
The chosen dataset is the Titanic Survival Prediction Dataset - https://www.kaggle.com/c/titanic to predict the survival of different passengers based on details like Fare, Gender, Age, Passenger Class etc.
Here the a Binary Prediction is done of whether the Passenger Survived - 1 for YES, 0 for NO. 
The folder consists of the training data in train.csv and testing data in test.csv
The Prediction is done in the jupyter file prediction.ipynb and the predictions are stored in the predictions.csv

1. In the Jupyter file, first data pre-processing is done to handle null values, and fill up the missing data. 
2. Then the data is converted into integer form by mapping the non-integer data into different integer classes. 
3. We also divide the traning data into 2 classes for cross-validation as well. 
4. Then different machine learning models from sklearn library are run and we compare the scores of the different models to find the optimum classifier.