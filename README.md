# COVID-19 Data Exploration in SQL

This repository contains SQL scripts for exploring and analyzing COVID-19 data obtained from Our World in Data. The data has been split into two datasets, `CovidDeaths` and `CovidVaccinations`, and uploaded to a SQL Server.

## Highlights

- **Data Processing:** The raw data was processed and split into two datasets.
- **Metrics Calculations:** Various metrics were calculated, including death percentages, infection rates, and population vaccination percentages.
- **Data Type Conversion:** Converted data types for relevant columns.
- **Joining Tables:** Joined `CovidDeaths` and `CovidVaccinations` datasets for combined insights.

## SQL Script Sections

1. **Selecting Data:**
   - Filtering data from the `CovidDeaths` dataset based on continent.
   - Selecting relevant columns for exploration.

2. **Data Exploration:**
   - Investigating total cases, total deaths, death percentages, and population infection rates.
   - Identifying countries with the highest infection rates and death counts per population.

3. **Continent-wise Analysis:**
   - Breaking down data by continent and exploring death counts.
   - Exploring global numbers, including new cases, new deaths, and death percentages.

4. **Joining Data:**
   - Joining `CovidDeaths` and `CovidVaccinations` datasets for combined insights.

5. **Population Vaccination Percentage:**
   - Calculating the percentage of the population vaccinated over time.
   - Using Common Table Expressions (CTEs) and temporary tables for analysis.

6. **Creating Views:**
   - Creating a view to store data for later visualizations.

## Getting Started

1. Clone this repository.
2. Execute the SQL scripts in your SQL Server environment to replicate the analyses.

## Visualization

Visualizations and insights can be derived from the joined tables and views created during the analysis.

Feel free to explore the SQL scripts for more detailed queries and insights!

Happy exploring! 🚀

