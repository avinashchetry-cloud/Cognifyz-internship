# Zomato Restaurant Data Analysis | Feature Engineering

## Project Overview
This project focuses on exploring and enhancing a restaurant dataset through Exploratory Data Analysis (EDA) and Feature Engineering.

The objective is to extract meaningful information from existing restaurant attributes, create new analytical features, and prepare the dataset for deeper analysis and visualization.

## Feature Engineering

Created 9 new features from existing dataset columns:

| Feature | Description |
|---|---|
| Restaurant Name Length | Calculates the character length of restaurant names. |
| Amount of Cuisines Offered | Counts the number of cuisines offered by each restaurant. |
| Offers Table Booking | Encodes table booking availability as a categorical/binary feature. |
| Offers Online Delivery | Encodes online delivery availability as a categorical/binary feature. |
| Currency Symbol | Extracts or maps the corresponding currency symbol. |
| Exchange Value | Assigns an exchange-rate multiplier for currency conversion. |
| INR Value | Converts restaurant costs into Indian Rupees (INR). |
| Price Category | Classifies restaurants into different pricing categories. |
| Address Length | Calculates the character length of restaurant addresses. |

## Data Transformation
- Mapped different currencies to their respective exchange-rate values.
- Standardized restaurant costs into INR for comparative analysis.
- Created price categories such as Inexpensive, Budget, Moderate, Expensive, Premium and Luxury.
- Transformed existing categorical attributes into more analysis-friendly features.

## Key Objectives
- Extract additional information from existing columns.
- Improve the analytical usefulness of the dataset.
- Transform categorical variables into meaningful features.
- Enable better comparison of restaurant pricing across different currencies.
- Prepare data for further EDA and visualization.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Outcome
Successfully engineered 9 additional features to enrich the original restaurant dataset and make it more suitable for exploratory analysis and further data-driven insights.
