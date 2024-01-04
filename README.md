# Load-Shortfall-Regression-Case-Study

This is a regression task and the metric used for this project is Root mean squared error.
The project is based on the  government of Spain which is considering an expansion of its renewable energy resource infrastructure investments. As such, they require information on the trends and patterns of the country's renewable sources and fossil fuel energy generation.
The goal of this project was to analyse the supplied data;
* Identify potential errors in the data and clean the existing data set;
* Determine if additional features can be added to enrich the data set;
* Build a model that is capable of forecasting the three hourly demand shortfalls;
* Evaluate the accuracy of the best machine learning model;
* Determine what features were most important in the model’s prediction decision, and
* Explain the inner workings of the model to a non-technical audience.

Some major insights I found include:
* The dataset contained weather information for 5 cities in Spain (Madrid, Barcelona, Seville, Bilbao and Valencia).
* The feature columns had a relatively low correlation with the target variable but some engineered features from the time column had a relatively higher correlation with the target variable
* The distribution of some of the variables was highly skewed but this was understandable because we were dealing with seasonal weather conditions. For instance, the snow value would be 0 for most of the year except for winter when it would have some value.
* Stacking different models together gave a better result i.e. lower root mean squared error. The model however would perform better if there was more data available with more relevant features.

You can access the full notebook [here](https://github.com/Othuke/Load-Shortfall-Regression-Case-Study/blob/main/Load%20Shortfall%20Regression.ipynb)
