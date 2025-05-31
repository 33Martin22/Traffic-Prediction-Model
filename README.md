Traffic Congestion Prediction Model

Overview

This repository contains a machine learning model built to predict traffic congestion conditions using a dataset of traffic-related features. The model is developed in Python using Google Colab and leverages libraries such as scikit-learn, pandas, and imbalanced-learn for data preprocessing, feature engineering, and classification. The primary goal is to predict traffic conditions (e.g., Light, Moderate, Heavy) based on features like vehicle count, traffic speed, weather conditions, and time-based attributes.

Dataset

The dataset (smart_mobility_dataset.csv) includes features such as:





Vehicle_Count: Number of vehicles on the road.



Traffic_Speed_kmh: Average speed of traffic in km/h.



Road_Occupancy_%: Percentage of road occupancy.



Traffic_Light_State: State of traffic lights (e.g., Green, Red).



Weather_Condition: Weather conditions (e.g., Clear, Rain, Fog).



Accident_Report: Presence or absence of accident reports.



Timestamp: Date and time of the observation.

Derived features include:





Hour: Hour of the day extracted from the timestamp.



DayOfWeek: Day of the week extracted from the timestamp.
