Algerian Forest Fires Prediction
Problem Statement
The objective of this project is to predict the Fire Weather Index (FWI) for the Bejaia and Sidi Bel-abbes regions in Algeria. FWI is a crucial indicator of fire danger, influenced by various weather parameters such as temperature, humidity, wind speed, and precipitation. By leveraging regression algorithms, our goal is to develop predictive models that can accurately forecast FWI based on these weather factors and FWI components (FFMC, DMC, DC, ISI, BUI).

Dataset Information
The dataset contains historical data spanning from June to September 2012, comprising weather observations and corresponding FWI values for both regions. It includes 244 instances, with 122 instances per region, classified into "fire" and "not fire" classes. Key attributes include:

Date: Date of observation
Temp: Noon temperature (max) in Celsius
RH: Relative Humidity in %
Ws: Wind speed in km/h
Rain: Total daily precipitation in mm
FWI Components: FFMC, DMC, DC, ISI, BUI
FWI: Fire Weather Index (target variable)
Dataset Columns
Date: Date of observation
Temp: Noon temperature (max) in Celsius
RH: Relative Humidity in %
Ws: Wind speed in km/h
Rain: Total daily precipitation in mm
FFMC: Fine Fuel Moisture Code
DMC: Duff Moisture Code
DC: Drought Code
ISI: Initial Spread Index
BUI: Buildup Index
FWI: Fire Weather Index (target variable)
Classes: Fire and not Fire classes
Repository Contents
Notebooks: Contains Jupyter notebooks for EDA, feature engineering, model development, and evaluation.
Data: Links to the cleaned dataset "Algerian_forest_fires_cleaned.csv".
Models: Pickle files of trained regression models for predicting FWI.
README.md: Overview of the project, dataset, and instructions for replication.
Getting Started

To replicate or explore this project:

Clone this repository to your local machine.
Download the cleaned dataset from the provided link.
Use Jupyter notebooks to run and modify the code for EDA, model training, and evaluation.
Ensure dependencies are installed (numpy, pandas, scikit-learn, etc.).
Usage
EDA: Explore data distributions, correlations, and insights.
Feature Engineering: Transform data for model compatibility.
Model Development: Train regression models to predict FWI.
Evaluation: Assess model performance using metrics like R2 Score, MAE, MSE, and RMSE.
Contributors
Carlos Rey Pinto (@carlosrey6) - Project Manager and Data Scientist
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
