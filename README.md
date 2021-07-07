# mycode_1

 dataset used - Fish market dataset

 link for the dataset - https://www.kaggle.com/aungpyaeap/fish-market

This dataset is a record of 7 common different fish species in fish market sales. With this dataset, a predictive model can be predicted using different machine learning algorithms and used to predict various features, here we have used this dataset to predict the species of the fish

model used - Logistic regression model

Accuracy of model - 89%

Libraries required : 

import pandas as pd  
import numpy as np 
%matplotlib inline
from scipy import stats
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.linear_model import LogisticRegression
from sklearn import metrics

Steps involved in the approach include :
1. Converting the dataset into dataframe
2. Checking the first few lines of dataframe
3. Seperating out each species so that we can see the outliers
4. Dropping the irrelevant columns and splitting the dataset into training and test dataset
5. Using and defining the logistic regression model
6. Predicting the species of the fish based on the model vs the actual species in the dataset

Author of dataset : Aung Pyae

