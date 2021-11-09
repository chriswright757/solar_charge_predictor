# Solar Charge Predictor

The aim of this notebook is to used the historical data extracted from the solar inverter installed at the authors home and match that to historical weather data for the location of the solar installation. 

The solar data and weather data are availible within this git. 

The tool developed to download the energy data from the solar inverter can be found at [LuxPower Downloader](https://github.com/chriswright757/LuxPower_Downloader)

This project is of interest because if it is possible to predict the quantity of solar energy that will be produced during the next day it means the smarter charging strategies can be implemented which can take advatage of low cost electricty and save the home owner money. 

## Notebook Structure

To make it easier to follow the data manipulation and testing of different models each part has been broken down into a seperate notebooks. 



## Models Evaluated

A number of different models have been considered and tested for this data set:

| Algorithm | Accuracy | Explanation |
|----------|----------------|---------|
| Polynomial Regression |   |    |
| Decision Tree Regression |  |   |
| Auto-Regression |   |    |
| SARIMA |    |  |
| Decision Tree Classification |    |    |
| XGB Classifier |   |   |

## Most Accurate Model Results




- Extracting solar data from raw files and merging with historical weather data to produce a day averaged data set - [Merge_Solar_Data.ipynb]()
- 


## View Rendered Notebook

**The notebook is best rendered in the browser using nbviewer at this [link](https://nbviewer.jupyter.org/github/chriswright757/solar_charge_predictor/blob/main/Solar%20Predictor_V2.ipynb).**
