# BoomBike Multiple Linear Regression Assignmnet
> Linear Regression performed on the Boombikes bike rental dataset as part of an assignment.


## Problem Statement
* A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.



## General Information
- Multiple linear regression is performed on the dataset.
The project is done as part of coursework in the Machine Learning module.
We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc.
The Boombikes bike rental dataset is being used.

## Conclusions
- The R-squared value of the train set is 82.71% whereas the test set has a value of 81.13% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

Our developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

The major steps included in the python notebook are data interpretation, data visualisation, data pre-processing, model training, feature selection, residual analysis, model evaluation on the test set.

Concepts such as EDA, p-value, VIF, RFE were used and model building was done using statsmodels library



## Technologies Used
pandas
seaborn
matplotlib
statsmodels
sci-kit learn
numpy


## Contact
Created by [@himansu2] - feel free to contact me!
