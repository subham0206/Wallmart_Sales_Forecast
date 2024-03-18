# Wallmart_Sales_Forecast
ML assignment Evaluation

Bike Sharing Assignment
Build a Multiple linear regression model to solve bike sharing problem for a company. Check out the full code available in my collab notebook with better readability: https://drive.google.com/drive/folders/1OJj2GvCnni0lHHiVg7QTYrAnehOtMDt6?usp=sharing

Table of Contents
General Info
Technologies Used
Conclusions
Acknowledgements
General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

Business Goal: We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

Conclusions
Top 3 predictor variable based on their coefficient caluculated using LR Model

Temperature: coeff "0.403895" indicates increase in temperature will increase in bike demand

Weather (thunderstorm or situation 3): coeff "-0.249302" indicates increase in situatuion 3 will decrease bike demand

Year: coeff "0.242173" indicates increase in year will increase in bike demand

General Observation

There seems to be jump in bike demand during september, company should come up with more offer to increase demand during sept.
It's evident from above analysis that there would be less bookings as weather condition goes severe i.e Rainy, Thunderstorm, Snow etc.
As we see rise in users demand from 2018 to 2019,we can expect to see a rise in demand again as situation goes normal.
Demand for bike depends on these independent variable significantly i.e year (2019>2018), holidays, temperature, windspeed, september month, weather (cloudy, thunderstorm) & season (spring, summer, winter).
Technologies Used
Python -pandas -numpy -matplotlib -seaborn -sklearn -statsmodel
Acknowledgements
I would like to thank Upgrad and IIIT Bangore professor for designing this assignment and special thank to my upgrad buddy for guiding us through this project
Contact
Created by [@subham0206] - feel free to contact me!
