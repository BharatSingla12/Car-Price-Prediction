## About the data 
With the rise in the variety of cars with differentiated capabilities and features such as model, production year, category, brand, fuel type, engine volume, mileage, cylinders, colour, airbags and many more, we are bringing a car price prediction challenge for all. We all aspire to own a car within budget with the best features available. 

Attribute Information:

- ID
- Price: price of the care(Target Column)
- Levy
- Manufacturer
- Model
- Prod. year
- Category
- Leather interior
- Fuel type
- Engine volume
- Mileage
- Cylinders
- Gear box type
- Drive wheels
- Doors
- Wheel
- Color
- Airbags


## App for the ML Model:
https://car-cost-prediction-app.herokuapp.com/


## ML Model Conclusion:
- The Random forest model with n_estimators = 500 and Gradient boosting with max_depth=10, n_estimators=150 both gives R² of 0.80 on the test data. 
- The Random forest is relatively better than Gradient boosting as MAE of random forest is lower than Gradient boosting on the test dataset.
- For both the models the top 10 features in descending orders are:
   -   Production year 
   -   Airbags 
   -   Mileage 
   -   Levy
   -   Engine volume 
   -   Fuel type diesel 
   -   Model 
   -   Gearbox tiptronic
   -   Drive wheels front 
   -   Gearbox automatic
- It is quite impressive that both the random forest model and gradient bossting are two different types of ensembling technique but both giving very similar results in terms of feature importances.
