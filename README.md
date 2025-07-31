# 1.Real Estate Price Prediction

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

<br>  
<br>

# 2.Image Classification model using CNN

This project demonstrates how to build and train a Convolutional Neural Network (CNN) for image classification using Python and TensorFlow/Keras. The notebook walks through all the essential steps, including data preprocessing, model building, training, evaluation, and prediction. This type of model is widely used in computer vision applications such as object recognition, face detection, and scene classification.

## Project Highlights

- Import and preprocess image datasets
- Build a CNN model using Keras Sequential API
- Apply data augmentation to prevent overfitting
- Train the model and monitor performance
- Evaluate the model on test data
- Make predictions on unseen images

## Model Architecture

A typical architecture implemented in the notebook may include:

- Convolutional Layers with ReLU activation
- MaxPooling layers
- Flatten layer
- Fully Connected (Dense) layers
- Dropout (for regularization)
- Softmax output layer for classification

## Requirements

- Python 3.7+
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook

## Results

- Accuracy and loss graphs for training and validation
- Classification accuracy on test dataset
- Sample predictions displayed along with true labels
