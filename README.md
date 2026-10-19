# East Africa Transport Emissions Dashboard

## Project Overview

An interactive Power BI project analysing transport-related CO₂ emissions across selected East African countries. The dashboard explores historical emissions trends, compares reported emissions across countries, and calculates year-on-year changes to support environmental analysis and ESG reporting.

## Objectives

* Compare transport CO₂ emissions across selected East African countries
* Visualise annual emissions trends.
* Calculate year-on-year percentage changes.
* Analyse each country's share of combined reported emissions.
* Communicate environmental findings through interactive Power BI visuals.

## Tools and Skills

- Microsoft Power BI
- Power Query for data preparation
- DAX for measures and calculations
- Data visualisation and analytical reporting
- Environmental, Social and Governance (ESG) data interpretation

## Dashboard Features

- Country and year slicers
- Cumulative transport emissions comparison
- Multi-country historical trend analysis
- Year-on-year emissions change
- Country contribution analysis
- Country ranking and key findings

## Data Source

Transport CO₂ emissions data from Our World in Data:

https://ourworldindata.org/grapher/co2-emissions-transport

The analysis is restricted to selected East African countries available in the dataset. See the source documentation for definitions, coverage, units and data updates.

## Methodology

- Emissions are aggregated by country and year using Power BI.
- Year-on-year change is calculated as the difference between the current year's emissions and the previous year's emissions, divided by the previous year's emissions.
- Country contribution is calculated relative to the combined emissions of the countries included in the analysis.
- Country and year slicers allow users to explore different reporting periods and country selections.

## Important Limitations

This project analyses national-level transport CO₂ emissions. These figures are not company-level emissions, fleet fuel consumption, emissions intensity per tonne-kilometre, or a complete greenhouse-gas inventory.

Differences between countries should be interpreted in context because population, economic activity, transport demand and freight volumes can differ. A reduction in total emissions alone does not establish improved transport efficiency.

## ESG Relevance

The dashboard demonstrates skills relevant to environmental data analysis, KPI monitoring, trend interpretation and ESG reporting. The findings may help frame questions for logistics operators about fuel use, fleet efficiency, route planning and emissions measurement. Company-level conclusions would require company operational data.

## How to Explore

1. Download the Power BI report from the `report/` folder.
2. Open it in Power BI Desktop.
3. Use the country and year slicers to explore the data.
4. Compare cumulative emissions, annual trends and year-on-year changes.

## Author

Created as a portfolio project to demonstrate Power BI analytics and environmental data interpretation.
