#                  portfolio
# [Project 1:NYC Taxi Fare Estimation Analysis](https://github.com/Shanis185/automati_data.git)
This project is part of the Google Advanced Data Analytics course, developed in collaboration with Automatidata, a fictional data consulting firm. The client, the New York City Taxi and Limousine Commission (TLC), aims to build a data-driven app that enables riders to estimate taxi fares in advance. This repository documents the process and outcomes of exploratory data analysis (EDA), data cleaning, and visualization conducted on the NYC TLC dataset. Future stages will develop a regression model to improve fare predictions.

## Project Overview
The primary objective of this project is to prepare the NYC TLC dataset for effective analysis by:

Conducting data cleaning and joining
Extracting key variables
Generating preliminary insights and visualizations
Providing an executive summary for Automatidata's internal stakeholders
This README also provides details on project goals, key findings, methods, and next steps.

## Table of Contents
Project Setup
Data Summary
Methods
Exploratory Data Analysis (EDA)
Descriptive Statistics
Hypothesis Testing
Results
Visualizations
Executive Summary
Next Steps
Contributors
## Project Setup
Install Required Libraries

Pandas
Matplotlib / Seaborn
Statsmodels
Scikit-learn
Load Data
The NYC TLC dataset is loaded into a structured DataFrame for organized analysis.

## Data Summary
### NYC TLC Dataset
The dataset includes information about taxi trip records, such as:

pickup_datetime and dropoff_datetime
pickup_location and dropoff_location
trip_distance
fare_amount, extra, mta_tax, tip_amount, and total_amount
### Project Goal
To build an app that provides fare estimates, enabling riders to calculate estimated fares based on trip details.

## Methods
### Exploratory Data Analysis (EDA)
The initial stage involves exploring the dataset, identifying data anomalies, missing values, and understanding key variables such as distance, fare components, and other trip details.

### Descriptive Statistics
Summary statistics are calculated to provide an overview of each variable, highlighting distributions and potential outliers.

### Hypothesis Testing
Using statistical hypothesis testing to validate assumptions about fare-related factors, which may enhance predictive accuracy in later regression modeling stages.

## Results
### Visualizations
Key visualizations created for internal stakeholders include:

Distribution of fares
Trip distance analysis
Fare breakdown by location and time
#### some of my visulaizations  ![](https://raw.githubusercontent.com/Shanis185/automati_data/db5bf72370dbb9fda05941e808e428bd7edd9434/image/Screenshot%202024-11-15%20140735.png)
![](https://raw.githubusercontent.com/Shanis185/automati_data/db5bf72370dbb9fda05941e808e428bd7edd9434/image/Screenshot%202024-11-15%20140717.png)
![](https://raw.githubusercontent.com/Shanis185/automati_data/db5bf72370dbb9fda05941e808e428bd7edd9434/image/Screenshot%202024-11-15%20140633.png)

### Executive Summary
An executive summary is provided for Automatidata's internal team, covering insights gained from EDA, key variables for fare estimation, and initial recommendations.


# [Project 2:Lightning Strike Data Analysis Dashboard - Tableau Project](https://github.com/Shanis185/TABLEAU.git)
This project is part of the Google Advanced Data Analytics course. The goal of this project is to analyze and visualize lightning strike counts in the United States using Tableau. The dataset contains four key columns: latitude, longitude, date, and lightning strike counts, where each row represents the total lightning strike count for a specific date and location.

The project includes creating a dynamic dashboard with two interactive worksheets and a set of filters for a detailed exploration of the data.

## Project Overview
This dashboard is designed to provide insights into lightning strike patterns across the United States by displaying the data using two bar graphs:
## some tableau visuals  ![](https://raw.githubusercontent.com/Shanis185/TABLEAU/95db8110ead5e12890596b7d33efe95d16108f18/images/Screenshot%202024-11-15%20150629.png)
![](https://raw.githubusercontent.com/Shanis185/TABLEAU/95db8110ead5e12890596b7d33efe95d16108f18/images/Screenshot%202024-11-15%20150653.png)
![](https://raw.githubusercontent.com/Shanis185/TABLEAU/95db8110ead5e12890596b7d33efe95d16108f18/images/Screenshot%202024-11-15%20150707.png)


## Tools Used
Tableau: For data visualization and dashboard creation.
Data Cleaning: Tableau’s data preparation tools were used to clean and structure the dataset for visualization.

# [Project 3:Ride-Sharing Fare Prediction: Trip Data Analysis and Regression Modeling](https://github.com/Shanis185/multi_regression.git)
## Overview
This project analyzes and predicts ride-sharing fare amounts in a metropolitan city using the 2017 Ride-Sharing Trip Data. The goal is to predict fare based on factors like trip distance, duration, passenger count, and tolls. Key data science techniques such as data preprocessing, exploratory data analysis (EDA), and regression modeling were used to build an accurate predictive model.

### Dataset
The dataset includes the following features:

trip_distance: Distance traveled (miles)
duration: Duration of the ride (minutes)
fare_amount: Total fare for the ride
passenger_count: Number of passengers
tolls_amount: Total tolls
pickup_datetime: Pickup time
dropoff_datetime: Drop-off time
Data Preprocessing
Key preprocessing steps:


### Data Cleaning
Converted pickup_datetime and dropoff_datetime to datetime format and calculated duration.
### Exploratory Data Analysis (EDA)
Visualized distributions using boxplots, and performed correlation analysis on key features.
### Outlier Detection & Handling
Capped or replaced extreme outliers in fare_amount and duration.
### Model Building
Built a linear regression model using selected features (trip_distance, duration, passenger_count, tolls_amount).
### Model Evaluation
Evaluated the model using metrics like R², MAE, and RMSE.
## Key Results
Feature Importance: trip_distance and duration are key predictors of fare.
Model Performance: The model achieved an R² of 0.868, explaining 86.8% of fare variance.
Outlier Handling: Improved model accuracy by managing outliers.
## Tools Used
Python: For data analysis and modeling
Pandas, NumPy, Matplotlib, Seaborn: For data manipulation and visualization
Scikit-learn: For machine learning modeling and evaluation

![](https://raw.githubusercontent.com/shanis185/multi_regression/main/images/Screenshot%202024-12-17%20234633.png)


