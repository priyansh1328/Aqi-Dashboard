## 🌬️ India BreathSync: National Air Quality Insights Dashboard

A comprehensive, interactive Power BI dashboard designed to monitor and analyze Air Quality Index (AQI) trends across India. This tool provides a granular look at pollution levels, prominent pollutants, and air quality status over a multi-year period to support environmental awareness and policy-making.

---

### 1. Project Title / Headline
**India BreathSync: National Air Quality Insights Dashboard**  
An interactive data visualization platform built to track India’s atmospheric health, focusing on year-over-year AQI trends, pollutant distribution, and regional air quality classifications.

---

### 2. Short Description / Purpose
The **India BreathSync Dashboard** is a robust analytical tool designed to visualize air quality data across various Indian states and cities from 2015 to 2025. By transforming complex environmental datasets into intuitive visuals, the dashboard helps users identify pollution hotspots, seasonal variations, and the primary pollutants (like PM10 and PM2.5) affecting different regions. It serves as a vital resource for environmental researchers, urban planners, and health-conscious citizens looking to understand the air they breathe.

---

### 3. Tech Stack
The dashboard was built using the following tools and technologies:
*   📊 **Power BI Desktop** – The primary platform for creating interactive reports and data visualizations.
*   📂 **Power Query** – Utilized for data cleaning, handling missing values, and normalizing pollutant names.
*   🧠 **DAX (Data Analysis Expressions)** – Used to calculate total AQI values, year-over-year growth, and dynamic categorization logic.
*   📝 **Data Modeling** – Established relationships between time-series data, regional geographies, and pollutant categories.
*   📁 **File Format** – `.pbix` for the live report and `.png` for repository documentation.

---

### 4. Data Source
The data is sourced from historical air quality records across India (comparable to datasets from **CPCB - Central Pollution Control Board**). 

The dataset includes thousands of records containing daily/monthly AQI values, specific pollutant concentrations (PM2.5, PM10, NO2, NH3, SO2, CO, and Ozone), and geographical markers for Indian states and cities spanning the last decade.

---

### 5. Features / Highlights

*   **Business/Environmental Problem**
    Air pollution is a critical health crisis in India. However, raw environmental data is often dense and difficult for the public or policy-makers to interpret quickly. Understanding which months are most hazardous or which pollutants are dominant in specific states is essential for targeted intervention.

*   **Goal of the Dashboard**
    To provide a centralized, easy-to-navigate interface that:
    *   Tracks the rise and fall of AQI levels over a 10-year horizon.
    *   Identifies the most dangerous pollutants by region.
    *   Maps air quality status (Good, Satisfactory, Poor, etc.) across India's geography.

*   **Walkthrough of Key Visuals**
    *   **AQI Trend by Year (Column Chart):** Visualizes the total sum of AQI values from 2015 to 2025, highlighting the steady increase in pollution metrics over time.
    *   **Prominent Pollutant Analysis (Line Chart):** Tracks the count of occurrences for specific pollutants. It clearly identifies **PM10 and PM2.5** as the leading contributors to poor air quality.
    *   **Air Quality Status Distribution (Donut Chart):** Breaks down the total data into status categories such as *Moderate (38.21%)*, *Satisfactory (22.8%)*, and *Poor (21.12%)*.
    *   **Geospatial Map (India Map):** A bubble map showing the air quality status across various states, allowing users to hover and see specific regional data.
    *   **Interactive Slicers:** Users can filter the entire dashboard by **Year**, **Month**, or specific **State** to perform deep-dive regional analysis.
    *   **Total AQI Gauge:** A central KPI gauge showing the aggregate AQI value (50M) against the total scale to represent the sheer volume of data analyzed.

*   **Impact & Insights**
    *   **Policy Support:** Helps government bodies identify years or months with peak pollution to implement "Graded Response Action Plans."
    *   **Public Health:** Allows citizens to identify the "Good" and "Satisfactory" windows for outdoor activities.
    *   **Pollutant Focus:** Highlights that PM10 remains the most frequently recorded pollutant, suggesting a need for better dust management and industrial filtration.

---

### 6. Screenshots / Demos
<img width="1280" height="766" alt="snashot of dashboard" src="https://github.com/user-attachments/assets/cf9e118a-22e9-4531-8ae7-0f0c6beebf86" />

#### Dashboard Preview
![India Air Quality Dashboard Preview](https://r.jina.ai/i/058e5781373549298457c7c34b6e5118)
*Figure 1: Main View of the India BreathSync Dashboard showcasing trends from 2015-2025.*
