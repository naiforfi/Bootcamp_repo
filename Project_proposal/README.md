# Project proposal
This reposotories is made in SDAIA Acadmey bootcamp.

# Is Going To Rain?
Weather imformation is important in many industries such as Aviation, agriculture, municipalities. 
Weather controls the distribution of rain water on earth. The aim of this study is to analysis the coorelation of the weather information and bulid model that help to predict rain Phenomena in Saudi Arabia. 

# Dataset 
The dataset is publically available on the Kaggle website titled Saudi Arabia Weather History.
https://www.kaggle.com/esraamadi/saudi-arabia-weather-history

This dataset contains hourly historical weather data for all Saudi Arabia cities from 2017 to 2019 . Included a date for which you would like to see weather history such as temperature, wind, humidity, barometer, visibility and the Phenomena. the data contains 15 columns and 249023 records. 

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Unnamed: 0</th>
      <th>city</th>
      <th>date</th>
      <th>time</th>
      <th>year</th>
      <th>month</th>
      <th>day</th>
      <th>hour</th>
      <th>minute</th>
      <th>weather</th>
      <th>temp</th>
      <th>wind</th>
      <th>humidity</th>
      <th>barometer</th>
      <th>visibility</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>0</td>
      <td>Qassim</td>
      <td>1 January 2017</td>
      <td>00:00</td>
      <td>2017</td>
      <td>1</td>
      <td>1</td>
      <td>24</td>
      <td>0</td>
      <td>Clear</td>
      <td>17</td>
      <td>11</td>
      <td>64%</td>
      <td>1018.0</td>
      <td>16</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>Qassim</td>
      <td>1 January 2017</td>
      <td>01:00</td>
      <td>2017</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>Clear</td>
      <td>17</td>
      <td>6</td>
      <td>64%</td>
      <td>1018.0</td>
      <td>16</td>
    </tr>
  </tbody>
</table>


We have notice that there are few missing values, and some data need to converted to correct data type. Also it seems that the weather column represet the weather Phenomena which is in text format. and multiple Phenomena merged together. So we will extrat  the keyword "rain" and it's synonyms and create new column tells rained or not raind.


# Tools
This project will use ```Jupytur Notebooks``` on coda environment, ```Python``` programming language and some python libraries, such as ```numpy , pandas``` for mathematical functions, data analysis and manipulation. Also for predictive data analysis it uses ```cikit-learn``` library, and for data visualization use ```matplotlib``` and ```seaborn```.


