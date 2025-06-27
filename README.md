# Real Estate Price Prediction

This project is focused on predicting real estate prices using features such as location, square foots, number of bedrooms, and more. A regression model is trained to estimate housing prices based on cleaned and processed data.

## Project Overview

- Cleaned and preprocessed housing data.
- Performed exploratory data analysis (EDA).
- Built regression models for price prediction.
- Included location-based filtering and outlier removal.

## Features Used

- Location
- Total Square Feet
- Number of Bathrooms
- Number of Bedrooms (BHK)
- Price (Target Variable)

## Data Preprocessing

- Handled missing and inconsistent data.
- Converted categorical variables using one-hot encoding.
- Created new features like price per square foot.
- Removed outliers and grouped similar locations.

## Model Building

- Linear Regression as the primary model.
- GridSearchCV used for hyperparameter tuning.
- Cross-validation to ensure generalization.
- Compared performance with other regression models.

## Exploratory Data Analysis (EDA)

- Visualizations for BHK vs Price, Location vs Price.
- Identified anomalies like inconsistent pricing.
- Removed extreme values and duplicates.

## Future Improvements

- Deploy model with a web interface using Flask or Streamlit.
- Enhance dataset with more features (e.g., property age, amenities).
- Implement advanced models like Random Forest or XGBoost.

## Acknowledgements

- Dataset inspired by publicly available housing data.
- Educational project for demonstrating ML pipeline in real estate.
