# Crime Data Analysis

## Project Overview

This project analyzes crime data from January 2020 to October 2023 to identify trends, patterns, and insights. The dataset includes various attributes such as crime type, location, and victim details. This analysis aims to provide a comprehensive understanding of crime dynamics over the years.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Data Cleaning](#data-cleaning)
- [Analysis and Findings](#analysis-and-findings)
- [Installation](#installation)

## Data Source

The crime data was downloaded from a public database https://catalog.data.gov/dataset/crime-data-from-2020-to-present covering the period from January 2020 to October 2023. It includes 28 columns with key information such as the date and time of occurrence, area name, crime description, and victim demographics.

## Data Cleaning

Key steps in data cleaning included:

- Excluding incomplete years (e.g., 2023) from analysis.
- Replacing null values in 'Vict Sex', 'Vict Descent', and 'Premis Desc' with 'Unknown'.
- Handling duplicates and converting date columns to datetime format.

## Analysis and Findings

### Overall Crime Trends

- **Total Crimes Per Year**: Crime rates have been increasing at a CAGR of 8.38%.
- **Seasonal Patterns**: No significant seasonality observed, but February shows fewer crimes due to fewer days.

### Common Crime Types

- **Most Common**: 'VEHICLE - STOLEN' is the most frequent crime type.
- **Rising Trends**: 'THEFT OF IDENTITY' has shown significant growth over the years.

### Regional Analysis

- **Crime Distribution**: Central area reports the highest number of crimes, while Foothill reports the least.

### Temporal Patterns

- **Day of the Week**: Higher crime rates on Fridays and Saturdays.
- **Time of Day**: Peaks in the afternoon and early evening.

### Impact of Major Events

- **COVID-19**: Significant drop in crime during lockdowns.
- **Elections**: Decrease in crimes during election periods due to increased security.

## Installation

Clone the repository:

```bash
git clone https://github.com/dheeraj932/Crime-Data-Analysis.git
cd Crime-Data-Analysis
