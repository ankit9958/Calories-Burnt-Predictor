# Calories-Burnt-Predictor


This project predicts the number of calories burned during exercise based on user data and exercise details using an XGBoost regression model.

## Features
* Data visualization using seaborn and matplotlib
* XGBoost model for accurate calorie burn prediction
* Predictive system for estimating calorie burn based on new input data

## Installation
Ensure you have the following Python libraries installed:
* pandas (v2.1.1)
* scikit-learn (v1.3.1)
* xgboost (v2.0.1)

You can install them using pip:

## Usage
1. Load the required datasets (`calories.csv` and `exercise.csv`).
2. Preprocess and visualize the data to gain insights.
3. Train the XGBoost model on the provided dataset.
4. Use the trained model to predict calorie burn for new input data.

**Input Data Format:**
The prediction system expects input data in the following format: (Gender, Age, Height, Weight, Duration, Heart_Rate, Body_Temp)

