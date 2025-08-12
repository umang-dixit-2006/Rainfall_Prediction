# Rainfall Prediction Project

## Overview
This project analyzes historical weather data for Austin, Texas, to predict precipitation levels using Linear Regression. The workflow includes data cleaning, preprocessing, exploratory analysis, model training, and visualization of relationships between weather attributes and rainfall.

## Methodology
1. Data Loading & Exploration:
   - Loaded the Austin weather dataset and explored its structure and missing values.
2. Data Cleaning:
   - Removed irrelevant columns and handled missing values or special symbols (e.g., 'T', '-').
3. Exploratory Data Analysis (EDA):
   - Visualized precipitation trends over time.
   - Explored relationships between precipitation and weather attributes using scatter plots and a correlation heatmap.
4. Modeling:
   - Built and evaluated a Linear Regression model to predict precipitation using features such as temperature, humidity, dew point, visibility, and wind speed.
   - Assessed model performance using RMSE and R² score.
   - Visualized actual vs. predicted precipitation and examined feature coefficients.

## Key Findings
- The linear regression model can predict precipitation levels based on weather attributes, with performance visualized by actual vs. predicted plots.
- Feature coefficients reveal which weather variables most influence precipitation.
- Further improvements could include advanced models, feature engineering, or more data.

## How to Run
1. Open the notebook `Rainfall_detection.ipynb` in Jupyter or VS Code.
2. Run all cells in order to reproduce the analysis and visualizations.
3. Review the plots and summary for insights.

---

Author: Umang Dixit
Date: 4 August 2025
