# portfolio
# [NYC Taxi Fare Estimation Analysis - Automatidata Project](https://github.com/Shanis185/automati_data.git)
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
#### some of my visulaizations ![](image/Screenshot 2024-11-15 140416.png)
### Executive Summary
An executive summary is provided for Automatidata's internal team, covering insights gained from EDA, key variables for fare estimation, and initial recommendations.
