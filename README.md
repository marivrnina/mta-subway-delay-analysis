# MTA Subway Delay Analysis 2020–2025

Analyzing what drives NYC subway delays across over 20 lines and 6 delay categories using time series forecasting and XGBoost.

## Overview
This project combines two MTA open datasets: delay incidents and daily ridership, to identify the primary drivers of subway service disruptions and forecast future delay volumes.

## 📹 Project Walkthrough
Watch the walkthrough: https://youtu.be/RdgQJYzO398

## Key Findings
- Infrastructure & Equipment is the largest delay category systemwide
- 4 lines (N, A, F, 6) account for 30% of all delays
- Weekday delays are 3.5x higher than weekends
- Ridership barely correlates with delays (r=0.15) — the problem is operational

## Methods
- Exploratory Data Analysis
- SARIMA time series forecasting
- XGBoost regression (R²=0.83, MAE=46 delays)
- Per-category delay prediction by day type

## Tools
Python, Pandas, Seaborn, Matplotlib, Statsmodels, XGBoost, Scikit-learn

## Data Sources
- [MTA Subway Trains Delayed](https://data.ny.gov/Transportation/MTA-Subway-Trains-Delayed-Beginning-2020/9zbp-wz3y)
- [MTA Daily Ridership](https://data.ny.gov/Transportation/MTA-Daily-Ridership-Data-2020-2025/vxuj-8kew)
