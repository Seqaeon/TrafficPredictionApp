# Traffic_App
https://team-scipy-traffic-predictor-ap.streamlitapp.com/
# Traffic_Analysis_and_Prediction

# Introduction

Traffic congestions is rising in cities around the world. Contributing factors include expanding urban populations, aging infrastructure, inefficient and uncoordinated traffic signal timing and a lack of real-time data. Given the physical and financial limitations around building additional roads, cities must use new strategies and technologies to improve traffic conditions.

In this project, we will analyze the provided Traffic dataset on [Kaggle](https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset). The provided dataset includes hourly traffic data on four different junctions in a particular city.


# Aim of the Project

The aim of this project is to derive insights from this analysis and then build a model/models that can be used to predict traffic at particular times at the different junctions in the city.


# Dataset Overview

The traffic data that was used in this end-to-end project was sourced from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset) and this dataset contains 48,120 rows and 4 columns. These columns are:

**DateTime:** this contains the time at which sensors collect traffic data at the different junctions. The traffic data is collected every hour.

**Junction:** this represents the four different junctions from which the traffic data was collected.

**Vehicles:** this represents the number of vehicles at the time the sensors capture the traffic data.

**ID:** this is the unique ID of the sensors.

Because this project involves a time series analysis, more columns were engineered for quality analysis, and these columns include Year, Month, Day_of_Month, Day_of_Week, Day_of_Year, Date, Time, and Seconds.


# Summary of Findings

 - There has been an upward trend of vehicles yearly in all four junctions with junction 1 having the highest upward trend
 
 - I notice an increase in the first and third junctions around the month of June, this might be due to summer activities that happen around that time.
 
 - I notice a daily increase in Vehicular movement in all the junctions except junction four which started recording data in January 2017.
 
 - With the exception of junction 4, We notice the data increasing during the morning time, around 6 am, staying steady throughout the afternoon, and decreasing during the evening time around 8 pm.
 
 - I also notice that we have less traffic during the weekend and steady traffic during the weekdays.

 - Junction 4 was created to reduce the overall traffic situation on the axis which seemed to work.



# Model Deployment

He’s a [link](https://team-scipy-traffic-predictor-ap.streamlitapp.com/) to the deployed model. This model is used to predict the number of vehicles that will be at a particular junction at a particular date and at a particular point in time.


# Dashboard Report

Here's a [link](https://bit.ly/Traffic-Data-Analysis-Dashboard-by-Team-SciPy) to the dashboard report that we created at the end of this project. In these reports, we tried to visualize the insights derived from the analysis of the traffic data like which junction had the most vehicular movement at a particular time of the day, month and year.


# Instructions For Team

 - The Traffic_Prediction_EDA ipynb file contains the data wrangling, analysis and visualization proceses.
 
 - Traffic Prediction Model ipynb file containing the feauture engineering and modeling processes.
  
 - The traffic excel file contains the original data as it was obtained from Kaggle.
 
 - The traffic_processed excel file is the cleaned file that was used for the data visualizations and dashboard design.
  
 - pkl files contain the trained model for each of the junctions.
 
 - app.py contains the app deployment code.
 
 - Requirements.txt file contains the packages and libraries used for the project with their listed versions.
 
