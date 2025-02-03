# **Data Analysis of Building Energy Benchmarking Data**

## Introduction
The purpose of this assignment was to perform an analysis on the **City of Calgary's Building Energy Benchmarking.** 
The goal of this analysis is to understand energy use trends between different building types and explore energy efficiency improvements. 

## Dataset
This dataset includes information from several years on 
* building types
* floor area
* total energy consumption
* electricity and gas usage
* GHG emissions
* and other key attributes

## Methodology
### Data Cleaning
* removing columns with more than 40% missing values
* filling other columns by imputing median and mode
* using regex to clean and standardize postal codes and addresses

### Exploratory Data Analysis (EDA)
* computing summary of the dataset and identifying outliers
* calculating the top 5 properties with their highest total energy consumption
* using regex to format values
* computing IQR to detect outliers in total GHG emissions

### Data Visualization
* Use bar charts to show the top 10 buildings with the highest GHG emissions
* using heatmaps to visualize the energy usage across different properties

## Challenges
Some of the challenges were:
* large dataset with a high number of missing values
* Make sure values are in the same format for calculation
* converting values of KwH to GJ

## Insights
Understanding that this analysis will help to come up with a solution in order to save energy and find better solutions for high-usage buildings. 
