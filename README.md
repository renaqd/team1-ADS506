# team1-ADS506
Applied Time Series Analysis


## Objective
The primary business objective is to develop an automated forecasting system to predict electricity demand for the period from October 2020 through October 2021, using historical data for timely, proactive decision-making. Success will be measured by achieving accurate forecasts, automating daily forecast generation, reducing resource allocation inefficiencies, and decreasing operational costs while maintaining service reliability. The company faces challenges such as manual intervention in forecasting, market volatility, competition, and government restrictions that impact demand patterns, making efficient forecasting and resource planning critical to its success. This project, led by a data science team from ADS506, seeks to develop a robust forecasting model for electricity demand.

## Data Source
https://www.kaggle.com/datasets/aramacus/electricity-demand-in-victoria-australia

## Team #1
* Lorena Dorado - EDA, Data Prep
* Nolan Peters - Modeling and Model Evaluation
* Tysir Shehadey - Pre-processing

## Methods
* EDA
* Time Series Modeling

## Language
* R

## Libraries
1. tidyverse
2. fpp3

## Dependent Variable
* Demand : float, a total daily electricity demand in MWh

## Independent Variables
* Date : datetime, the date of the recording
* Regional Reference Price (RRP) : float, a recommended retail price in AUD$ / MWh
* Demand Positive RRP : float, a total daily demand at positive RRP in MWh
* RRP_positive : float, an averaged positive RRP, weighted by the corresponding intraday demand in AUD$ / MWh
* Demand Negative RRP : float, an total daily demand at negative RRP in MWh
* RRP_negative : float, an average negative RRP, weighted by the corresponding intraday demand in AUD$ / MWh
* frac_at_neg_RRP : float, a fraction of the day when the demand was traded at negative RRP
* Minimum Temperature : float, minimum temperature during the day in Celsius
* Maximum Temperature : float, maximum temperature during the day in Celsius
* Solar Exposure : float, total daily sunlight energy in MJ/m^2
* Rainfall : float, daily rainfall in mm
* School Day : boolean, if students were at school on that day
* Holiday : boolean, if the day was a state or national holiday