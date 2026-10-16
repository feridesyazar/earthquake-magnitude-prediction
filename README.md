# 🌍 Earthquake Magnitude Prediction

A simple Machine Learning project to estimate earthquake **magnitude** using historical earthquake data.

We compare **Linear Regression** and **Gradient Boosting** in a supervised learning **regression** task. This is an educational project, **not an earthquake early warning or forecasting system**.

**Dataset:** [USGS Earthquake Database on Kaggle](https://www.kaggle.com/datasets/usgs/earthquake-database) — significant earthquakes, 1965–2016.

## Project Overview

- **Features (X):** Year, Month, Latitude, Longitude, Depth
- **Target (y):** Magnitude
- **Models:** Linear Regression, Gradient Boosting Regressor
- **Metrics:** MAE, RMSE, R²

## Workflow

Data Exploration (EDA) → Data Preparation → Train/Test Split → Model Training → Evaluation → Visualization

## How to Run

1. Download or clone the repository.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Place `database.csv` in the same folder as the notebook.
4. Open `Earthquake_Magnitude_Prediction.ipynb` in Jupyter Notebook and run all cells.

## Results

In our initial notebook evaluation, Gradient Boosting performed slightly better than Linear Regression, but predictive performance was limited (R² around **0.06**). The date, location and depth features alone do not allow reliable prediction of earthquake magnitude.

## Data Source & Inspiration

- [USGS Earthquake Database (Kaggle)](https://www.kaggle.com/datasets/usgs/earthquake-database)
- [Aman Kharwal — Earthquake Prediction Model with Machine Learning](https://amanxai.com/2020/11/12/earthquake-prediction-model-with-machine-learning/)

*Note: The dataset is historical. Reported test scores come from a random train/test split, not a future-earthquake forecasting evaluation.*
