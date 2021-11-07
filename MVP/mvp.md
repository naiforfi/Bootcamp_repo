## Predicting the rain in Saudi Arabia

This project is aim to use historical weather data like temperature, humidity, windspeed, visibility and the pressure, and understand which elements are most important in to predict the rain phonomena.



This start analysis use some feature engineering, Data cleansing and logistic regression model is been used with two features: temperature `temp` and `humidity`. I discover that the it's distributions is clearly related the target.

```
              precision    recall  f1-score   support

       False       0.72      0.76      0.74       704
        True       0.72      0.67      0.70       644

    accuracy                           0.72      1348
   macro avg       0.72      0.72      0.72      1348
weighted avg       0.72      0.72      0.72      1348
```

we could change the threshold to bias toward more precision ,However, we belive that other weather elements can support the model which may help us to predict more precisely.
