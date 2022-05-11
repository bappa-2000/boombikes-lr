# BoomBikes 
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to ongoin Covid-19 pandaemic. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes?
- How well those variables describe the bike demands?


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The project uses day.csv as the data set. 
- We need to model the demand of the shared bikes with different independent variables/features and identify their respective coefficient. 


## Technologies Used
- pandas library - version 1.3.4
- numpy library - version 1.20.3
- matplotlib library - version 3.4.3
- seaborn library - version 0.11.2
- statsmodels - version 0.12.2
- sklearn - version 0.24.2

## Conclusions
- The top 3 features contributing significantly towards explaining the demand of shared bikes are-
	- temp with the coefficient of 0.5499
	- weathersit_Light Snow/Rain (weathersit = 3) with the coefficient of -0.2880
	- year (yr) with a coefficient of 0.2331
- Interpretation
	- Demand is more during Fall season followed by summer season.
	- Demand is more during summer months (higher temperature) and clear weather conditions. 
	- Demand has significantly increased in the year 2019 as compared to 2018.
	- During spring, and light snow/rain/misty weather conditions the demand goes down as we can see that there is a negative correlation with these variables.


## Acknowledgements
- Research for General Subjective Questions from Google

