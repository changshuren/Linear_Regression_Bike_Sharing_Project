# Bike Sharing Project
> Outline a brief description of your project.

This project is to identify factors affecting the demand for the shared bikes in the American market. The questions will be answered:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A US-based bike-sharing provider, BoomBikes has recently suffered a great deal of sale loss in their revenues due to the widespread COVID pandemic. 
- They ask for help from a consulting company, which will provide the analysis that aims to understand the influential factors that boosts the demand for these shared bikes relies.
- Specifically, they want to understand the important factors affecting the demand for these shared bikes in the current market.
- The dataset contains many variables collected related to the demand and sales from the sharing bikes. 

## Conclusions

- According to the results, the equation of our best fitted line is:

CNT = (-0.317)* light_rain_snow + (-0.175)*windspeed + (-0.093)*mist_cloud + 0.058*workingday + 0.066*Saturday + 0.082*sep + 0.098*oct + 0.190*winter + 0.248*yr + 0.255*summer + 0.294*fall 

- Overall, we have a decent model with the value of R^2 at 77.8% in training data and at 77.1% in test data.   

The following conclusions are based on the results of the analysis with 11 features, which all together have significant contributions to the model. In other words, the following factors might booster the sales of the bike sharing. 

1.	When weather conditions are: no light rain/snow, no mist/cloud, or having a lower windspeed, the sales are likely much better.
2.	During the seasons in summer, fall, or winter, the sales are better except in spring.
3.	In September and October, the sale trends are doing better. 
4.	During working days and Saturdays, the sales tend to be good. 
5.	The sales in year 2019 are better than the ones in 2018. Following the sale trend, the sales in following years are likely doing better.  

## Technologies Used
- Python - 3.8.2
- Numpy - 1.14.5
- Pandas - 1.1.0
- Seaborn - 0.12.2
- Matplotlib - 3.2.1
- Scikit-learn 1.2.2
- Statsmodels 0.11.0

## Acknowledgements
- Theoretical and practical concepts learned from Linear Regression module are very helpful to address real-world issues.

## Contact
Created by [@changshuren] - feel free to contact me!

## License
This project is open source.