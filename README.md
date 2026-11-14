# Electric Vehicle Population Analysis | Power BI

## Project Overview

This project focuses on analyzing the Electric Vehicle (EV) Population dataset using **Microsoft Power BI**. The objective is to explore electric vehicle adoption patterns, identify leading manufacturers and popular models, and understand the distribution of vehicles based on their electric range and Clean Alternative Fuel Vehicle (CAFV) eligibility.

The project demonstrates the use of data cleaning, transformation, data modeling, DAX calculations, and interactive data visualization to turn raw data into meaningful insights.

## Objectives

- Analyze the overall electric vehicle population.
- Compare Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).
- Examine electric vehicle registrations across different model years and states.
- Identify the top 10 electric vehicle manufacturers and models.
- Analyze vehicle distribution by CAFV eligibility.
- Present key findings through interactive Power BI dashboards.

## Tools & Technologies

- **Microsoft Power BI Desktop** – Dashboard development and visualization.
- **Power Query** – Data cleaning and transformation.
- **DAX (Data Analysis Expressions)** – Measures and calculated columns.
- **Microsoft Excel / CSV** – Dataset handling.

## Data Preparation & Cleaning

The dataset was prepared using Power Query Editor. The following operations were performed:

- Renamed and standardized electric vehicle type categories.
- Removed records with missing Vehicle Location values.
- Created electric range categories:
  - Low: 0–100
  - Medium: 101–200
  - High: Above 200
- Extracted latitude and longitude coordinates from Vehicle Location.
- Created simplified CAFV eligibility categories for clearer visualization.
- Checked and prepared columns for analysis.

## Key Performance Indicators (KPIs)

The dashboard includes the following key metrics:

- **Total Vehicles** – Total number of electric vehicles in the cleaned dataset.
- **Average Electric Range** – Average electric range of the vehicles.
- **Total BEV Vehicles** – Number of Battery Electric Vehicles.
- **BEV Percentage** – Percentage of BEVs in the total vehicle population.
- **Total PHEV Vehicles** – Number of Plug-in Hybrid Electric Vehicles.
- **PHEV Percentage** – Percentage of PHEVs in the total vehicle population.

## Dashboard Pages

### 1. EV Market Overview

Provides a high-level overview of the electric vehicle population through KPI cards and visualizations.

Key analysis:
- Total electric vehicle population.
- Average electric range.
- BEV and PHEV distribution.
- Vehicle registrations by model year.
- Geographic distribution of electric vehicles across states.

### 2. Manufacturer Analysis

Focuses on the manufacturers contributing to the electric vehicle market.

Key analysis:
- Top 10 electric vehicle manufacturers by vehicle count.
- Distribution of vehicles based on CAFV eligibility.
- Comparison of manufacturer representation in the dataset.

### 3. Model Analysis

Explores the popularity of individual electric vehicle models.

Key analysis:
- Top 10 electric vehicle models by total vehicle count.
- Comparison of vehicle representation across popular models.

## Interactive Features

- Dedicated report pages for different aspects of EV analysis.
- Navigation buttons to move between dashboard pages.
- Interactive charts and visual filtering.
- KPI cards for quick access to important metrics.

## Project Structure

```text
electric-vehicle-population-analysis/
│
├── README.md
├── Electric_Vehicle_Analysis.pbix
├── Electric Vehicle Population dataset.csv
│
└── screenshots/
    ├── ev-market-overview.png
    ├── manufacturer-analysis.png
    └── model-analysis.png
```

*Note: Update the filenames above to match the actual files uploaded to the repository.*

## How to View the Project

1. Clone or download this repository.
2. Download the Power BI `.pbix` file.
3. Open the file using Microsoft Power BI Desktop.
4. Explore the three report pages using the navigation buttons.

## Dataset

The project uses the Electric Vehicle Population dataset, containing information about electric vehicle manufacturers, models, model years, electric range, vehicle type, state, and CAFV eligibility.

## Author

Created as a Data Analytics project using Microsoft Power BI.

**Areas Demonstrated:** Data Cleaning | Data Transformation | DAX | Data Visualization | Dashboard Development
