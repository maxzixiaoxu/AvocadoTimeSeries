# AvocadoTimeSeries

Supervised machine learning model for forcasting average avocado price for the next week.

## Feature Selection and Feature Engineering

EDA is performed and analysis is used to encode, select, and engineer features. 

## Preprocessing
Preprocessor transformer includes pipelines with Imputer, Scaler, OHE, PolynomialFeatures.

## Machine Learning Models
A baseline model is created that uses the most recent past timepoint as the predicted point. 
Ridge and RandomForestRegressor approaches are examined.

## Testing the Model
The model is tested on $R^2$ score. 
