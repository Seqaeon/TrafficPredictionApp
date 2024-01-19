# Traffic_App
https://team-scipy-traffic-predictor-ap.streamlitapp.com/
# Traffic_Analysis_and_Prediction

# Introduction

Traffic congestions is rising in cities around the world. Contributing factors include expanding urban populations, aging infrastructure, inefficient and uncoordinated traffic signal timing and a lack of real-time data. Given the physical and financial limitations around building additional roads, cities must use new strategies and technologies to improve traffic conditions.

In this project, we will analyze the provided Traffic dataset on [Kaggle](https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset). The provided dataset includes hourly traffic data on four different junctions in a particular city.


# Aim of the Project

The aim of this project is to build a model/models that can be used to predict traffic at particular times at the different junctions in the city.


# Dataset Overview

The traffic data that was used in this end-to-end project was sourced from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset) and this dataset contains 48,120 rows and 4 columns. These columns are:

**DateTime:** this contains the time at which sensors collect traffic data at the different junctions. The traffic data is collected every hour.

**Junction:** this represents the four different junctions from which the traffic data was collected.

**Vehicles:** this represents the number of vehicles at the time the sensors capture the traffic data.

**ID:** this is the unique ID of the sensors.

Because this project involves a time series analysis, more columns were engineered for quality analysis, and these columns include Year, Month, Day_of_Month, Day_of_Week, Day_of_Year, Date, Time, and Seconds.





# Model Deployment

He’s a [link](https://team-scipy-traffic-predictor-ap.streamlitapp.com/) to the deployed model. This model is used to predict the number of vehicles that will be at a particular junction at a particular date and at a particular point in time.

 
 - Requirements.txt file contains the packages and libraries used for the project with their listed versions.
 
