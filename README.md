# Poverty and Inequality Dashboard

This project involves performing exploratory data analysis (EDA) on a dataset related to poverty and inequality, training a machine learning model, and creating an interactive dashboard to visualize the results. **There is a picture of Dashboard Created in Power BI in PovertyRAteDashboardPDF**

## Project Overview

•  **EDA and Data Visualization**: Conducted EDA using pandas profiling and visualized the data to identify trends and patterns.

•  **Model Training**: Trained a machine learning model to predict the share of the population living below $1 a day.

•  **Dashboard**: Developed an interactive dashboard using Dash to visualize poverty rates, income distribution, and inequality indicators.


## Dashboard Features

•  **Select Country**: Dropdown to select a country.

•  **Select Year**: Dropdown to select a year.

•  **Poverty Rate Chart**: Line chart showing the trend of poverty rates over the years.

•  **Income Distribution Chart**: Bar chart showing the income distribution for the selected country and year.

•  **Inequality Indicators Chart**: Bar chart showing various inequality indicators for the selected country and year.


## Installation

1. Clone the repository:
```bash
git clone https://github.com/FurqanMujahid/PovertyRateAnalysis.git
cd PovertyRateAnalysis

# Run all the cells

Usage
•  Dashboard Open.

•  Use the dropdowns to select a country and year.

•  View the visualizations to gain insights into poverty and inequality.

Model Training
The trained model is saved as a joblib file. You can load and use the model as follows:

import joblib

# Load the model
model = joblib.load('poverty_model.pkl')

# Make predictions
prediction = model.predict(sample_data)

