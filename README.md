# Multiple Linear Regression - BoomBikes Bike Sharing Case Study
> To build a multiple linear regression model for predicting the demand for shared bikes with the available independent variables. The target variable is 'cnt'


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
#### Problem Statement:
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
####  Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. 


## Conclusions
### The equation of model: 
cnt =  0.09 + 0.23\*yr - 0.09\*holiday  + 0.57\*temp  - 0.15\*windspeed  + 0.08\*summer  + 0.13\*winter  + 0.09\*mnth_9 - 0.25\*light_snow

### OLS Regression Results    
  <img src="https://github.com/coachjimmyha/ML-LinearRegressionAssignment-BikeSharing/blob/master/OLS_Regression_Results.png" alt="Bike Sharing Model" width="500">

## Technologies Used
- warnings
- python
- numpy
- pandas
- matplolib
- sklearn
- statsmodel

## Contact
Created by [@coachjimmyha] - feel free to contact me!
