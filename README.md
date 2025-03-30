# Power-BI-Capstone-Project-Weather_Analysis
This is my final capstone project for Power BI

**Drive Link**

Link : https://drive.google.com/drive/folders/18r-Pn4C_DhWSydFqz_iyoVALTq6qrVyX?usp=drive_link


🌦️ **Weather Analysis Project**



📌 **Overview**


The Weather Analysis Project aims to explore and visualize global weather patterns using advanced data analysis techniques. It leverages meteorological data—temperature, humidity, pressure, wind speed, and direction—across various cities and time periods to derive actionable insights for urban planning, disaster preparedness, climate research, and energy management.
This project combines Power BI dashboards, Exploratory Data Analysis (EDA) in Excel, and structured documentation using relational databases for a complete end-to-end weather analytics solution.



🎯 **Objectives**


Analyze seasonal trends and anomalies in temperature, humidity, pressure, and wind.

Study city-wise and country-wise variations in climate patterns.

Create interactive dashboards and visual reports using Power BI.

Conduct EDA to identify weather correlations and location-based insights.

Support data-driven decision-making in climate-sensitive industries.


🛠️ **Tools & Technologies**


Power BI – For advanced interactive visualizations

Excel – For EDA and dashboard prototyping

MySQL Workbench – For relational data modeling and queries

Python (optional) – For preprocessing or extended analytics

GitHub – Version control and project sharing


🧰 **Dataset & Schema**


The dataset includes weather metrics linked to time and geographic dimensions.

Database Tables
final_fact: Core table for weather observations
![image](https://github.com/user-attachments/assets/8e1fc06c-9a4d-4ece-bb88-5ab1caf71e56)

city_lookup: City metadata
![image](https://github.com/user-attachments/assets/701dfaed-7011-49ab-845f-355669e52a06)

country: Country reference
![image](https://github.com/user-attachments/assets/05b451f1-146f-4fe8-a652-e988b97cd1ba)

city_attributes: Latitude & longitude data
![image](https://github.com/user-attachments/assets/e3c12351-71c6-4434-811a-e379e455fc6f)

date_lookup, time_lookup: Temporal dimensions
![image](https://github.com/user-attachments/assets/f256b52f-890b-4b66-8d72-76c00f80a77c)

Key Columns
Table	Column	Description
final_fact	temperature	Temperature in Celsius
final_fact	humidity	Humidity in %
final_fact	pressure	Atmospheric pressure in hPa
final_fact	wind_speed	Wind speed in m/s
city_attributes	latitude, longitude	City coordinates


📊 **Power BI Visualizations**


A range of visualizations were created to uncover trends, relationships, and anomalies:

🌍 Geographical Maps: City distributions based on latitude & longitude

![image](https://github.com/user-attachments/assets/9ef3f3ba-71cb-4f79-bfc0-2d2812d4c641)


📊 Bar Charts: Top countries by city count, temperature extremes

![image](https://github.com/user-attachments/assets/444c7b4e-0f5b-49ea-b275-8fb5104c0868)


📈 Line Charts: Temperature trends over time (global and city-specific)
![image](https://github.com/user-attachments/assets/ae05a67f-6745-46b4-a348-620d9af47b44)


🌡️ Heatmaps:

Humidity distribution
![image](https://github.com/user-attachments/assets/47b94d16-5230-4ec5-b152-aef4918f3598)

Wind speed by month
![image](https://github.com/user-attachments/assets/034408b9-7924-4478-83c7-0036d281f1e3)

Busiest weather conditions by hour
![image](https://github.com/user-attachments/assets/dbfb5e30-bd4a-4ed9-979e-bce8b75f2e3e)

🌀 Radial & Wind Rose Charts: Diurnal wind speed and directional patterns
![image](https://github.com/user-attachments/assets/a5d7db61-67b0-4f9a-bdb2-34271f4d7256)
![image](https://github.com/user-attachments/assets/2f72dae1-86c4-4c6f-9586-b23ea3a00751)

⚡ Scatter Plots: Wind speed vs air pressure relationships
![image](https://github.com/user-attachments/assets/edc7f017-e15b-4a24-83be-095a2a024b05)

Each visualization is backed by real insights useful for smart cities, climate resilience, and disaster management​.

​
📈 **MECE Breakdown (Problem Segmentation)**


The MECE Breakdown outlines problem areas across four key domains (refer to image in MECE_BreakDown.pdf):

Climate Pattern Analysis – Temperature trends, humidity variation, pressure shifts

Weather Conditions – Categorization & frequency of weather types

Correlation Analysis – Relations between weather attributes (e.g., pressure vs humidity)

Location-Based Insights – Regional extremes and city-level comparisons

![image](https://github.com/user-attachments/assets/6dd26ff2-443e-4bad-9346-74bea7246dd0)


🔍 **Exploratory Data Analysis (EDA)**
![image](https://github.com/user-attachments/assets/c82ebdcc-7617-4e51-a2b4-55b23d7890e4)


Key questions answered during EDA include:

Are cities with similar latitudes experiencing similar climates?

Which cities see the most rain, and in which season?

How does humidity correlate with air pressure?

Which months show the most temperature fluctuation?

Are energy demands affected by extreme temperatures?

Findings are backed by SQL queries and visual summaries in Excel and Power BI
