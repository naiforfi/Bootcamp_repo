## Predicting the rain in Saudi Arabia

This project is aim to use historical weather data like temperature, humidity, windspeed, visibility and the pressure, and understand which elements are most important in to predict the rain phonomena. 

![file](https://github.com/naiforfi/Bootcamp_repo/blob/main/MVP/figure.png)


During the data analysis we found that thers is a relation when ploting the features: `temperature` and pressure (`barometer`) which it seems whether was rain occured or not. However, we belive that other weather factor can support the relationship which may help us to predict more precisely.

Logstic regression is been used with minimal features resulted as accuracy of  98%. 
```
              precision    recall  f1-score   support

       False       0.99      1.00      0.99    122866
        True       0.44      0.04      0.07      1646

    accuracy                           0.99    124512
   macro avg       0.72      0.52      0.53    124512
weighted avg       0.98      0.99      0.98    124512
```
