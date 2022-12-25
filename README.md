#  Time Series Data Predictions analysis using Weather Data


## Introduction

  Time series data is a type of data that is collected over a period of time, typically at regular intervals. This data consists of a sequence of measurements, observations, or events that are recorded at specific times, and can be used to understand trends and patterns in the data over time. Analytics for time series involves a range of techniques and methods that are designed to extract useful insights and information from the data, such as statistical analysis, machine learning algorithms, and data visualization techniques. 
    
    
   In order to predict future values for any dataset using existing datasets, we need to use some form of regression. Regression models are statistical models that are used to predict a continuous outcome variable based on one or more predictor variables. These models are commonly used in time series data analytics to forecast future values of a given variable based on its past values.
   
Linear regression is one of the most commonly used regression models for time series data. This model assumes that there is a linear relationship between the predictor variable (the time series data) and the outcome variable (the value being predicted). Linear regression models can be used to make predictions about future values of a time series based on a set of past values.

## Dataset

   For the weather data, we referred to the [Open-Meteo Weather API](https://open-meteo.com/en/docs/historical-weather-api) . The idea was to gain access to a reliable datastream which could be used as a long term feed for the model once we were able to train a reliable data model for our predictions.

  In the short term, we have prepared a data dump for the last ~20 years of data to use in the code in a static manner. We’ve prepared extracts for the following 5 cities: New York, Mumbai, London, Canberra, and Los-Angeles.
  
  Parameters selected for the extract can be found  [here](https://github.com/palakkeni5/ML-project/blob/main/data/open-meteos-historical-weather-api-extract-config.pdf)
  
  ## References
  
*[https://scikit-learn.org/](https://scikit-learn.org/)

*[https://www.statsmodels.org/dev/vector_ar.html](https://www.statsmodels.org/dev/vector_ar.html)

*[https://www.statology.org/granger-causality-test-in-python](https://www.statology.org/granger-causality-test-in-python)

*[https://www.analyticsvidhya.com/blog/2018/08/k-nearest-neighbor-introduction-regression-python/](https://www.analyticsvidhya.com/blog/2018/08/k-nearest-neighbor-introduction-regression-python/)

*[https://www.analyticsvidhya.com/blog/2020/03/support-vector-regression-tutorial-for-machine-learning/](https://www.analyticsvidhya.com/blog/2020/03/support-vector-regression-tutorial-for-machine-learning/)

*[https://keremkargin.medium.com/ridge-regression-fundamentals-and-modeling-in-python-bb56f4301f62](https://keremkargin.medium.com/ridge-regression-fundamentals-and-modeling-in-python-bb56f4301f62)

*[https://machinelearningmastery.com/ridge-regression-with-python/](https://machinelearningmastery.com/ridge-regression-with-python/)

*[https://medium.com/analytics-vidhya/lasso-regression-fundamentals-and-modeling-in-python-ad8251a636cd](https://medium.com/analytics-vidhya/lasso-regression-fundamentals-and-modeling-in-python-ad8251a636cd)

*[https://towardsdatascience.com/vector-autoregressive-for-forecasting-time-series-a60e6f168c70](https://towardsdatascience.com/vector-autoregressive-for-forecasting-time-series-a60e6f168c70)
