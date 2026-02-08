# 🌍 Global Air Quality Index Data Analysis and Visualization

## 📖 Project Overview

Air pollution is one of the world's largest health and environmental problems. This project utilizes global air quality data to analyze the concentration of major pollutants—Carbon Monoxide (CO), Nitrogen Dioxide (NO2), Ozone, and Particulate Matter (PM2.5).

Using **Tableau**, I crafted a series of dashboards and a data story to identify pollution hotspots, compare pollutant severity, and determine which chemical compound is the primary driver of the overall Air Quality Index (AQI).

**Key Question:** Which pollutant correlates most strongly with dangerous air quality levels globally?

## 📊 The Data

The dataset contains air quality indices for cities worldwide, including geographical coordinates and specific pollutant values.

* **Source:** [Kaggle: World Air Quality Index by City and Coordinates](https://www.kaggle.com/datasets/adityaramachandran27/world-air-quality-index-by-city-and-coordinates)
* **Key Metrics:**
  * **AQI Value:** Overall Air Quality Index.
  * **CO AQI:** Carbon Monoxide levels.
  * **Ozone AQI:** Ground-level ozone levels.
  * **NO2 AQI:** Nitrogen Dioxide levels.
  * **PM2.5 AQI:** Fine particulate matter (<2.5 micrometers).

## 🖼️ Dashboard Showcase

### 1. Carbon Monoxide (CO) Analytics
*Analysis of CO levels across global cities.*
This dashboard visualizes the concentration of Carbon Monoxide. It features a global heatmap and a treemap to identify cities with the highest recorded CO values.

* **Key Insight:** CO levels generally remain within the "Good" category for most regions, with specific hotspots identified in the bar chart.

### 2. Nitrogen Dioxide (NO2) Analytics
*Geospatial distribution of NO2 pollution.*
This view investigates Nitrogen Dioxide levels, highlighting the disparity between different countries.

* **Key Insight:** The United States shows significant aggregate NO2 values compared to other regions in this dataset, as seen in the "NO2 AQI Value by Country" chart.

### 3. Ozone AQI Analytics
*Understanding Ozone distribution and drivers.*
This dashboard uses box plots to show the spread of Ozone values across different AQI categories.

* **Key Insight:** 93% of the data falls into the "Good" category. The scatter plot reveals a moderate relationship between PM2.5 and Ozone, but Ozone alone is rarely the sole cause of "Unhealthy" ratings.

### 4. The Story: PM2.5 as the Dominant Pollutant
*A Tableau Story walkthrough connecting PM2.5 to overall AQI.*
This analysis culminates in a slide deck style story that isolates PM2.5. By comparing the raw values of all pollutants, it becomes clear that **PM2.5 is the greatest air pollutant**.

The scatter plot below demonstrates an almost perfect linear correlation (diagonal alignment) between **PM2.5 AQI** and **Overall AQI**, proving that fine particulate matter is the primary determinant of air quality.

## 🚀 How to Use These Files

This repository contains the raw data and packaged Tableau workbooks (`.twbx`).

1. **Prerequisites:** You need **Tableau Desktop** or the free **Tableau Public** app installed.
2. **Viewing:**
   * Download the `.twbx` files.
   * Double-click to open. The data is packaged within the file, so no external connection setup is required.
   * Navigate through the tabs to explore the dashboards and the final Story.

## 🛠️ Tools Used

* **Tableau Desktop:** For visualization, dashboarding, and story creation.
* **Microsoft Excel:** For initial data inspection and Data Cleaning.
* **Kaggle:** Data sourcing.
