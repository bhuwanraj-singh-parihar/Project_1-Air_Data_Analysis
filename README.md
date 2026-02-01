# CIVE 202 Project #1  
## Nebraska Air Quality Analysis Using AirPurple Sensors

**By:** Bhuwanraj Singh Parihar  
**Course:** CIVE 202 – Civil Engineering Analysis II  
**Client:** UNMC Water, Climate, and Health Working Group  
January 31, 2026  

---

## Project Overview

This project analyzes publicly available **AirPurple sensor** data across Nebraska to understand **air quality patterns**, identify **extreme pollution events**, and evaluate potential **public health risks**. The analysis focuses on key pollutants (**VOC, PM2.5, PM10**) and investigates how environmental factors like **temperature**, **humidity**, and **sensor elevation** relate to air quality conditions.

---

## Client Questions Addressed

This analysis was designed to answer the following:

- Where are pollution levels consistently highest across the monitoring network?
- When did the most extreme pollution events occur?
- How do **temperature** and **humidity** influence PM2.5 concentrations?
- Did PM2.5 levels reach categories associated with **health concerns** under EPA AQI standards?
- Does **sensor elevation** appear to affect pollutant measurements?

---

## Repository Contents (Final Submission Files)

| File | Description |
|------|-------------|
| [**AirQuality_Daily_StudentVersion.csv**](AirQuality_Daily_StudentVersion.csv) | Raw air quality dataset used in analysis |
| [**CIVE202_Spring2026_Bhuwanraj_Project1_PythonCode.ipynb**](CIVE202_Spring2026_Bhuwanraj_Project1_PythonCode.ipynb) | Jupyter Notebook containing all analysis code |
| [**CIVE202_Spring2026_Bhuwanraj_Project1_ACD.docx**](CIVE202_Spring2026_Bhuwanraj_Project1_ACD.docx) | Annotated Code Document explaining each code section |
| [**CIVE202_Spring2026_Bhuwanraj_Project1_SOW.docx**](CIVE202_Spring2026_Bhuwanraj_Project1_SOW.docx) | Scope of Work outlining project tasks and deliverables |
| [**CIVE202_Spring2026_Bhuwanraj_Project1_Report.docx**](CIVE202_Spring2026_Bhuwanraj_Project1_Report.docx) | Final client-ready report with results and discussion |

---

## Methods Summary

The analysis was conducted using **Python** and the **pandas** library.

Key steps included:

1. Loading and verifying the air quality dataset.
2. Creating environmental categories:
   - Temperature (Cold, Cool, Mild, Warm/Hot)
   - Humidity (Low, Moderate, High)
   - Elevation (Low, Medium, High)
3. Grouping data by location to calculate mean and median pollutant levels.
4. Identifying maximum pollution events (date and location).
5. Classifying PM2.5 values into **EPA AQI-style categories**.
6. Comparing pollutant levels across temperature, humidity, and elevation categories.

All steps are fully documented in the Jupyter Notebook and Annotated Code Document.

---

## How to Run the Analysis

1. Download or clone this repository.
2. Ensure [**AirQuality_Daily_StudentVersion.csv**](AirQuality_Daily_StudentVersion.csv) is in the same folder as the notebook.
3. Open [**CIVE202_Spring2026_Bhuwanraj_Project1_PythonCode.ipynb**](CIVE202_Spring2026_Bhuwanraj_Project1_PythonCode.ipynb) in Jupyter Notebook.
4. Run all cells from top to bottom.

---

## References

- U.S. Environmental Protection Agency (EPA) — *Air Quality Index (AQI) Basics*  
  https://www.airnow.gov/aqi/aqi-basics/

- PurpleAir Community Documentation  
  https://community.purpleair.com/

- AirNow — Air Quality Information  
  https://www.airnow.gov/
