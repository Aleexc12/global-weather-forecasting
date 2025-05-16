# Global Weather Forecasting

This repository contains an analysis and predictive modeling project based on a comprehensive global weather dataset.

## Dataset

## Dataset Description

The dataset is sourced from the [Global Weather Repository](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository) on Kaggle.

It provides daily weather information for capital cities around the world, starting from August 29, 2023. Unlike forecast datasets, this repository contains a comprehensive set of over 40 features representing current weather conditions globally.

Included variables cover temperature, wind, pressure, precipitation, humidity, visibility, air quality measurements, and more. This rich dataset is valuable for analyzing global weather patterns, exploring climate trends, and understanding relationships among various meteorological parameters.

The full dataset CSV (`GlobalWeatherRepository.csv`) is included in the `data/` folder and used throughout this project.


## Project Overview

The main goals of this project are:

- Exploratory Data Analysis (EDA) to understand data distributions, missing values, and relationships among variables.
- Data cleaning and feature selection, including removal of redundant or highly correlated columns.
- Building predictive models to forecast temperature in Celsius using various algorithms such as Random Forest, XGBoost, and LightGBM.
- Hyperparameter tuning to optimize model performance.
- Model interpretation using permutation importance to identify key features influencing temperature predictions.

## Notebook Walkthrough

The Jupyter notebook `GlobalWeather.ipynb` guides you through the complete workflow:

1. **Data Loading and Preprocessing:** Loading the CSV dataset, basic cleaning, and handling missing values.
2. **Exploratory Data Analysis:** Visualizations and statistics to understand variable distributions, seasonal patterns, and geographic variation.
3. **Correlation Analysis:** Identifying and removing redundant variables based on correlation matrices.
4. **Modeling:** Training initial regression models, including Random Forest and XGBoost, with performance evaluation using RMSE and MAE.
5. **Hyperparameter Tuning:** Using grid search and cross-validation to optimize model parameters.
6. **Model Interpretation:** Applying permutation importance to understand the influence of different features on model predictions.
7. **Final Model Training and Evaluation:** Training the final optimized model and evaluating its performance on a validation set.

For further details, please refer to the notebook itself, which contains full code, plots, and detailed comments.

---

Feel free to ask if you want me to add sections like Installation, How to Run...
