# Bike sharing Assignment

Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

Technologies used: Python

Solution: I have analysed the data and after that data cleaning and data manipulation done. Did unvariate analysis, univariate continuous variable analysis, Bivariate and Multi-variate variable analysis by using plots and created the model and applied the model on test data.

Conclusion: As per our final Model, the top 3 predictor variables that influences the bike booking are:

Temperature (temp) - A coefficient value of ‘0.378031’ indicated that a unit increase in temp variable increases the bike hire numbers by 0.378031 units.
weathersit_Light Snow - A coefficient value of ‘ -0.289853’ indicated that, a unit increase in weathersit_Light Snow variable decreases the bike hire numbers by -0.289853 units.
Year (yr) - A coefficient value of ‘0.241211’ indicated that a unit increase in yr variable increases the bike hire numbers by 0.241211 units.
So, it's suggested to consider these variables utmost importance while planning, to achive maximum Booking
The next best features that can also be considered are

season_spring: - A coefficient value of ‘-0.159358’ indicated that a unit increase in season_spring variable increases the bike hire numbers by -0.159358 units.
