# Time Series

Forecasting is valuable in a variety of industries and fields. From financial data where we forecast market volatility, 
to consumer product good (CPG) companies where we forecast demand and sales individually for our products, to energy companies forecasting energy demand from their customers, 
time series and forecasting models drive business decisions and insights.

With the ever growing focus on energy usage, getting accurate forecasts for the use and demand of energy is vitally important. 
These energy forecasts allow energy companies to better adjust and plan for future energy demand by consumers which guides policy and resource management. 
Forecasting too low leads to having to buy energy from other locations or rolling black-outs. Forecasting too high leads to over use of resources.

Forecasting is a complicated process that involves a combination of analytical techniques. 
The company needs your help to use regression and time series techniques to forecast and visualize hourly energy usage for million of their customers for resource allocation.

Your project will involve accomplishing the following tasks:

* Visualizing and exploring the time series characteristics of hourly energy data.
* Exploring relationships between temperature and energy usage across different times of year.
* Building a linear regression model using temperature, hourly, and day of week effects to forecast energy usage.
* Expand the linear regression model to become more dynamic and include time components with ARIMA models.
* Compare the dynamic time series model with an exponential smoothing model.
* Incorporate holiday effects into the time series forecast.


# Techniques employed
Forecasters are always learning new techniques to improve their forecasts and must use outside resources to do so. We will give you the resources to learn more, 
just like you would do in a real job. Remember, these techniques aren’t only limited to energy forecasting. They provide value in almost any industry.


Listed under the bullets are the Python libraries for the technique:

* Exploring and visualizing relationships in energy data

     * pandas: manipulating and matching up data sets as well as creating new variables for the models
     * matplotlib: visualizing relationships between variables as well as variables across time
     
* Building a model between energy usage and a variety of temperature, hour, and month factors

     * statsmodels: building a linear regression model
* Layering on dynamic time series effects to the linear regression model

    * statsmodels: building time series models - exponential smoothing, ARIMA
    
* Evaluating holiday effects in energy data

    * statsmodels: adding holiday effects to linear regression model
* Visualizing the final forecast

    * matplotlib: displaying the results of your final forecast compared to the actual data

