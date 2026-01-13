# 👮 Malaysia Crime Data Analytics Dashboard (2021–2023)

### *Geospatial Intelligence & Temporal Analysis for Public Safety*

## 🌟 Project Overview

This project provides a comprehensive analysis of crime trends across Malaysia using data sourced from the **Department of Statistics Malaysia (DOSM)**. By integrating **Excel** for data engineering and **Tableau** for advanced visualization, I developed a Business Intelligence (BI) dashboard to identify high-risk hotspots and correlate crime volume with urban density to support data-driven policy recommendations.

## 🚀 Key Insights & Impact

* **Hotspot Identification:** Conducted geospatial analysis to pinpoint **Selangor** as the highest crime hotspot with over **160,000 recorded cases**, specifically identifying high-risk districts such as **Gombak, Kajang, and Petaling Jaya**.


* **Crime Category Trends:** Segmented data into Property and Violent crime categories to track the prevalence of specific offenses like theft, housebreaking, and assault over a three-year period.


* **Correlation Analysis:** Identified a strong correlation between **population density and crime volume** in urban centers, leading to proposed infrastructure and policy improvement initiatives.


* **Temporal Patterns:** Utilized temporal analysis to track crime fluctuations from 2021 to 2023, providing a baseline for assessing the effectiveness of local law enforcement strategies.



## 🛠️ Technical Implementation

### **1. Data Engineering (Excel)**

* **Cleaning & Transformation:** Processed raw DOSM datasets by standardizing district names and handling categorical inconsistencies to ensure seamless integration with Tableau.


* **Aggregation:** Structured data into logical hierarchies (State > District > Crime Type) for granular drill-down capabilities.



### **2. Geospatial Visualization (Tableau)**

* **Interactive Mapping:** Built dynamic maps to visualize crime distribution across all Malaysian states.


* **Advanced Dashboards:** Implemented interactive filters and parameters allowing stakeholders to toggle between years and specific crime indices.



## 📂 Repository Structure

```text
├── data/               # Processed CSV/Excel datasets from DOSM
├── images/             # Dashboard screenshots and geospatial maps
├── reports/            # Full Crime Index Analysis Report (PDF)
├── .gitignore          # Prevents system and temporary files from cluttering the repo
├── README.md           # Project documentation and policy insights
└── Crime_Analytics_Dashboard.twbx # Tableau Packaged Workbook for interactive viewing

```

## 📥 How to View

1. **Static Preview:** View the high-resolution screenshots in the `/images` folder.
2. **Interactive Version:** Download the `Crime_Dashboard.twbx` file and open it using **Tableau Desktop** or **Tableau Public** to explore the interactive slicers and maps.

---
