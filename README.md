# Chicago-crime-2023-data-analysis
This project provides an analysis of crime dynamics in Chicago for the year 2023, using a dataset provided by the Chicago Data Portal. The analysis was done using Tableau for visualization and Python for data cleaning. The project explores spatial, temporal, and crime-type trends with a focus on drawing insights from arrest rates and high-crime locations.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Cleaning Process](#data-cleaning-process)
- [Visualizations](./Visualizations)
- [Sample Visualizations](#Sample_Visualizations)
- [Insights](#insights)
- [Technologies Used](#technologies-used)
- [Hypotheses and Results](./Chicago-crime-2023-data-analysis.pdf)

## Introduction
Crime dynamics are influenced by various factors including geography, time, and law enforcement strategies. This project investigates these dynamics for Chicago in 2023, focusing on:
- Prevalence of different crime types.
- Crime rates across various locations and times of the day.
- Arrest rates for specific crimes and locations.

## Dataset
The dataset was sourced from the [Chicago Data Portal](https://data.cityofchicago.org/Public-Safety/Crimes-2023/xguy-4ndq/about_data), containing information on crimes reported in 2023. The cleaned dataset is [Cleaned Dataset](./Datasets/)

### Key Attributes:
- **Crime Type**: The primary type of crime (e.g., Theft, Battery).
- **Location Type**: The place where the crime occurred (e.g., Street, Apartment).
- **Date**: Date and time of the incident.
- **Arrest**: Whether an arrest was made.
- **Street**: The street where the crime occurred.

The dataset was cleaned by removing unnecessary columns and normalizing certain values (e.g., street names).

## Data Cleaning Process
The data cleaning steps involved:
1. Dropping irrelevant columns like `Case Number`, `IUCR`, `Ward`, etc.
2. Normalizing street names to maintain consistency.
3. Converting the date to a standard format for easier analysis.
4. Extracting the street name from block addresses.

## Visualizations
The analysis was done using Tableau, with key visualizations highlighting:
- Crime trends over the months of 2023.
- The top 10 streets with the highest crime rates.
- Crime distribution by location type (e.g., Street, Apartment).
- Arrest patterns for different crime types.

### Sample_Visualizations:
- Crime distribution by time of day
  ![Crime distribution by time of day](./Visualizations/Crime_count_over_hours_of_day.jpg)
- Top 20 Least safe streets by crime count.
  ![Top 20 Least safe streets by crime count](./Visualizations/Least_safe_streets_20.jpg)
- Arrest count comparison between `S Michigan Ave` and `N State St`.
- ![Arrest count comparison between `S Michigan Ave` and `N State St`](./Visualizations/Arrest_count_comparison_nstate_smichiganave.jpg)


## Insights
- **Theft** is the most common crime in Chicago for 2023.
- **S Michigan Ave** is the least safe street, with a significant concentration of theft incidents.
- Arrest rates vary significantly, with **`Narcotics`** crimes leading to more arrests than other types.
- Crime rates peak during late night hours, particularly around **midnight**.

## Technologies Used
- **Python**: Data cleaning and preprocessing.
- **Tableau**: Visualizations and data exploration.
- **GitHub**: Project documentation and version control.

