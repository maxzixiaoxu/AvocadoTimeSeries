# AvocadoTimeSeries

Supervised machine learning model for forcasting average avocado price for the next week.

## Feature selection and Feature Engineering

EDA is performed and analysis is used to encode, select, and engineer feature. 

## Preprocessing
Preprocessor transformer includes pipelines with Imputer, Scaler, OHE, PolynomialFeatures.

## Machine learning models
A baseline model is created that uses the most recent past timepoint as the predicted point. 
Ridge and RandomForestRegressor approaches are examined.

## Testing the model
The model is tested on $R^2$ score. 
