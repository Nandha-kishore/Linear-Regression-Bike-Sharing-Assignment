#Linear-Regression-Bike-Sharing-Assignment

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents

- [About](#About)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)

## About

- Problem:
  A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
  In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

- Agenda :
  Which variables are significant in predicting the demand for shared bikes.
  How well those variables describe the bike demands
- DataSet :
  day.csv

- Steps Followed :
  ~ Reading and Understanding the Data
  ~ Data Visualization
  ~ Data Preparation
  ~ Model Building
  ~ Residual Analysis
  ~ Making Predictions
  ~ Model Evaluation

## Conclusions

 The Overall sales have increased from the year 2018 to 2019.
 The bookings are more during the Mid of the year and less during the beginning and ending maybe due to more number of holidays.
 The bookings are high when the weather is Clear, Few clouds, Partly cloudy.
 Booking are comparitvely less on holidays.
 Registered users are using the bikes more than casual users.

## Technologies Used

Language : Python

Libraries : - pandas (To work with dataset) - numpy (Math library) - seaborn (Graph library that use matplot in background) - matplotlib.pyplot (to plot some parameters in seaborn) - warnings (to ignore warnings) - sklearn.model_selection (to split the dataframe into Train and Test) - sklearn.preprocessing (Using MinMaxScaler to Rescaling the features) - sklearn.feature_selection (Importing RFE) - sklearn.linear_model (Importing LinearRegression) - statsmodels.stats.outliers_influence (Check for the VIF values of the feature variables) - statsmodels.api (Building linear regression model) - sklearn.metrics (R-squared score)

## Contact

Created by :
Nandha Kishore(https://github.com/Nandha-kishore)
