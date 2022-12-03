# Real-Estate-Price-Prediction

What are the things that a potential home buyer considers before purchasing a house? The location, the size of the property, vicinity to offices, schools, parks, restaurants, hospitals or the stereotypical white picket fence? What about the most important factor — the price?
So worked on real life data science project in which had to predict the property price based on certain features such as :
1.Bedroom
2.Sqft
3.Location
4.Bathroom 
5.Area type
6.Size
7.Society
8.Balcony

Tool Used:
1.Python:Programming language
2.Pandas:Data Clening
3.Matplotlib:Visualization
4.Sklearn:Model Building

# Workflow of the project:
1.Dataset: Have downloaded the dataset from kaggle (https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data) which is the data for banglore city in India.

2.EDA:Such as dropping certain columns which are not important for predicting the price and also exploring the columns 

3.Data Cleaning:dropping NaN values and outlier detection and removal

4.Feature engineering:To transform rows because there are many locations which have different data points so have to come up with threshold such as less than 10 data points for better prediciton

5.Model Building: Did hyperparameter tuning using gridsearch CV to check the best model for this dataset. Tried different models such as Linear Regression,Lasso Regression,Decision Tree Regressor. And the conclusion was Linear Regression is the best model for this data 

6.Predictive System: Made a predictive system which predicted the price based on location,sqft,bath,bhk.
