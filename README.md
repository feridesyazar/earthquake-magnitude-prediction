# 🌍 Earthquake Magnitude Prediction

A simple Machine Learning project to estimate earthquake **magnitude** using historical earthquake data

We compare four models: **Linear Regression**, **Decision Tree**, **Random Forest**, and **Gradient Boosting**

This is a supervised learning **Regression** project, not an earthquake early warning or forecasting system

## Project Overview

- **Features (x):** Year, Month, Latitude, Longitude, Depth
- **Target (y):** Magnitude
- **Models:** Linear Regression, Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor
- **Metrics:** MAE, RMSE, R²

## Workflow

Data Exploration (EDA) → Data Preparation → Train/Test Split → Model Training → Evaluation → Visualization

## Results

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 0.314 | 0.422 | 0.004 |
| Decision Tree | 0.303 | 0.413 | 0.047 |
| **Random Forest** | **0.300** | **0.410** | **0.062** |
| Gradient Boosting | 0.301 | 0.410 | 0.058 |

**Random Forest** performed slightly better than the other models

However, the low R² score shows that the models have limited predictive power. More geological and seismic data would be needed for more reliable predictions

## Data Source & Inspiration

- [USGS Earthquake Database (Kaggle)](https://www.kaggle.com/datasets/usgs/earthquake-database) - significant earthquakes, 1965–2016.
- [Aman Kharwal — Earthquake Prediction Model with Machine Learning](https://amanxai.com/2020/11/12/earthquake-prediction-model-with-machine-learning/)

*Note: The dataset is historical
