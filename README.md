# Load-Shortfall-Regression-Case-Study

The government of Spain is considering an expansion of it's renewable energy resource infrastructure investments. As such, they require information on the trends and 
patterns of the countries renewable sources and fossil fuel energy generation. Your company has been awarded the contract to:

- 1. analyse the supplied data;
- 2. identify potential errors in the data and clean the existing data set;
- 3. determine if additional features can be added to enrich the data set;
- 4. build a model that is capable of forecasting the three hourly demand shortfalls;
- 5. evaluate the accuracy of the best machine learning model;
- 6. determine what features were most important in the model’s prediction decision, and
- 7. explain the inner working of the model to a non-technical audience.

Formally the problem statement was given to you, the senior data scientist, by your manager via email reads as follow:

> In this project you are tasked to model the shortfall between the energy generated by means of fossil fuels and various renewable sources - for the country of Spain. 
> The daily shortfall, which will be referred to as the target variable, will be modelled as a function of various city-specific weather features such as `pressure`,
>  `wind speed`, `humidity`, etc. As with all data science projects, the provided features are rarely adequate predictors of the target variable. As such, you are 
>  required to perform feature engineering to ensure that you will be able to accurately model Spain's three hourly shortfalls.