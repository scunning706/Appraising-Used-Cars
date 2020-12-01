# Appraising-Used-Cars
Machine Learning: A New Used Car Salesman
This repository contains all of the steps in the analysis and model building for a used car price predictor. 

Data

The data folder contains a link to the original website containing the data. Named used_cars_data.csv it contains used car data from the United States from the years 1981-2021. This data set is very large and cannot be loaded by itself. There are some smaller chunks of the data for analysis here as well.

https://www.kaggle.com/ananaymital/us-used-cars-dataset

Notebooks

Our notebook shows all the code used to clean the data as well as some initial analysis to understand which columns we felt were worthy of further evaluation. We were able to load the data into chunks and clean it and drop all of the null values. We then ran the data through a GridSearch Algorithm as well as an XGBoost model to find the feature importances. With this, we were able to determine which columns were the most important in predicting the car price. We then ran these columns through a XGBoost model as well as a K-Nearest Neighbors model. The predictions were ensembled togther. We then made a input function to get user input and predict the price of their car.


This analysis is done by Morgan Allen, Nick Phan, Stella Cunningham, and Woo Seok Kim.
