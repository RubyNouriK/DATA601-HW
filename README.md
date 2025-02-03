# **Data Analysis of Building Energy Benchmarking Data**

## Introduction
The purpose of this assignment was to perform an in depth-analysis on the **City of Calgary's Building Energy Benchmarking.** The goal of this analysis is to understand energy uses trends between different building types and explore energy efficiency improvements. 

## Dataset
This dataset includes information throughout several years on 
* building types
* floor area
* total energy consumption
* electricity and gas usuage
* GHG emissions
* and other key attributes

## Methodology
### Data Cleaning
* removing columns with more than 40% missing values
* filling other columns by imputing median and mode
* using regex to clean and standardize postal codes and addresses

### Exploratory Data Analysis (EDA)
* computing summary of the dataset and identifying outliers
* calculating top 5 properties with their highest total energy consumption
* using regex to format values
* computing IQR to detect outliers in total GHG emissions

### Data Visualization
* using bar charts to show the top 10 buildings with the highest GHG emissions
* using heatmaps to visualize the energy usuage across different properties

## Challenges
Some of the challenges were:
* large dataset with a high number of missing values
* making sure values are in the same format for calculation
* converting values of KwH to GJ

## Insights

