# Bike Sharing assignment- BoomBikes
>Model on prediction of demand of Bike Sharing ('BoomBikes') with Multiple Linear Regression.


## Table of Contents
* Step 1: Reading and Understanding the Data
* Step 2: Visualising the Data
* Step 3: Data Preparation
* Step 4: Splitting the Data into Training and Testing Sets
* Step 5: Building a linear model
* Step 6: Residual Analysis of the train data
* Step 7: Making Predictions Using the Final Model
* Step 8: Model Evaluation

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement/General Information

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


- Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- R square of final model built is 0.8083, and the adjusted R square is 0.8109.
- The final equation of the Target variable 'cnt' with respect to all the Predictor variabes is :
 (cnt = 0.2401yr - 0.0985holiday + 0.4623temp - 0.2857lightSnowRain - 0.0754MistCloudy - 0.1258Spring + 0.0587Winter + 0.1724)
 - We can say that temp (positive relation by slope of 0.4623), year(positive relation by slope of 0.2401) and LightSnowRain(weather being Light snow or rainy with negative slope of 0.2857) are the top 3 features, in order, contributing significantly towards explaining the demand of the shared bikes


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.10
- Pandas - version 1.5.0
- Scikit-learn - version 0.20
- Statsmodels - version 0.11

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is part of multiple linear regression assignment.

## Contact
Created by @ShashiKant7391 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
