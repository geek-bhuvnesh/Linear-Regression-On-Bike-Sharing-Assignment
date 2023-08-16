# Linear-Regression-On-Bike-Sharing-Assignment

> You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

### Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system. 

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

### Business Goal:
 You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

### Problem solution

- Data Understanding
- Data Cleaning
- Exploratory DataAnalysis
>  Univariate Analysis
>  Bivariate Analysis 
- Machine Learning Model
> Feature Selection (Using P-Value Method)
> Train Test Split
> Training the model
> Residual analysis(error)-   Residual analysis(error)
- Conclusion


## Conclusions
- It has been oberved that there is no null values in provided day data 
- Number of bikes rented in 2019 increased by 65% compared to the year 2018, which is a positive sign for any business on a year-over-year basis*
- Highest bike rented on Friday
- Most bikes were rented on working days. This indicates that a significant number of people are likely renting bikes for their daily commutes to their workplaces. As a result, the bike rental company, BoomBikes, generates the majority of its business (more than twice as much) on workdays rather than holidays or weekend
- Weather conditions play a significant role in the bike rental business. The number of bikes rented during rainy weather is notably lower compared to when the weather is clear
- The highest bike rentals occurred during August and June
- Bike rentals were more frequent during the fall season and relatively lower during spring. Upon analyzing the climatic conditions, one plausible explanation for this trend could be the significantly lower average temperature and higher average wind speed during spring compared to the fall
- Bike rentals were more frequent during the fall season and relatively lower during spring.
- On weekends, which are non-working days, the bike rental count is notably lower compared to other days. However, an intriguing pattern emerges: when Wednesday transitions from a working day to a holiday or non-working day, there is a significant increase in the number of rented bikes compared to Wednesdays that are regular working days
- R-squared score remains unchanged even after removing the 'weekday_Wed', 'temp', 'mnth_Jul' etc columns
- Distribution of errors is normal and centers around 0. This observation suggests that our model has effectively addressed the assumption of normal error distribution.
- There is minimal correlation between the Residual and Predicted Value. This outcome aligns with our model's expectation of exhibiting no distinct pattern
- The initial structure of X_train included 29 columns, resulting in an achieved r2 score of approximately 84.17%.


## Technologies Used
- Python 3.10.11
- pandas - 2.0.2
- numpy - 1.24.3
- matplotlib - 3.7.1
- seaborn - 0.12.2
- sklearn - 1.3.0


## Acknowledgements

- https://www.kaggle.com/
- https://seaborn.pydata.org/
- https://pandas.pydata.org/
- https://learn.upgrad.com/
- https://scikit-learn.org/

## Contact

Created by [@geek-bhuvnesh] feel free to contact us!
