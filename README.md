# Boom Bikes Linear Regression Assignment
> This project focuses on explaining the target feature using optimal number of input features with Linear Regression Algorithm.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Boom Bikes is a US based bike sharing provider has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. They wants to cater the people's needs once the situation gets better all around and stand out from other service providers.
- Boom Bikes is trying to understand the factors on which the demand for these shared bikes depends.
- We will find "which variable is significant in predicting the demand for shared bikes" and "how well those variables describe the bike demands".
- Based on various meteorological surveys and people's styles, Boom Bikes has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model built with all Features 27 has R2 Score as 81.2% on Test Data
- Model built with 14 Features 
  'const','temperature','humidity','windspeed','season_spring','season_winter','year_2019',
  'month_dec','month_nov','month_sep','is_holiday_not_holiday','weekday_saturday',
  'is_workingday_workingday','weather_lightrain','weather_mist'
  has R2 Score as 79.38% on Test Data
- Model built with 10 Features  
  'const','temperature','humidity','windspeed','season_spring','season_winter','year_2019',
  'weekday_saturday','is_workingday_workingday','weather_lightrain','weather_mist'
  has R2 Score as 78.6% on Test Data
  
So we will go with 10 Features model as final one.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- matplotlib
- pandas
- seaborn
- statsmodel
- scikit-learn
- numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is part of my "Executive PG Programme in Machine Learning & AI" assignment.


## Contact
Created by [@CrazyDussa] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
