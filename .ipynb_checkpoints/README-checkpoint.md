# Assignment 11.1 What drives the price of a used car?

## Overview
 In this project we looked at the dataset provided, which contains the prices for 426k used cars, to determine which factors are most important to determine the price of a used car. Based on the methods studied in class, so far, we try to build a variety of different linear models and try to determine the best model for predicting the price, using test data and cross-validation.

 In order to frame the task, and guide our research, we use the CRISP-DM framework which is a standard process in industry for data projects

## Business and Data Understanding
The first step was to determine the business goal of this project, which is to infer the drivers of price for a used car. Next, we familarize ourselves with the data provided. 

The dataset contains a lot of different features for the cars, such as the manufacturer and model of the car, the year of manufacture, odometer reading, condition, size, and so on. After cleaning the data, which involves removing observations with extreme data points, we explore the relationship of price with different variables. 

<img src="images/hist_price.png" alt="histogram_prices" width="600"/>

#### Few visualizations for relationship between features and prices

<img src="images/px_year_odometer.png" alt="year_odometer" width="600"/>
<img src="images/px_fuel_condition_drive.png" alt="other_features" width="600"/>

## Data Processing

<img src="images/pipe_process.png" alt="processig" width="600"/>

## Model and Evaluation

## Conclusion and Next Steps


## Link to Notebook
All these steps and results are further eloborated upon in the attached jupyter-notebook: [Notebook](car_price_drivers.ipynb)

