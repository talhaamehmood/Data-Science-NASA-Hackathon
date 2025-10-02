# Data-Science-NASA-Hackathon
We made a Data analytics and visualization project using 30+ years of NASA data and predicted Weather.
**NASA Space Apps Challenge 2025 Project**

A weather probability dashboard that helps event planners make informed decisions by analyzing 30+ years of NASA satellite data. Select any location and date to get historical weather probabilities, trends, and smart recommendations.

<img width="1899" height="916" alt="image" src="https://github.com/user-attachments/assets/36eb9e1f-de9c-443c-aac4-dc0d4b55f162" />


## 🎯 Problem Statement

Planning outdoor events months in advance is challenging because traditional weather forecasts only work 7-10 days ahead. This app solves that problem by using historical climatology data to predict weather probabilities for any date and location.

## ✨ Features

- **Smart Location Input**: Search by city name or enter coordinates
- **Historical Analysis**: 30+ years of NASA satellite observations
- **Weather Predictions**: Temperature, precipitation, wind speed probabilities
- **Visual Analytics**: Interactive charts, graphs, and probability gauges
- **Climate Trends**: Detect warming/cooling patterns over decades
- **Extreme Event Risk**: Heat wave, heavy rain, and cold weather probabilities
- **Smart Recommendations**: Actionable planning advice based on weather data
- **Packing Checklist**: Personalized items list based on predicted conditions
- **Data Export**: Download results in CSV or JSON format

## 🛰️ NASA Data Sources

- **Primary**: NASA POWER API (MERRA-2 reanalysis)
- **Variables**: Temperature (T2M), Precipitation (PRECTOTCORR), Wind Speed (WS2M)
- **Coverage**: Global, 1981-present
- **Resolution**: Daily observations

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Setup

1. Clone the repository:
```bash
git clone https://github.com/talhaamehmood/Data-Science-NASA-Hackathon.git
cd Data-Science-NASA-Hackathon

Install dependencies:

bashpip install streamlit pandas numpy plotly requests

Run the application:

bashstreamlit run app.py
