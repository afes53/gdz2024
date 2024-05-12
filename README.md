# Gdz Elektrik Datathon: Unplanned Power Outage Prediction
## Overview
Welcome to the repository for the Gdz Elektrik Datathon! This project focuses on predicting the number of unplanned power outages at the district level, utilizing a variety of meteorological data and special day information. Our team achieved a ranking of 34th out of 184 teams, placing us in the top 18% with an MAE score of 1.81071.

## Table of Contents
  Project Description
  Data
  Features
  Model
  Results
  Contributors
  Acknowledgements
  
## Project Description

Electricity distribution companies aim to ensure the continuity and quality of energy. This competition tasked data scientists with predicting the number of unplanned outages in GDZ's service areas. The project involved developing a model to predict daily unplanned outage counts at the district level using meteorological data and special day information.

## Data

The dataset includes:

Weather Data: Information on temperature, wind speed, wind direction, cloud cover, solar radiation, humidity, and precipitation probability.
Holiday Data: Details of holidays and special days.
Outage Data: Historical data on unplanned power outages.

## Features

Key features engineered for the model include:

Weather Interaction Features: Combinations of wind speed, precipitation probability, and solar radiation.
Dew Point Analysis: Dew point, its gradient, and interactions with other weather variables.
Gust Analysis: Examination of wind gust impacts.
Temperature Anomalies: MACD-based calculation of temperature anomalies.
Wind Speed Anomalies: MACD-based calculation of wind speed anomalies.

## Model

We utilized LightGBM for regression, leveraging its efficiency and capability to handle large datasets with complex interactions.

## Preprocessing Steps

Weather Data Preprocessing: Creation of delta and interaction features.
Feature Engineering: Development of anomalies and interaction features.
Data Aggregation: Aggregation of weather data to daily level.
Merging Datasets: Combining weather, outage, and holiday data.
Categorical Encoding: Encoding categorical features for the model.

## Results

Ranking: 34th out of 184 teams
MAE Score: 1.81071

# Acknowledgements

A big thank you to Gdz Elektrik for organizing this enriching datathon and providing such a valuable learning experience!
