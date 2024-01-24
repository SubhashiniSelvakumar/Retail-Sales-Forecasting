# Retail Sales Forecasting

## Overview

This repository contains the code and resources for a retail sales forecasting project. 
The goal of this project is to predict department-wise sales for each store for the following year, model the effects of markdowns on holiday weeks, and provide recommended actions based on the insights drawn, with prioritization placed on the largest business impact.

## Dependencies

- Python
- NumPy
- pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

##Dataset:

This is the historical sales data for 45 stores located in different regions. Each store contains a number of departments In addition, Store runs several promotional markdown events throughout the year. 

store_df.csv: This file contains anonymized information about the 45 stores, indicating the type and size of store.

sales_df.csv:

This is the historical training data, which covers to 2010-02-05 to 2012-11-01. Within this file you will find the following fields:

Store - the store number
Dept - the department number
Date - the week
Weekly_Sales - sales for the given department in the given store
IsHoliday - whether the week is a special holiday week

Feature_df.csv:

This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:

Store - the store number
Date - the week
Temperature - average temperature in the region
Fuel_Price - cost of fuel in the region
MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.
CPI - the consumer price index
Unemployment - the unemployment rate
IsHoliday - whether the week is a special holiday week

## Project Objectives

1. **Sales Prediction:**
   - Predict department-wise sales for each store for the upcoming year.
   - Utilize historical sales data, store information, and external factors for accurate forecasting.

2. **Markdown Impact Modeling:**
   - Examine the impact of markdowns on sales during holiday weeks.
   - Create features that capture the effects of markdowns and holidays on sales.

3. **Insights and Recommendations:**
   - Derive actionable insights from the analysis.
   - Provide recommended actions based on insights, focusing on maximizing business impact.
