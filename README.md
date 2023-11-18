# EU Unemployment Data Analysis
## Overview
This Python script analyzes unemployment data across European Union (EU) countries, focusing on different demographics and spanning from January 2010 to June 2020. The goal is to understand unemployment trends and assess the impact of various factors, including the COVID-19 pandemic.

## Data Sources
`Unemployment Data (une_rt_m.tsv)`
Contains TSV formatted data on unemployment rates in EU countries.

`Country Codes Data (wikipedia-iso-country-codes.csv)`
Includes ISO country codes and related details.

## Dataset Details
Age Groups
- `TOTAL`: All age groups
- `Y_LT25`: Less than 25 years old
- `Y25_74`: Between 25 and 74 years old

Data Units
- `PC_ACT`: Percentage of Active Population
- `THS_PER`: Thousands of Persons

Sex Groups
- `T`: Total (all genders)
- `M`: Male
- `F`: Female

Seasonal Adjustment (s_adj)
- `NSA`: Non-Seasonally Adjusted
- `SA`: Seasonally Adjusted
- `TC`: Trend-Cycle

## Dependencies
- Python 3.x
- Libraries: Pandas, Warnings, Regular Expressions (re)

## Features
- Categorizes data by country, age, unit, sex, and seasonally adjusted rates.
- Compares unemployment rates over time across different EU countries.
- Filters data for EU countries only.

## How to Run
- Ensure Python 3.x and required libraries are installed.
- Place the unemployment data and country codes in the datasets folder.
- Execute the script using Python.

## Analysis Outcomes
- Insights into average unemployment rates by year and country.
- Detailed breakdown of unemployment rates by age, sex, and rate type.

## Acknowledgements
Data sourced from the EU Open Data Portal: EU Open Data Portal