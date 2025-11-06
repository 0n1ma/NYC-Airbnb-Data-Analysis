# NYC-Airbnb-Data-Analysis
This project explores the relationship between Airbnb listing prices and NYC property sale prices across the boroughs. These two datasets were used to examine how factors like location, property value, and listing characteristics influence short-term rental pricing.

# Objectives
- Analyze how average property sale prices correlate with Airbnb listing prices across boroughs
- Identify key variables that significantly affect Airbnb prices
- Build multiple linear regression models to predict Airbnb prices
- Visualize pricing patterns in terms of geography and statistics

# Datasets
- Airbnb NYC 2019 Dataset: Kaggle
- NYC Property sales Dataset: NYC Department of Finance, Rolling Sales Data

# Data Cleaning 
- Removed missing and duplicate entries
- Filtered listings with zero or invalid values
- Converted data types
- Standardized texts and corrected any inconsistencies
- Removed outliers using IQR

# Analysis
- Descriptive statistics and data distributions
- Correlation analysis between Airbnb price and property sale price
- Merging datasets by bororugh to connect real estate values with rental pricing
- Regression analyses: Linear Regression, Model evaluation with R^2, MAE, and RMSE

# Visualizations
- Airbnb price vs. average property sale price
- Price distribution by borough
- Geographic price distribution
- Correlation heatmap of numerical features
- Regression residual and preidction plots

# Insights
- Airbnb prices show moderate correlation with local property sale prices
- Borough is the strongest predictor of listing price
- Listings with higher availability and review counts are more competitively priced
- Manhattan has the highest average Airbnb and property sale prices compared to the other boroughs
