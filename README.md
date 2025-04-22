# Airline-Passenger-Satisfaction Prediction 
## Objective
To help airlines identify key factors influencing customer satisfaction and predict satisfaction levels using machine learning. Improving these factors can directly impact customer retention, reputation, and overall business growth.

## Dataset Overview
- Sourced from Kaggle (airline customer satisfaction survey)
- 103,904 records (train), 25,976 records (test)
- 25 features including Age, Gender, Travel Class, Flight Delays, and Service Ratings
- Target variable: satisfaction – “satisfied” or “neutral or dissatisfied”

## Project Structure
- **Data Cleaning & Preprocessing**: handling Missing Values, feature engineering (e.g, age groups, service averages).
- **EDA**: Visual exploration of satisfaction trends across travel types, service quality, and delays.
- **Modeling**: Built and compared two classification models:
  - Random Forest
  - LightGBM
- **Evaluation**: Accuracy, F1-Score, Confusion Matrix, ROC-AUC.

## Problem Statement
The airline industry faces challenges in maintaining high customer satisfaction levels due to varying passenger experiences with flight services and amenities. Understanding the factors driving dissatisfaction is crucial to improving service quality.

## Key Insights
- Dissatisfaction is highly linked to In-flight comfort, delays and service ratings.
- LightGBM slightly outperformed Random Forest (ROC-AUC: 0.95 vs 0.94).
- Targeted improvement in Wifi, entertainment, and Delay management could boost satisfaction.

## Conclusion
Random Forest and LightGBM both performed well. However, LightGBM was fast, making it the final chosen model.
