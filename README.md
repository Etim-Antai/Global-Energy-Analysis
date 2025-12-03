📊 Global Sustainable Energy Data Analysis & Forecasting
📘 Project Overview

This project explores global sustainable energy trends using data from Our World in Data.
It includes interactive visualizations, country-level comparisons, and machine learning forecasting using Facebook Prophet.

The goal is to provide clear insights into electricity access, renewable energy adoption, CO₂ emissions, and long-term sustainability trends across countries.

This project was developed and deployed as a Kaggle Notebook and mirrored on GitHub for public access.


🎯 Project Objectives

Analyze global energy sustainability metrics across countries.

Visualize time-series trends using interactive dropdown tools.

Identify top renewable-energy-adopting countries.

Examine relationships between major energy variables using correlations.

Forecast future energy patterns (e.g., CO₂ emissions) using Prophet.


🔧 Tools & Technologies

Python

Pandas

Matplotlib

Seaborn

Scipy

Facebook Prophet

IPyWidgets (interactive dropdowns)

Kaggle Notebook




📊 Key Features
1️⃣ Interactive Country Dashboard

A dropdown menu allows users to select any country and automatically update:

Electricity access trends

Renewable energy share

CO₂ emissions

Fossil vs renewable electricity

The chart uses:

Smooth interpolation

Clean visuals

Automatic country filtering

2️⃣ Forecasting with Prophet

For each selected country, the model predicts CO₂ emissions for the next 10 years:

✔ Cleaned and filtered data
✔ Prophet model with yearly seasonality
✔ Forecast and confidence intervals
✔ Automatic visualization

4️⃣ Correlation Heatmap

A heatmap reveals relationships between:

CO₂ emissions

Electricity access

Renewable energy share

Fossil electricity

Low-carbon electricity

Energy consumption

GDP per capita
