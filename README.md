# Boom Bikes Linear Regression Model Assignment
This is an assignment for resolving a problem of identifying the factors on which a bike renting company boom bikes wants to do analysis for expanding their business and take a lead with their competitors in the market.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
Which variables are significant in predicting the demand for shared bike
How well those variables describe the bike demands 
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

## Conclusions
The summary of the model after data interpretation, visualisation, data-preparation, model building and training, residual analysis and evaluation of test model are as follows-

The R-squared value of the train set is 84.3% whereas the test set has a value of 81.0% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

Our developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

We can conclude that the bike demands for the BoomBikes company is dependent on the temperature and whether it is a workingday or not. Additionally more rentals seem to be demanded on the winters as compared to the summer and spring. We had observed that the months of September had higher use of rentals. In terms of days the maximum turnaround was on days like Wed, Thurs and Sat and more on holidays.

The Year has a strong positive impact on the demand for shared bikes. This suggests that the demand for shared bikes has been steadily increasing over the years from 2018 to 2019.
Seasonality (spring, summer, fall, winter) also significantly influences demand. Summer and fall generally see higher demand compared to winter and spring.
The day of the week impacts demand. Weekends (Saturday and Sunday) typically have higher demand compared to weekdays.
The presence of holidays can significantly impact demand, usually people tend to stay at home in holidays and hence the booking count is low.
Working Day and Non-Working Day are almost having same count values of bike booking and hence have not major impact.
Majority of bookings were done in mid-year starting from June to Sept and then year-end the bike booking again decreases.

Rentals were more in 2019 than 2018 which suggests that over time more people would be exposed to this idea and there has to be a strong analysis done to retain the repeat customers.

These interpretations help us derive meaningful insights in the bike rental market and the behaviour of the people. One of the recommendations based on this model are that there should be aggressive marketing in the summer and spring season to drive up rentals. Since the summer months also show low rental levels, a strong marketing strategy for the first 6 months of the year can assist in driving up the rental numbers. There has to be an approach required to introduce more users on days where the weather is less clear, perhaps with incentives or strategic deals.

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- statsmodels.api
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upGrad
- References if any...
- This project was based on [this tutorial](https://www.upgrad.com).


## Contact
Created by [@kafeel123ahmad] - feel free to contact me!
