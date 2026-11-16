🌍 Global Air Pollution Analytics Dashboard

📌 Project Overview

The **Global Air Pollution Analytics Dashboard** is a data visualization project developed using Microsoft Power BI. It analyzes air quality levels across cities and countries worldwide.

The dashboard provides insights into the Air Quality Index (AQI), pollutant levels, country-wise pollution rankings, and the distribution of different air quality categories.

The main objective is to understand global air pollution patterns and identify areas with higher pollution levels through interactive visualizations.

🎯 Project Objectives

- Analyze air quality across different countries and cities.
- Identify the most polluted countries based on average AQI.
- Compare major air pollutants such as CO, Ozone, NO₂, and PM2.5.
- Understand the distribution of AQI categories.
- Identify cities with the highest pollution levels.
- Present insights through an interactive Power BI dashboard.

 📊 Dataset Description

The project uses a Global Air Pollution dataset containing approximately 23,463 records across 175 countries.

Key Dataset Columns

| Column | Description |
|---|---|
| Country | Name of the country |
| City | Name of the city |
| AQI Value | Overall Air Quality Index |
| AQI Category | Air quality classification |
| CO AQI Value | Carbon Monoxide AQI |
| Ozone AQI Value | Ozone AQI |
| NO2 AQI Value | Nitrogen Dioxide AQI |
| PM2.5 AQI Value | Fine particulate matter AQI |

## 📈 Dashboard Features

The dashboard includes:

1. **Average AQI:** Displays the average Air Quality Index.
2. **Total Records:** Shows the total number of dataset records.
3. **Countries Covered:** Displays the number of countries included.
4. **High-Risk Records:** Shows records classified as Unhealthy, Very Unhealthy, or Hazardous.
5. **AQI Category Distribution:** Visualizes the distribution of air quality categories.
6. **Top 10 Countries by Average AQI:** Identifies countries with the highest average AQI.
7. **Global AQI Map:** Provides a geographical view of air pollution.
8. **Pollutant Comparison:** Compares CO, Ozone, NO₂, and PM2.5 AQI values.
9. **Most Polluted Cities:** Displays the cities with the highest AQI values.
10. **Interactive Filters:** Allows users to filter the dashboard by country and AQI category.

 🛠️ Tools & Technologies

- Microsoft Power BI – Dashboard development and visualization
- Microsoft Excel – Data inspection and analysis
- CSV – Dataset storage
- DAX – Calculated measures and KPIs
- Power Query – Data cleaning and transformation

 🎨 Dashboard Design

The dashboard uses a dark navy and cyan color theme to create a professional data visualization experience.

- Dark Navy: Main background
- Blue: Visual backgrounds
- Cyan: Borders and highlights
- Green: Good air quality
- Yellow: Moderate air quality
- Orange: Poor air quality
- Red: Unhealthy air quality
- Purple: Hazardous air quality

🔍 Key Insights

- The dataset contains approximately 23,463 records from 175 countries.
- The overall average AQI is approximately 72.
- PM2.5 has the highest average pollutant AQI among the four pollutant indicators.
- The dashboard helps identify countries and cities with comparatively higher AQI values.
- AQI category analysis provides an overview of global air quality conditions.

 🚀 How to Run the Project

1. Download or clone this repository.
2. Install Microsoft Power BI Desktop.
3. Open Power BI Desktop.
4. Import the cleaned CSV dataset.
5. Load the data into Power BI.
6. Create the required DAX measures.
7. Apply the dashboard theme.
8. Open or recreate the dashboard visuals.
9. Save the report as a `.pbix` file.

📂 Project Structure


Global-Air-Pollution-Dashboard/
│
├── Dataset/
│   └── Global_Air_Pollution_Clean.csv
│
├── Dashboard/
│   └── Global_Air_Pollution_Dashboard.pbix
│
├── DAX/
│   └── PowerBI_Measures.dax
│
├── Theme/
│   └── PowerBI_Theme.json
│
├── Preview/
│   └── Dashboard.png
│
└── README.md
```

💡 Future Improvements

- Add historical air quality trend analysis if time-based data becomes available.
- Include more detailed geographical analysis.
- Add city-level pollution comparisons.
- Integrate real-time air quality data.
- Develop predictive analytics for air pollution levels.

 👩‍💻 Project Information

**Project Name:** Global Air Pollution Analytics Dashboard

**Domain:** Data Analytics and Business Intelligence

**Visualization Tool:** Microsoft Power BI

**Dataset Type:** Global Air Quality Dataset

**Project Type:** Data Analysis and Visualization

---

### Conclusion

This project demonstrates how data analytics and business intelligence tools can be used to understand global air pollution patterns. The interactive Power BI dashboard transforms raw air quality data into meaningful visual insights that help users explore pollution levels across different countries and cities.
