# Hospital Readmission & Admission Trends Analysis

## Overview
This repository contains a data analytics project focused on tracking hospital admission volumes and patient readmission rates. It features a complete pipeline: utilizing Jupyter Notebooks for exploratory data analysis (EDA) and trend visualization, backed by regional and patient-level datasets, and culminating in a management-level dashboard.

## Project Assets

### 📓 Python Analysis Notebooks
* **`01_Monthly_Admission_Trends.ipynb`:** Analyzes and visualizes macro-level seasonal admission trends over the course of the year.
* **`02_Admissions_Over_Time.ipynb`:** Explores how general patient admission rates fluctuate across broader timeframes.
* **`03_High_Volume_Ward_Analysis.ipynb`:** Drills down into department-level data to identify high-capacity wards and readmission bottlenecks.

### 📁 Datasets (CSV)
* **`Regional_Healthcare_Data.csv`:** Macro-level data tracking healthcare metrics across different regional facilities.
* **`Patients_readmission_data.csv`:** Patient-level demographic and visit data used to calculate readmission intervals.
* **`Department_readmission_data.csv`:** Aggregated metrics showing readmission rates categorized by specific hospital wards/departments.

### 📊 Dashboard
* **`Readmission_Dashboard.pdf`:** A static export of the final visualization dashboard, summarizing the key findings from the Python analysis for executive review.

## Potential Use Cases
* **Resource Allocation:** Predicting high-volume months to ensure adequate staffing and bed availability.
* **Quality Assurance:** Identifying specific departments with higher-than-average readmission rates to trigger clinical review.
* **Financial Strategy:** Tracking metrics that directly impact healthcare reimbursement penalties associated with 30-day readmissions.

## How to Use
1. **Explore the Code:** Open the numbered Jupyter Notebooks to view the Python logic, data manipulation, and generated plots.
2. **Review the Summary:** Open the `Readmission_Dashboard.pdf` to see how the code translates into a high-level BI report.
3. **Practice:** Download the CSV datasets to replicate the analysis or build out custom visualizations in a tool like Tableau or Power BI.

> **Disclaimer:** All data within this repository is strictly synthetic and created for educational portfolio demonstration purposes. It does not contain any real patient health data or Protected Health Information (PHI).
