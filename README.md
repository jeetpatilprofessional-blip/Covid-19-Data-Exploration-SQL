# COVID-19 Data Exploration using SQL

## Project Overview
This project explores global COVID-19 data using SQL Server to analyse reported cases, deaths, infection rates, and vaccination progress across countries and continents.

The analysis uses COVID-19 deaths and vaccination datasets and demonstrates SQL techniques for extracting insights from large datasets.

## Tools
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)

## SQL Skills Demonstrated
- Joins
- Common Table Expressions (CTEs)
- Temporary Tables
- Window Functions
- Aggregate Functions
- Data Type Conversion
- Creating Views

## Analysis
- Total cases versus deaths and death percentage
- Cases versus population and infection percentage
- Countries with the highest infection rates
- Countries with the highest death counts
- Death counts by continent
- Global COVID-19 statistics
- Rolling vaccination totals
- Percentage of population vaccinated

## Datasets
- `CovidDeaths`
- `CovidVaccinations`

Dataset files are intended to be stored in the `Dataset/` folder.

## Repository Structure
```
Covid-19-Data-Exploration-SQL/
├── README.md
├── Dataset/
│   ├── CovidDeaths.xlsx
│   └── CovidVaccinations.xlsx
└── SQL/
    └── Covid19_Data_Exploration.sql
```

## How to Run
1. Import the datasets into SQL Server.
2. Create and use a database for the project.
3. Ensure the tables are named `CovidDeaths` and `CovidVaccinations` (or adjust the script accordingly).
4. Open and execute the SQL analysis script in SSMS.

## Author
Jeet Jaykar Patil
