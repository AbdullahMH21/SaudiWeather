# 🌤 SaudiWeather Dashboard

A data visualization and exploration tool for Saudi Arabian weather trends, combining static analysis with an interactive dashboard built using Streamlit and Plotly.

## 📁 Project Files

- `EDA.py`  
  Performs data loading, preprocessing, and exploratory data analysis (EDA) on Saudi cities' weather data. It includes:
  - Renaming and cleaning weather features
  - Calculating average temperature
  - Plotting histograms, correlations, and distribution graphs

- `weather_analysis.py`  
  An interactive dashboard built with Streamlit. It provides:
  - A city selector interface
  - Folium-based geospatial visualization
  - Date range filtering
  - Dynamic map type switching (temperature, humidity, dew point, wind speed)
  - User-driven sliders for preferred weather conditions

## 🗃 Dataset

The dataset used:

SaudiCitiesWeather.csv

## 🧑‍🎓 Features

- Select a custom date range for weather trends
-  Interactive Folium map with weather overlays
-  Summary statistics and trend filtering
-  Sliders for user-defined ideal weather (temperature/humidity)
-  Logo branding and polished layout

## 🧪 Requirements

Install all necessary packages using `uv` or `pip`:

uv pip install pandas matplotlib seaborn streamlit folium streamlit-folium geopandas plotly

Or using pip:

pip install pandas matplotlib seaborn streamlit folium streamlit-folium geopandas plotly

## 🚀 Run Instructions

### ➤ Launch the static EDA:

python EDA.py

### ➤ Start the Streamlit dashboard:

streamlit run weather_analysis.py

