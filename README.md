# House-Price-Prediction

House Price Prediction – Boston Housing Dataset
Project Overview

This project predicts median house prices in the Boston area using socio-economic, structural, and geographic features. The dataset was cleaned, preprocessed, and analyzed to develop accurate machine learning models for predicting house values.

Objective

Predict house prices based on features like crime rate, average number of rooms, socio-economic status, and more.

Identify key factors that influence housing prices.

Build robust models with high predictive accuracy.

Dataset

Source: Boston Housing Dataset (Variant)

Features:
CrimeRate, ResLandZone, IndusProp, RiverDummy, PollutionNOX, AvgRooms, OldHousePerc, DistEmploy, HighwayAccess, PropertyTax, PupilTeacher, BlackProp, LowStatusPerc

Target: HouseValue (Median value of owner-occupied homes in $1000s)

Preprocessing:

Handled outliers for key features

Verified no missing values or duplicates

Renamed columns for better interpretability

Visualizations

Feature Importance Plot – highlights which features most influence house prices.

Actual vs Predicted Plot – compares predicted prices with actual values.

Residual Distribution Plot – checks for bias and distribution of prediction errors.

Skills & Tools Used

Programming & Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Data Preprocessing: Outlier handling, feature engineering, train-test split

Modeling: Linear Regression, Random Forest Regressor

Evaluation: R² Score, RMSE, residual analysis, predicted vs actual plots

Data Analysis & Visualization: EDA, correlation analysis

Conclusion

Random Forest provides robust and accurate predictions for house prices.

Socio-economic status and average number of rooms are key drivers of pricing.

Project demonstrates the complete workflow from data preprocessing to analysis and prediction.

Future Improvements

Hyperparameter tuning for Random Forest or use Gradient Boosting / XGBoost.

Feature engineering for polynomial terms or log transformations.

Deploying the model for real-time house price prediction.
