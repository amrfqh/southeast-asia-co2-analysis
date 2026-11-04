# CO₂ Emissions Analysis: Malaysia and Southeast Asia (1990–2024)

## Project Overview

This project analyses annual carbon dioxide (CO₂) emissions in four Southeast Asian countries: **Malaysia, Indonesia, Thailand, and Singapore**, from 1990 to 2024.

Using Python, the project explores historical emissions trends, compares changes between 1990 and 2024, and applies statistical techniques to examine the relationship between time and annual CO₂ emissions.

The objective is to identify differences in national emissions patterns and provide a data-driven overview of CO₂ emissions trends across the selected countries.

## Research Objectives

- Examine annual CO₂ emissions trends from 1990 to 2024.
- Compare average annual emissions among the four countries.
- Calculate year-on-year (YoY) percentage changes.
- Compare emissions levels between 1990 and 2024.
- Evaluate the correlation between year and annual CO₂ emissions.
- Apply linear regression to estimate long-term emissions trends.

## Countries Included

- Malaysia
- Indonesia
- Thailand
- Singapore
- 
### Data Source & Attribution

- **Original dataset:** Annual CO₂ emissions per country
- **Publisher:** Our World in Data (OWID)
- **Original data source:** Global Carbon Budget
- **Dataset URL:** https://ourworldindata.org/grapher/annual-co2-emissions-per-country
- **Data coverage:** 1750–2024
- **Analysis period:** 1990–2024
- **Unit:** Million tonnes of CO₂ (MtCO₂)
- **Emissions scope:** Territorial CO₂ emissions from fossil fuels and industry, excluding land-use change emissions.

## Tools and Technologies

- **Python** – Data analysis and statistical computation
- **Pandas** – Data cleaning, manipulation, grouping, and analysis
- **NumPy** – Numerical computation and linear regression calculations
- **Matplotlib** – Data visualisation
- **Jupyter Notebook** – Interactive data analysis and documentation

## Methodology

The analysis follows these steps:

1. **Data collection:** Import the annual CO₂ emissions dataset from Our World in Data.
2. **Data inspection:** Examine dataset structure, missing values, duplicate records, and descriptive statistics.
3. **Data filtering:** Select Malaysia, Indonesia, Thailand, and Singapore for the 1990–2024 period.
4. **Data validation:** Check annual observations and identify missing years for each country.
5. **Data transformation:** Convert emissions from tonnes to million tonnes (MtCO₂).
6. **Trend analysis:** Calculate year-on-year percentage changes and average annual emissions.
7. **Comparative analysis:** Compare emissions in 1990 and 2024, including absolute and percentage changes.
8. **Correlation analysis:** Calculate Pearson correlation coefficients between year and annual CO₂ emissions.
9. **Regression analysis:** Apply simple linear regression to estimate emissions trends and calculate R² values.
10. **Data visualisation and export:** Generate charts and export statistical results into CSV files.

## Key Findings

### 1. Average Annual CO₂ Emissions (1990–2024)

| Country | Average emissions (MtCO₂) |
|---|---:|
| Indonesia | 419.19 |
| Thailand | 212.99 |
| Malaysia | 179.23 |
| Singapore | 46.19 |

Indonesia recorded the highest average annual CO₂ emissions, while Singapore recorded the lowest.

### 2. Emissions Comparison (1990–2024)

| Country | 1990 (MtCO₂) | 2024 (MtCO₂) | Percentage change |
|---|---:|---:|---:|
| Malaysia | 54.27 | 290.22 | +434.78% |
| Indonesia | 154.99 | 812.22 | +424.04% |
| Thailand | 86.56 | 267.76 | +209.32% |
| Singapore | 43.54 | 53.92 | +23.85% |

Malaysia recorded the highest percentage increase, whereas Indonesia experienced the largest absolute increase in emissions.

### 3. Average Year-on-Year Growth

| Country | Average YoY change |
|---|---:|
| Malaysia | 5.33% |
| Indonesia | 5.26% |
| Thailand | 3.52% |
| Singapore | 1.18% |

Malaysia had the highest average year-on-year percentage change over the study period.

### 4. Pearson Correlation Analysis

| Country | Pearson correlation (r) |
|---|---:|
| Malaysia | 0.9923 |
| Indonesia | 0.9769 |
| Thailand | 0.9529 |
| Singapore | 0.2227 |

Malaysia, Indonesia, and Thailand demonstrated strong positive linear associations between year and annual CO₂ emissions. Singapore showed a considerably weaker positive association.

### 5. Linear Regression Analysis

| Country | Estimated annual change (MtCO₂/year) | R² |
|---|---:|---:|
| Indonesia | 17.2791 | 0.9543 |
| Malaysia | 6.9571 | 0.9847 |
| Thailand | 5.5849 | 0.9079 |
| Singapore | 0.1152 | 0.0496 |

Indonesia had the highest estimated absolute annual increase based on the fitted linear regression model. Malaysia had the highest R², indicating the strongest linear fit among the four countries.

## Visualisations

The project includes:

- Average annual CO₂ emissions comparison.
- Annual CO₂ emissions trends by country.
- Malaysia-specific emissions trend.
- Comparison of emissions in 1990 and 2024.
- Pearson correlation visualisation.
- Linear regression plots for all four countries.

## Statistical Methods

- Descriptive statistics
- Percentage change calculations
- Pearson correlation coefficient
- Simple linear regression
- Coefficient of determination (R²)

## Limitations

- The analysis focuses on total national emissions rather than per-capita emissions.
- The dataset excludes CO₂ emissions from land-use change.
- Correlation and regression identify statistical relationships but do not establish causation.
- Population growth, GDP, energy consumption, industrialisation, and renewable energy use were not incorporated as explanatory variables.
- Simple linear regression may not adequately capture nonlinear emissions patterns or structural changes over time.

## Future Improvements

Potential extensions include:

- Comparing CO₂ emissions per capita.
- Investigating relationships between emissions and GDP.
- Examining population growth and energy consumption.
- Comparing renewable and non-renewable energy contributions.
- Applying multiple linear regression to investigate potential explanatory variables.
- Exploring forecasting techniques for future emissions trends.


## Author

GitHub: [amrfqh](https://github.com/amrfqh)

**Project focus:** Environmental Data Analysis | Python | Statistical Analysis | Data Visualisation
