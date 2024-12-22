# Singapore-Resale-Flat-Prices-Predicting

# Introduction:
The objective of this project is to develop a machine learning model and deploy it as a user-friendly web application that predicts the resale prices of flats in Singapore. This predictive model will be based on historical data of resale flat transactions, and it aims to assist both potential buyers and sellers in estimating the resale value of a flat.

# Technologies used:
Data Collection, Data Wrangling, Data Preprocessing, EDA, Model Building, Model Deployment.

# Import Libraries:
import streamlit as st </br>
import pandas as pd </br>
import numpy as np </br>
from sklearn.tree import DecisionTreeRegressor</br>
import joblib

# Work flow of the Project:
Download the dataset from the link https://beta.data.gov.sg/collections/189/view</br>
Totally there are 5 datasets ranging from 1990 to 2020</br>
Download the complete datasets, did data wrangling and append it to a one dataset</br>
Data preprocessing steps includes fill null values, datatype conversion, outliers detection etc.,</br>
Find skewness using KDE plot and default skew method</br>
Created additional four features based on the datasets</br>
Visualizations done for categorical and continuous variables</br>
Visualizations like bar chart, count plot, density plot, box plot, line plot</br>
Label encoding was used to encode categorical variables</br>
Highly correlated features with target variables was calculated using correlation matrix and heat map</br>
Split the dataset into train and test set for model building</br>
Used Linear regression and Decision tree regression for model building</br>
Coefficient of determination for Linear regression is 0.95 and that for Decisiontree regression is 0.99</br>
Decision Tree was used to build predictive modelling</br>
Using pickling and joblib , pickle the model for further usage</br>
Created a simple UI for the users to set the values for predicting resale flat price in Singapore</br>
Price per square meter, Flat type, Floor area square meter are the few features highly impacting the resale price</br>
Successfully deployed the predictive modelling in Render platform, to use this predictive modelling as a web application.
Thank you All!
