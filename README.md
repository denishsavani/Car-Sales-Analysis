# Car Sales Analysis 

## Overview

This project involves the analysis of car sales data from an Excel file. The goal is to preprocess, merge, and analyze the data to derive meaningful insights using Python.

## Libraries and Setup

- **pandas**: Used for data manipulation and analysis.
- **warnings**: Used to ignore unnecessary warnings.
- **plotly.express**: Used for data visualization.

## Data Loading

1. Define the path to the Excel file: `analytics_test.xlsx`.
2. Load the Excel file and access its sheets (`car_sales`, `car_details`, `car_claims`).

## Data Preprocessing

1. Load each sheet into a separate DataFrame.
2. Drop duplicate records.
3. Rename columns for consistency.
4. Merge DataFrames on the `car_id` column.

## Data Cleaning and Transformation

1. Handle missing values appropriately.
2. Convert boolean and categorical variables to suitable data types.
3. Create additional columns for visualization by converting boolean features to string representations.

## Analysis and Visualization

1. Explore unique values of key features.
2. Visualize data using `plotly.express` to understand unique car features and refund statuses.

## How to Run

1. Ensure you have Python installed with the required libraries.
2. Place the `analytics_test.xlsx` file in the same directory as the notebook.
3. Run the notebook to see the analysis and visualizations.

## Conclusion

This case study provides a comprehensive guide for analyzing car sales data, covering all necessary steps from data loading to visualization. The methods and techniques demonstrated can be applied to similar datasets for effective data analysis.
