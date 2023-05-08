# DA-Project-Chennai-EXL
<table align="center">
  <tr>
    <td>Name</td>
    <td>PRANAVASHREE</td>
  </tr>
  <tr>
    <td>Enrollment No</td>
    <td>EBEON1122685376</td>
  </tr>
  <tr>
    <td>Batch</td>
    <td>2022-8410 DA</td>
  </tr>
  <tr>
    <td>Center</td>
    <td>Chennai EXL</td>
  </tr>
 </table>

# Fight Price Prediction
## Introduction
  The Flight ticket prices increase or decrease every now and then depending on various factors like timing of the flights, destination, duration of flights. In the proposed system a predictive model will be created by applying machine learning algorithms to the collected historical data of flights. Optimal timing for airline ticket purchasing from the consumer’s perspective is challenging principally because buyers have insufficient information for reasoning about future price movements.


## What we will see in this Notebook
- Problem Statement
- Importing Libraries
- Loading the dataset
- Data Inspection
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Checking for null values
- Using Encoding to Handle categorical data
- Feature Selection
- Building Machine Learning models
- Hyperparameter Tuning
- Conclusion

## About the Dataset

dataset is taken from the Kaggle website. The dataset includes prices for various airlines and cities between March and June of 2019, with a training set of 10,683 records and a test set of 2,671 records. The prediction results can be beneficial for both travelers, who can use it to make informed decisions about their travel, and for airlines, who can use it to forecast competitors' rates and adjust their pricing strategies to maximize revenue while remaining competitive.

- Size of training set: 10683 records
- Size of test set: 2671 records
- Link of the dataset:- https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh

### Conclusion

I have used here Linear Regreesion, KNeighborsRegressor, DecisionTreeRegressor,and RandomForestRegressor algorithm for prediction, we come to know that Random Forest classifier is more accurate among other algorithm,have used a random forest model for this data with improved accuracy by doing hyperparameter tuning. As a result, we were able to successfully train our regression model, the ‘Random forest model,’ to forecast fares of flight tickets with an R2 score of 84 percent and complete the required work.

## Future Work
- we try with different machine learning Algorithms
- We can deploy the model using Flask,Heroku,django etc
