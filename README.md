# IOT Projects with Raspberry Pi

![alt text](https://github.com/chalendony/iot/blob/master/images/collecting-hardware.png)


# Humidity / Temperature Data and Analytics 

Objectives:

Part 1) Set up Your Python Environment

Part 2) Explore and Understand characteristics of the Humidity and Temperature (HT) data - collected from my Raspberry Pi HT11 Sensor

Part 3) Clean Prepare data for two types of predictive tasks: Linear Regression and Classification 

Part 4) Make predictions with heat and temperature data using both classic Statistics and Machine Learning algorithms 

## PART 1: Setting up Python Environment

#### A. install pip 

#### B: create environment

#### C. install requirements

#### D. test setup


TODO : store data set - from my server, check link works, backup plan if server down showtime

## PART 3. About Time Series Data

## PART 2: Explore and Understand Data

About Time Series Data



| Algorithm                                                                             | Type  | Seasonality | Trend | 
|---------------------------------------------------------------------------------------|-------|-------------|-------| 
| Autoregression (AR)                                                                   | uni   | n           | n     | 
| Moving Average (MA)                                                                   | uni   | n           | n     | 
| Autoregressive Moving Average (ARMA)                                                  | uni   | n           | n     | 
| Autoregressive Integrated Moving Average (ARIMA)                                      | uni   | n           | y     | 
| Seasonal Autoregressive Integrated Moving-Average (SARIMA)                            | uni   | y           | y     | 
| Seasonal Autoregressive Integrated Moving-Average with Exogenous Regressors (SARIMAX) | uni   | y           | y     | 
| Vector Autoregression (VAR)                                                           | uni   | n           | n     | 
| Vector Autoregression Moving-Average (VARMA)                                          | mulit | n           | n     | 
| Vector Autoregression Moving-Average with Exogenous Regressors (VARMAX)               | mulit | n           | n     | 
| Simple Exponential Smoothing (SES)                                                    | uni   | n           | n     | 
| Holt Winter’s Exponential Smoothing (HWES)                                            | uni   | y           | y     | 


### 2.1: Outside Humidity and Temperature Data

#### A. Visual Inspection

* Q: Does the plot make sense?

* Q: Is the data seasonal?

* Q: Does the data have a trend?

* Q: Is the Data Additive or Multiplicative

* Q: Is the data Stationary

* Q: Does the data contain outliers that can potentially hinder algo performance

* Q: Is there missing data, can missing data be explained?

#### B. Decompose Time Series:

#### C. Overlaying Official Weather Data

 


### 2.2: Inside Humidity and Temperature Data



## PART 3: Data Preparation 

How prepare data for time series analysis

* Smoothing Data 


## PART 4: Builld Model to Make Predictions


### What Predict?


* Predict Temperature and Humidity:  a single step in future - by using past observations of single variable (univariate) or past observations of 
 
 * Predict Season:  given more than one time series variables (multivariate) 


### Predicting Temperature and Humidity 

Univariate Regression : Single variable input (temperature or humidity) and forecast a  numerical quantity (temperature)


Algorithms Classical Statistics:

* Triple Exponential Smoothing
* SARIMA: Seasonal ARIMA

Machine Learning:
* MLP
* BNN



### Predicting Season 

* Multivariate : Multiples variables used as input 
* Classification : predict label (season)


Machine Learning Algorithm

* LSTM
* RNN
