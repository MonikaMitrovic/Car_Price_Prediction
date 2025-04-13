# Car Price Prediction 
A machine learning project for predicting car prices based on various vehicle attributes.  
The goal of the project is to build models that can accurately predict a car’s MSRP (Manufacturer's Suggested Retail Price) using its characteristics.

# Features used:
Make– car manufacturer (brand)
Model – specific model of the car
Year – year of production
Engine Fuel Type – fuel type (gasoline, diesel, electric, etc.)
Engine HP – engine horsepower
Engine Cylinders – number of cylinders
Transmission Type – manual or automatic (etc.)
Driven Wheels – drive type (FWD, RWD, AWD)
Number of Doors – number of vehicle doors
Market Category – market segment (luxury, sports, SUV, economy, etc.)
Vehicle Size – size class of the vehicle
Vehicle Style – body type (sedan, coupe, hatchback, SUV, etc.)
Highway MPG / City MPG – fuel efficiency
Popularity – popularity score
MSRP – target variable (price)

# Project Approach:
1. Manual Linear Regression:  
   In the first phase, I implemented linear regression step by step, without using the scikit-learn library.
   This included data normalization, coefficient calculation, prediction logic, and evaluation (RMSE, MAE).

2. Random Forest Regression (with sklearn): 
   In the second part, I used the `RandomForestRegressor` from the `scikit-learn` library to build a more advanced model.  
   The model was trained on the training set, evaluated using R², RMSE, MAE, and then tested on real examples from the test set.

Technologies: 
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn (for data visualization)
- scikit-learn
- Jupyter Notebook

The models successfully predicted car prices with satisfying accuracy.  
The Random Forest model significantly outperformed the manually implemented linear regression, thanks to its ability to capture nonlinear relationships and feature interactions.
