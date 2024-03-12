# Bike Sharing Analysis
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Observation](#observation)
* [Conclusions](#conclusions)

## General Information
- This assignment is based on the bike-sharing system dataset. The dataset contains the hourly count of rental bikes between years 2011 and 2012 in the Capital bikeshare system with the corresponding weather and seasonal information. The dataset is publicly available on the UCI Machine Learning Repository. The dataset has been used for this assignment is available at the following link: [Bike Sharing Dataset](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)
- The objective of this assignment is to perform an exploratory data analysis of the bike-sharing system dataset. The analysis will help in understanding the patterns and trends in the bike-sharing system dataset. The analysis will also help in understanding the factors that affect the demand for rental bikes. The analysis will also help in understanding the impact of weather and seasonal factors on the demand for rental bikes.
- The analysis will be performed using the Python programming language and its libraries for data analysis and visualization. The analysis will be performed using the Jupyter Notebook environment. The analysis will be performed using the following steps:
  - Data Preprocessing
  - Data Visualization
  - Exploratory Data Analysis
  - Conclusion

## Technologies Used
- Python - version 3.9
- Jupyter Notebook - version 6.6.3
- Pandas - version 2.2.0
- Numpy - version 1.26.3
- Matplotlib - version 3.8.2
- Seaborn - version 0.13.2
- Sklearn - version 1.4.0
- Statsmodels - version 0.14.1

## Observation
- The predicted model will follow the following linear equation: 
```
  y = 0.2876 + 0.2364yr + 0.3905temp - 0.1474windspeed - 0.1069season_spring + 0.0421season_winter - 0.0501mnth_Jan + 0.0647mnth_Sep - 0.0464weekday_Tuesday - 0.0778Mist - 0.2904Snow
```
- Demand is strongly correlated with temperature and it increases when temperature rises
- Demand is increasing YOY basis
- In Spring season demand for bikes decreases
- Demand increases in winter season and clear weather
- Demand is low on tuesdays
- Demand decreases significantly in snowy weather

## Conclusions
The best fitted equation for predicting the demand of shared bikes depends on the major factors like the year, temperature, season, weather situation. It is positively related with temperature while it is negatively correlated with bad weather.
