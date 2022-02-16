# Carbon-Emission-Analysis
From a company perspective, bringing greater transparency to carbon intensity can help better manage emissions, and analyze business risk and potential opportunity. 

** INTRODUCTION:- 
       Time Series Analysis is the way of studying the characteristics of the response variable with respect to time, as the independent variable. To estimate the target variable in the name of predicting or forecasting, use the time variable as the point of reference. In this article we will discuss in detail TSA Objectives, Assumptions, Components (stationary, and Non- stationary). Along with the TSA algorithm and specific use cases in Python.
        This notebook explores how to retrieve times series dataset, visualizing visualizaing based on trends, how to transform dataset into times series, testing if the time series is stationary or not using Dickey-Fuller test statistic methods, how to transform time series to stationary, how to find optimal parameters to build seasonal Autoregressive Integrated Moving Average (SARIMA) model using grid search method, diagnosing time series prediction, validating the predictive power, forecasting 10 year future CO2 emission from power generation using natural gas.
     
*** TABLE OF CONTENTS:-
    
**    1. INTRODUCTION

       2. IMPORTING NECESSARY LIBRARIES
       
       3. DATA PREPROCESSING
       
        3.1 HANDLING MISSING VALUES
        
        3.2 HANDLING INCORRECT DATATYPES
        
        3.3 VISUALIZING THE PLOT TRENDS
        
       4. Coal Electric power sector CO2 Emmission Analysis
       
       5. CHECKING FOR STATIONARITY
       
        5.2 HANDLING SEASONALITY- Differencing
        
        5.3 Eliminating trend and seasonality: Decomposing
        
       6. AUTOREGRESSIVE MODEL
       
       7. Plotting the ACF and PACF- Finding the optimal parameter
       
       8. ARIMA MODEL
       
        8.1 ARIMA MODEL- EVALUATION
        
       9. SARIMAX MODEL
       
        9.1 Grid Search - To find the optimal p,d,q value
        
        9.2 Validation Prediction
        
       10. FORECASTING
       
       
       
       
     
       
