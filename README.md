# Heart Disease Prediction

## Overview
This project aims to analyze and predict the risk of cardiovascular disease (CVD) based on various health parameters using machine learning techniques. The dataset used for this project contains information about the various health factors of individuals.

## Dataset

### Source:

 * Dataworld:https://data.world/kudem/heart-disease-dataset/workspace/file?filename=heart_data.csv
 * No of records 70,000 and 13 columns

### Features:

 * id – Unique identifier for each record
 * age – Age in days
 * gender – Gender (1 = Female, 2 = Male)
 * height – Height in cm
 * weight – Weight in kg
 * ap_hi – Systolic blood pressure
 * ap_lo – Diastolic blood pressure
 * cholesterol – Cholesterol level (1 = Normal, 2 = Above Normal, 3 = Well Above Normal)
 * gluc – Glucose level (1 = Normal, 2 = Above Normal, 3 = Well Above Normal)
 * smoke – Smoking status (0 = No, 1 = Yes)
 * alco – Alcohol intake (0 = No, 1 = Yes)
 * active – Physical activity (0 = No, 1 = Yes)
 * cardio – Presence of cardiovascular disease (0 = No, 1 = Yes)-Target variable

## Steps used:

 * Data Collection & Cleaning
 * Exploratory Data Analysis (EDA)
 * Feature Engineering
 * Model building
 * Model Evaluation
 * Regularization
 * Hyperparameter tuning 
 * Pipeline Implementation
 * Test with unseen data

## Libraries used:

 * pandas
 * numpy
 * matplotlib
 * seaborn
 * scikit-learn

## About the project

In this project, we developed a machine learning model to predict the presence of cardiovascular disease using patient health data. We began by loading and exploring the dataset to understand its structure and identify key features. As part of data preprocessing,we applied capping for handling outliers, standardized the features using StandardScaler and converted the age values from days to years for clarity. To enhance model performance, we applied SelectKBest for feature selection, retaining only the most 8 relevant attributes and developed the model.we evaluated the model performance and applied regularization technique on models to prevent overfitting, found GradientBoosting as the best model,performed hyperparametertuning on this to increase its performance. We then built a predictive pipeline using a GradientBoostingClassifier, optimizing its parameters to improve accuracy. Additionally, we prepared an "unseen" dataset  simulating real-world test conditions. The trained model was used to make predictions on this unseen data, demonstrating its ability to generalize and potentially assist in early detection of cardiovascular risk.

## Results

 * Best performing model: GradientBoostingClassifier
 * Accuracy: 73.82%




















 
 
