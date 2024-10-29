# Project Name
## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

Business Goal:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- What is the background of your project?
  Project is all about making BoomBikes profitable, as due to covid it faced lots of revenue loss. So we utilize Linear Regreassion technique to know about how can we improve revenue and make BomBike profitable again
  
- What is the business probem that your project is trying to solve?
  #### Recover Book Bike revenue loss
  #### Best suitable environment for Bike sharing and factor most affecting business.
- What is the dataset that is being used?
  #### BoomBike bike sharing system



## Conclusions
- cnt = 4491.30 + 992.43 x yr + 1229.32 x temp -442.38 x hum - 350.59 x windspeed + 303.88 x Summer + 510.12 x Winter -123.63 x July + 211.14 x September -109.19 x Monday
- Three key feature variables, temp, yr, and Winter, exhibit the highest coefficient values, indicating their significant impact.
- The RMSE values of 837 in the training set and 839 in the test set for a linear regression model indicate that the model is fitting well to the training data and generalizing reasonably to new, unseen data with a small difference         between training and test set performance.




## Technologies Used
- Python - version 3.11.4
- Matplotlib - version 3.7.1
- Numpy - version 1.24.3
- Pandas - version 1.5.3
- Seaborn - version 0.12.2
- Statsmodels - version 0.14.0
- Scikit-Learn - version 1.3.0


## Acknowledgements
- This project is assignment from Upgrad for Linear Regression study.
  


## Contact
Created by [@ashish2790] - feel free to contact me!
