# Solar Charge Predictor

The aim of this notebook is to used the historical data extracted from the solar inverter installed at the authors home and match that to historical weather data for the location of the solar installation. 

The solar data and weather data are available within this git. 

The tool developed to download the energy data from the solar inverter can be found at [LuxPower Downloader](https://github.com/chriswright757/LuxPower_Downloader)

This project is of interest because if it is possible to predict the quantity of solar energy that will be produced during the next day it means the smarter charging strategies can be implemented which can take advantage of low cost electricity and save the home owner money. 

## Notebook Structure

To make it easier to follow the data manipulation and testing of different models each part has been broken down into a separate notebooks. 

## Notebooks for merging data and assessment

- Extracting solar data from raw files and merging with historical weather data to produce a day averaged data set - [Merge_Solar_Data.ipynb](https://github.com/chriswright757/solar_charge_predictor/blob/main/Merge_Solar_Data.ipynb)
- Assessing correlation between weather data and solar production - [Plotting_Correlation.ipynb](https://github.com/chriswright757/solar_charge_predictor/blob/main/Plotting_Correlation.ipynb)

## Models Evaluated

A number of different models have been considered and tested for this data set:

| Algorithm |  Link |
|----------|---------|
| Polynomial Regression    | [Polynomial_Regression_Model.ipynb](https://github.com/chriswright757/solar_charge_predictor/blob/main/Polynomial_Regression_Model.ipynb)   
| Decision Tree Regression |[Decision_Tree_Model.ipynb](https://github.com/chriswright757/solar_charge_predictor/blob/main/Decision_Tree_Model.ipynb)|
| Decision Tree Classification |[Decision_Tree_Model.ipynb](https://github.com/chriswright757/solar_charge_predictor/blob/main/Decision_Tree_Model.ipynb)   |
| XGB Classifier |[XGBoost_Model.ipynb](https://github.com/chriswright757/solar_charge_predictor/blob/main/XGBoost_Model.ipynb)|
| Auto-Regression |[Auto_Regression_Model.ipynb](https://github.com/chriswright757/solar_charge_predictor/blob/main/Auto_Regression_Model.ipynb)|





