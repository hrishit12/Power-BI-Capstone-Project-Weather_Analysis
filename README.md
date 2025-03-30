# Power-BI-Capstone-Project-Weather_Analysis
This is my final capstone project for Power BI



🌦️ Weather Analysis Project

📌 Overview

The Weather Analysis Project aims to explore and visualize global weather patterns using advanced data analysis techniques. It leverages meteorological data—temperature, humidity, pressure, wind speed, and direction—across various cities and time periods to derive actionable insights for urban planning, disaster preparedness, climate research, and energy management.

This project combines Power BI dashboards, Exploratory Data Analysis (EDA) in Excel, and structured documentation using relational databases for a complete end-to-end weather analytics solution.

🎯 Objectives
Analyze seasonal trends and anomalies in temperature, humidity, pressure, and wind.

Study city-wise and country-wise variations in climate patterns.

Create interactive dashboards and visual reports using Power BI.

Conduct EDA to identify weather correlations and location-based insights.

Support data-driven decision-making in climate-sensitive industries.

🛠️ Tools & Technologies
Power BI – For advanced interactive visualizations

Excel – For EDA and dashboard prototyping

MySQL Workbench – For relational data modeling and queries

Python (optional) – For preprocessing or extended analytics

GitHub – Version control and project sharing

🧰 Dataset & Schema
The dataset includes weather metrics linked to time and geographic dimensions.

Database Tables
final_fact: Core table for weather observations

city_lookup: City metadata

country: Country reference

city_attributes: Latitude & longitude data

date_lookup, time_lookup: Temporal dimensions

Key Columns
Table	Column	Description
final_fact	temperature	Temperature in Celsius
final_fact	humidity	Humidity in %
final_fact	pressure	Atmospheric pressure in hPa
final_fact	wind_speed	Wind speed in m/s
city_attributes	latitude, longitude	City coordinates
📊 Power BI Visualizations
A range of visualizations were created to uncover trends, relationships, and anomalies:

🌍 Geographical Maps: City distributions based on latitude & longitude

📊 Bar Charts: Top countries by city count, temperature extremes

📈 Line Charts: Temperature trends over time (global and city-specific)

🌡️ Heatmaps:

Humidity distribution

Wind speed by month

Busiest weather conditions by hour

🌀 Radial & Wind Rose Charts: Diurnal wind speed and directional patterns

⚡ Scatter Plots: Wind speed vs air pressure relationships

Each visualization is backed by real insights useful for smart cities, climate resilience, and disaster management​.
​
📈 MECE Breakdown (Problem Segmentation)
The MECE Breakdown outlines problem areas across four key domains (refer to image in MECE_BreakDown.pdf):

Climate Pattern Analysis – Temperature trends, humidity variation, pressure shifts

Weather Conditions – Categorization & frequency of weather types

Correlation Analysis – Relations between weather attributes (e.g., pressure vs humidity)

Location-Based Insights – Regional extremes and city-level comparisons

🔍 Exploratory Data Analysis (EDA)
Key questions answered during EDA include:

Are cities with similar latitudes experiencing similar climates?

Which cities see the most rain, and in which season?

How does humidity correlate with air pressure?

Which months show the most temperature fluctuation?

Are energy demands affected by extreme temperatures?

Findings are backed by SQL queries and visual summaries in Excel and Power BI
