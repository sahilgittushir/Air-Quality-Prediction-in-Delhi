# Air-Quality-Prediction-in-Delhi
The alarming rise in air pollution levels in Delhi presents a severe public health challenge. This project focuses on developing a sophisticated regression model to forecast the Air Quality Index (AQI) by analyzing major pollutant concentrations, including PM2.5, PM10, NO, NO2, NH3, SO2, and CO. By leveraging machine learning techniques.

Overview

The alarming rise in air pollution levels in Delhi presents a severe public health challenge. This project focuses on developing a sophisticated regression model to forecast the Air Quality Index (AQI) by analyzing major pollutant concentrations, including PM2.5, PM10, NO, NO2, NH3, SO2, and CO. By leveraging machine learning techniques, we aim to provide actionable insights for policymakers and public health officials to combat air pollution effectively.

Motivation

Delhi, one of the world's most populous cities, faces extreme air pollution due to industrial emissions, vehicular traffic, and seasonal agricultural burning. Our project seeks to address these challenges by analyzing historical data and environmental variables to predict AQI and guide interventions.

Objectives

Build regression models to predict AQI based on pollutant concentrations and meteorological factors.

Compare and analyze the performance of various regression algorithms.

Generate actionable insights to support effective policy-making and intervention strategies.

Methodology

Data Source

We utilized a robust dataset comprising:

Historical air quality measurements.

Pollutant concentration records (PM2.5, PM10, NO, NO2, NH3, SO2, CO).

Meteorological data.

Data Preprocessing

Key preprocessing steps included:

Handling missing values using mean/mode imputation and interpolation.

Feature engineering with label encoding, datetime extraction, and cyclic encoding.

Scaling data using MinMaxScaler for consistent feature contribution.

Identifying and managing outliers with IQR and Z-Score methods.

Machine Learning Models

We employed the following regression models:

K-Neighbors Regressor: Best performer with an R² of 0.9678.

CatBoost Regressor: Efficiently handles categorical features with an R² of 0.9646.

XGBoost Regressor: High speed and performance, achieving an R² of 0.9554.

LightGBM Regressor: Efficient ensemble method with an R² of 0.9342.

Bayesian Ridge Regression: Robust against overfitting, with an R² of 0.7827.

Exploratory Data Analysis (EDA)

Right-skewed distributions observed in most pollutants.

Strong positive correlations between PM2.5, PM10, and AQI.

Bimodal behavior in AQI, suggesting distinct air quality clusters.

Performance Metrics

The models were evaluated using:

Mean Squared Error (MSE).

Mean Absolute Error (MAE).

Coefficient of determination (R²).

Key Results

Model

MSE

MAE

R²

K-Neighbors Regressor

0.0098

0.0569

0.9678

CatBoost Regressor

0.0104

0.0764

0.9646

XGBoost Regressor

0.0131

0.0861

0.9554

LightGBM Regressor

0.0192

0.1051

0.9342

Bayesian Ridge

0.0637

0.1978

0.7827

Key Insights

Ensemble methods like K-Neighbors, CatBoost, XGBoost, and LightGBM provided high accuracy.

Pollution spikes and clusters were observed, emphasizing the need for targeted policies.

Feature selection using Recursive Feature Elimination identified PM2.5, PM10, NO2, and AQI as critical variables.

Contributions

Shrey Yadav: Dataset acquisition and preprocessing.

Lakshay Trehan: Exploratory Data Analysis (EDA).

Karanjeet Singh & Lakshay Trehan: Preprocessing and data cleaning.

Yash Singh & Sahil: Model training, methodology, and result analysis.

Technologies Used

Python

Libraries: Scikit-learn, XGBoost, CatBoost, LightGBM, Pandas, Matplotlib, Seaborn

Future Work

Expand the dataset to include real-time data streams.

Explore deep learning models for further improvement in AQI prediction.

References

Mahanta et al., "Urban Air Quality Prediction Using Regression Analysis," IEEE, 2019. DOI

Shukla et al., "Regression-based Flexible Models for Photochemical Air Pollutants," Chemosphere, 2021. DOI

Kumar & Goyal, "Forecasting of Air Quality in Delhi," Atmospheric Pollution Research, 2011. DOI

Gupta et al., "Prediction of Air Quality Index Using Machine Learning Techniques," Journal of Environmental and Public Health, 2023. DOI

Ganesh et al., "Forecasting Air Quality Index Using Regression Models," IEEE, 2017. DOI
