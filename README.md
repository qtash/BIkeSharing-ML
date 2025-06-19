# BikeSharing User Prediction ML Model
A machine learning model development Study Case project for forecasting service user on specific conditions. 

## Background
Bike-sharing systems are a new generation of traditional bike rentals where the whole process has become automatic. Through these systems, a user can easily rent a bike from a particular position and return back at another position. Not only the process, lots of data are explicitly recorded in Bike-sharing systems. 

### Problem
The issues with rental services is failing to fulfil the number of request of its services (because of the resource shortages, management setbacks, system failures, and other potential disaster like a bad weather). Thus, it’s important to predict the size of demands, especially on peak moment (hour/day). Identifying peak moments could also help with service providence and handling strategies.

## Goals & Strategy
Predicting Bike-sharing demands on specific condition (events availability, climate & atmospheric conditions) using RMSE, MAE, and MAPE metrics for model performance evaluation. 

### Current Best Model
Tuned XGBoost model able to achieve 66.1 MAE. 
#### Most important feature: hour (of the day of using the service)

## Conclusion & Recommendation
The current model's MAPE is still very high, further tuning, data treatment, and model performance testing could still be done to achive lower error and better machine learning prediction model. 
- Add more feature or related data
- Do more complex feature engineering or more explorative feature selection
- Do outlier treatment or add more data to broaden the interquartile area of the target
- Use more model to benchmark
- Do deeper model tuning

****
- Acknowledgement: This project is initially created for the Capstone Project of Module 3 on Purwadhika Digital School Data Science Bootcamp purposes. 
- Created by Qonita Shobrina
