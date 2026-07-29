
# Global Health & Life Expectancy Dashboard

AnalystLab Africa — Batch B Internship Final Capstone Project
Author: Justinah Ajayi

## Project Overview
This project analyzes global health and life expectancy trends using the World Bank's World Development Indicators (WDI) dataset. It examines how life expectancy has evolved since 1960, how it varies by region and income group, and how it relates to health expenditure and maternal mortality — culminating in an interactive Power BI dashboard.

## Objective
To identify which regions and income groups lag behind in health outcomes, and to assess whether health expenditure (as % of GDP) reliably predicts better outcomes — supporting evidence-based recommendations for global health stakeholders.

## Dataset
- Source: [World Bank World Development Indicators](https://datatopics.worldbank.org/world-development-indicators/)
- Files used: WDICSV.csv (main indicator data), WDICountry.csv (region/income group metadata)
- Coverage: 217 countries/territories + regional/income aggregates (264 entities), 1960–2024
- Key indicators: Life expectancy at birth, current health expenditure (% of GDP), maternal mortality ratio

## Tools Used
- Power Query (Power BI): data cleaning, filtering, unpivoting, and merging
- Power BI Desktop: dashboard design and interactive visualization
- Microsoft Word / PDF: final report

## Data Cleaning Steps
1. Promoted headers and set correct data types
2. Filtered to health-related indicators only
3. Unpivoted year columns (wide → long format)
4. Removed nulls and duplicate rows
5. Merged in Region and Income Group from country metadata

Full details are documented in the Final Report (PDF).

## Dashboard Features
- KPI Cards: Avg. Life Expectancy (2022), Avg. Health Expenditure (% GDP), Maternal Mortality Ratio, Countries Covered
- Trend Chart: Life expectancy by region, 1960–2024
- Comparison Charts: Top 10 countries by life expectancy; Top 15 countries by health expenditure (% GDP)
- Slicers: Region, Income Group, Year — for interactive filtering

## Key Findings
- A persistent life expectancy gap remains between Sub-Saharan Africa (~65 years) and other regions (~75–83 years)
- Top life-expectancy countries are mostly small, high-income territories (Monaco, San Marino, Liechtenstein) rather than large economies
- High health expenditure as % of GDP does not reliably predict top life-expectancy rankings
- Global maternal mortality remains high at ~133 deaths per 100,000 live births
- A visible dip in life expectancy appears across most regions around 2020–2021, consistent with COVID-19 impact

Full insights and recommendations are in the Final Report (PDF).

## Repository Contents
