# Predicting The rain phenomena in Saudi Arabia

This repository is made in SDAIA Acadmey bootcamp.

Naif Alorfi

## Abstract

Weather information considered important in many fields such as Aviation, Agriculture, Municipalities and many others. We need water for many reasons and weather controls the distribution of rain water on earth. The aim of this project is to analysis the coorelation of the weather information and use classification models to predict rain Phenomena in Saudi Arabia. First, I preprocessed on ["Saudi Arabia Weather History"](https://www.kaggle.com/esraamadi/saudi-arabia-weather-history) dataset and implement some exploratory data analysis and deal with outliers using Interquartile Range (IQR) and data balncing use SMOTE. Then I have implemented feature scaling. at the end a I have train the dataset with 3 models Logistic Regression and Artificial Neural Network and then random forest classifier.

## Design

This project aims to predict the rain based on other weather elements that hopefully it can help forecasters in the meteorology center and other officals for example Municipalities need the rain forcast to get prepared for any incident that may occur because of the rain Such as flash flood. I understand there is many factors that should be considered when forecasting the weather. This project is based on the dataset available publicly at [Kaggle](https://www.kaggle.com/esraamadi/saudi-arabia-weather-history) website with title "Saudi Arabia Weather History".

## Data

Dataset is contains hourly historical weather data for all Saudi Arabia cities from 2017 to 2019 with 249023 observations and 15 variables for each, 10 Numerical and 5 Categorical variable with object datatype. Unfortunately the data is not described on the website but I have got the information from meteorologist and identified as the following :
|  # |  Columns |   description |   |   |
|---|---|---|---|---|
|  1 | `Unnamed` : | index.  |   |   |
|  2 | `city` :    | City name.  |   |   |
|  3 | `date` :    | The date of Observation.  |   |   |
|  4 | `time` :    | The time of Observation.  |   |   |
|  5 | `year` :    | The year of Observation  |   |   |
|  6 | `month` :   | The month of Observation  |   |   |
|  7 | `day` :     | The day of Observation |   |   |
|  8 | `hour` :    | The hour of Observation  |   |   |
|  9 | `minute` : | The minute of Observation  |   |   |
| 10 | `weather` : | List of phenomenas.  |   |   |
| 11 | `temp` :    | Temperature.  |   |   |
| 12 | `wind` :    | Wind speed. |   |   |
| 13 | `humidity` : | The percentage of Humidity |  |   |
| 14 | `barometer` : |The pressure per barometer  | |   |
| 15 | `visibility`:| The visibility per KM  |   |   |


## Algorithms

## Tools

## Communication
