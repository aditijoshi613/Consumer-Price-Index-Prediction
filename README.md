# Consumer-Price-Index-Prediction

## DATA/MSML602: Principles of Data Science Final Project

Submission by: Aditi Ganesh Joshi (119171493), Rishabh Bhonsle(119392157)

Introduction

Time series forecasting is the process of predicting future decision variables based on analysis of historical time series data related to the same variable.  These future variables are predicted based on the assumption that future trends will hold similar to historical trends. An important property of a time-series algorithm is that it extrapolates patterns outside of the domain of training data. Unlike most ML regression models that predict data within its dataset, a time series forecasts data by extrapolation of its ordered dataset.

Data

Time series forecasting is arguably one of the most common areas where machine learning is applied in business. For our implementation of time series forecasting, we choose data obtained through the consumer price index (CPI) of the United States (U.S.). The Consumer Price Index (CPI) measures the monthly change in prices paid by U.S. consumers. The Bureau of Labor Statistics (BLS) calculates the CPI as a weighted average of prices for a basket of goods and services representative of aggregate U.S. consumer spending. Thus the CPI data would directly or indirectly contribute to changes in time series prediction of any business affiliated model. We thus study the CPI time series data.

Source of Data

The CPI time series data is obtained from the Main Economic Indicators database includes a wide range of areas from 196, such as quarterly national accounts, business surveys, retail sales, industrial production, construction, consumer prices, total employment, unemployment rates, interest rates, money and domestic finance, foreign finance, foreign trade, and balance of payments. This data is extracted from the OECD  (Organisation for Economic Cooperation and Development) Library using the FRED API (“Organization for Economic Co-operation and Development, Consumer Price Index: Total All Items for the United States [CPALTT01USM657N]”). The FRED API (FRED API) is a web service that allows developers to write programs and build applications that retrieve economic data from the FRED and ALFRED websites hosted by the Economic Research Division of the Federal Reserve Bank of St. Louis. 

Description of Data

The CPI time series data consists of CPI values from 1960 to date at a monthly frequency. At the time of December 2022, this dataset thus has 753 data points. 
