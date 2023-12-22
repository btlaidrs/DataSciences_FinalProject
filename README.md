# Data Science Final Project: Exploring Relationships Between Renewable Energy Consumption And Various Economical And Environmental Indicators Worldwide


**Author:** Batool Alaidaroos

**Date:** 2023-12-20

## Overview

This project explores the intricate relationships between renewable energy consumption and various economical and environmental indicators across countries. The analysis encompasses data from 2000 to 2021, covering aspects such as CO2 emissions, access to electricity, and energy depletion.



## Libraries

- **tidyverse**: For data manipulation and visualization
- **readr**: For reading CSV files
- **caret**: For data preprocessing
- **RANN**: For k-nearest neighbors imputation
- **reshape2**: For data reshaping
- **randomForest**: For creating a correlation matrix
- **gridExtra**: For arranging plots in a grid
- **sf**: For spatial data manipulation and plotting

## Loading Data

Read CSV files containing data on renewable energy consumption, CO2 emissions, access to electricity, economic growth, energy depletion, and regions (including income level).

All of the .csv files are provided in the data folder of this project, in addition to the shape file of the world map that has been used in question 5.



## Data Preprocessing

- Sliced the data from 2000 to 2021
- Pivoted the data to long format for better analysis
- Merged datasets on Country_Name and year
- Cleaned data by removing rows with missing values
- Imputed missing values using k-nearest neighbors imputation



## Data Analysis

### Question 1

Explored the relationship between economic growth, renewable energy consumption, CO2 emissions, access to electricity, energy depletion, and income level across countries.

### Question 2

Examined the distribution of renewable energy consumption among different income levels and compared it to the distribution of access to electricity across income levels.

### Question 3

Analyzed the correlation between renewable energy consumption and various environmental and economic factors, including CO2 emissions and access to electricity.

### Question 4

Investigated how the mean energy depletion and mean renewable energy consumption vary across different income levels.

### Question 5

Explored the spatial variation of environmental and economic indicators, such as CO2 emissions, access to electricity, and renewable energy consumption, across different countries.

### Question 6

Built a machine learning model (Random Forest) to predict renewable energy consumption based on other variables. Evaluated model performance and assessed agreement between predictions and actual values using a confusion matrix.



## Conclusion

This comprehensive analysis provides valuable insights into the relationships between renewable energy consumption, economic growth, and environmental indicators. The findings contribute to our understanding of the complex interplay between these factors and provide a basis for informed decision-making in the realm of sustainable development.