# Weather_Analysis_Dashboard
---

## 📁 Project Overview

This project explores global weather patterns using structured datasets stored in SQL, with analysis enhanced through Excel and Power BI visualizations. The objective is to uncover trends, seasonal variations, geographic relationships, and the broader impact of weather by examining key variables such as temperature, humidity, air pressure, wind speed, wind direction, and weather conditions.

---

## 🗃️ Dataset Structure

The data is organized into a relational database with the following tables:

**1. City Attributes**
Contains geographical details of each city, including country ID, latitude, and longitude. This supports regional analysis and clustering.

**2. City Lookup**
Maps city IDs to their respective names.

**3. Country Table**
Maps country IDs to country names for aggregation at the national level.

**4. Date Lookup**
Stores date-related information for time-based analysis.

**5. Time Lookup**
Captures hourly time data for granular temporal insights.

**6. Final Fact Table**
The core dataset containing weather observations such as temperature, humidity, pressure, wind speed, wind direction, and weather descriptions. This table drives all analysis and reporting.

---

## 🔍 Analytical Framework (MECE Approach)

**Distinct Analytical Areas:**

* **Geographical Analysis:** Based on latitude, longitude, and spatial grouping
* **Weather Metrics:** Temperature, humidity, pressure, wind patterns
* **Time-Based Analysis:** Hourly, monthly, and seasonal trends
* **Impact Analysis:** Effects on pollution, energy usage, and extreme weather events

**Comprehensive Coverage Includes:**

* City-level climate profiling
* Variable correlation analysis
* Detection of anomalies and extreme events
* Insights for forecasting and planning

---

## 🧪 Exploratory Data Analysis (SQL + Excel)

All analysis was performed using SQL queries, with outputs exported to Excel for visualization.

**Key Findings:**

* No cities fall in extreme polar regions (above 60°N or below 60°S)
* Cities close in latitude/longitude tend to share similar climates
* Temperature decreases as latitude increases; longitude shows minimal impact
* Canadian cities like Toronto and Montreal experience peak rainfall in spring and fall
* Weak relationship between humidity and pressure
* Coastal wind patterns influence temperature variations
* February shows the highest temperature fluctuations
* Storms peak in April; heatwaves occur between May and July
* Southern Hemisphere remains warmer during Northern Hemisphere winters
* Rising temperatures correlate with increased energy consumption
* Stable wind patterns help reduce pollution, while stagnant air worsens it
* Wind-prone cities like Dallas and Phoenix face transport disruptions

---

## 📊 Power BI Dashboard Insights

Interactive dashboards were built using Power BI and DAX calculations.

**Highlights:**

* Geographic map showing global city distribution
* Top countries by number of cities
* Temperature trends from 2012 to 2017 showing a gradual increase
* Monthly humidity heatmaps across cities
* Inverse relationship between wind speed and air pressure (notably in 2016)
* Identification of warmest (Miami, Phoenix) and coldest (Montreal, Toronto) cities
* Hourly patterns of clear vs. rainy conditions
* Wind distribution visualized through heatmaps and wind rose charts
* Comparative analysis between cities and countries

---

## ⚙️ Workflow

1. **Data Preparation:** Import and structure datasets in MySQL
2. **SQL Analysis:** Perform queries for insights and relationships
3. **Excel Processing:** Create summaries, pivot tables, and initial charts
4. **Power BI Visualization:** Build dashboards and apply DAX for deeper insights
5. **Reporting:** Present findings through reports and visual storytelling

---

## 🛠️ Tools Used

* **MySQL:** Data querying and analysis
* **Excel:** Data summarization and basic visualization
* **Power BI:** Dashboard creation and advanced analytics

---

## 📌 Conclusion

This project demonstrates how combining SQL, Excel, and Power BI can generate meaningful insights from weather data. The analysis supports applications in urban planning, energy management, and disaster preparedness.

**Future Enhancements:**

* Integration of real-time weather APIs
* Long-term forecasting models
* Climate change trend analysis

---
