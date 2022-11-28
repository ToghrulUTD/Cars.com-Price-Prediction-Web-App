# Flask_Deployment_Price_Prediction
## Overview
This is a Flask web app which predicts the price of used car based on its make, model, bodystyle, mileage, year, and location.
### Data
Data has been scraped from cars.com and includes details such as make, model, bodystyle, year, mileage, location and price for more than 100000 cars. You can refer to the Jupyter notebook for more details about web scraping. 
### Methods used
For estimating the car prices, I have used Gradient Boosting Tree regression model due to highly categorical nature of the data. The model was tuned with bayesian hyperparameter optimization using Optuna. The final tuned achieves a MAPE of 0.09. Please refer to the jupyter notebook for more details.

## Demo of the Web App
<img src="static/Screen Shot 2022-11-28 at 12.48.05 AM.png">
<img src="static/Screen Shot 2022-11-28 at 12.51.47 AM.png">
