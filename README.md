# WHO GLASS Antibiotic Consumption Dashboard

## Project Overview

This project presents an interactive Power BI dashboard analysing antimicrobial consumption data reported through the World Health Organization (WHO) Global Antimicrobial Resistance and Use Surveillance System (GLASS) from 2016–2023.

The dashboard examines antibiotic consumption using Defined Daily Doses (DDD) and DID (DDD per 1,000 inhabitants per day), explores antibiotic distribution across the WHO AWaRe categories, compares consumption patterns across countries and WHO regions, and assesses country performance against the current ≥70% Access target. > **Target note:** The ≥70% Access target is the current 2030 global target. In this project, it is applied as a benchmark to the historical 2016–2023 GLASS-AMU observations; it should not be interpreted as having been the target throughout the entire study period.

Antimicrobial resistance (AMR) is a major public health challenge globally, and monitoring antimicrobial consumption is an important part of antimicrobial stewardship.

The project aimed to explore:

- antibiotic consumption patterns over time;
- differences between countries and WHO regions;
- Access, Watch and Reserve antibiotic consumption;
- country performance against the current ≥70% Access target; and
- changes in the number of countries contributing data over time.

The analysis also includes validation checks to account for differences in reporting coverage and to ensure that DID is aggregated at the appropriate country-year level.

## Dashboard Preview
The interactive dashboard provides a summary of reporting coverage, AWaRe antibiotic distribution, country and regional consumption patterns, temporal trends in DID, and performance against the current ≥70% Access target.

Users can filter the dashboard by country and year to explore changes in antibiotic consumption and AWaRe composition.

![WHO GLASS Antibiotic Consumption Dashboard](dashboard-overview.png)

## Analytical Questions

The analysis was designed to answer the following questions:

- How has antibiotic consumption changed across reporting countries between 2016 and 2023?
- How does antibiotic consumption vary across countries and WHO regions?
- What proportion of reported antibiotic consumption falls within the Access, Watch and Reserve (AWaRe) categories?
- Which countries meet the WHO benchmark of at least 70% of total antibiotic consumption coming from the Access category?
- How has the number of countries reporting antimicrobial consumption data changed over time?
- To what extent do changes in reporting coverage affect observed trends in antibiotic consumption?

## Data Source & Structure

**Primary data source:** [WHO Global Antimicrobial Resistance and Use Surveillance System (GLASS) – Data Visualization Dashboard](https://worldhealthorg.shinyapps.io/glass-dashboard/)

The analysis uses national antimicrobial use data from the World Health Organization (WHO) Global Antimicrobial Resistance and Use Surveillance System (GLASS-AMU).

The dataset analysed in this project covers **2016–2023** and contains data for **73 reporting countries and territories** across the six WHO regions. Reporting coverage differs by year, increasing from 36 countries in 2016 to 65 in 2023.

### Key Variables

The analysis focuses on:

- **Country/Territory** – reporting country or territory.
- **Year** – reporting year from 2016 to 2023.
- **WHO Region** – geographical region assigned by WHO.
- **DDD (Defined Daily Dose)** – a standardised unit used to measure antibiotic consumption.
- **DID** – Defined Daily Doses per 1,000 inhabitants per day, allowing consumption to be compared between populations.
- **AWaRe Category** – WHO classification of antibiotics into Access, Watch and Reserve groups, with additional records not classified/recommended under AWaRe.

### Reporting Coverage

Not all countries reported data in every year. The number of reporting countries increased over the study period:

| Year | Reporting Countries |
|------|---------------------|
| 2016 | 36 |
| 2017 | 42 |
| 2018 | 44 |
| 2019 | 50 |
| 2020 | 53 |
| 2021 | 60 |
| 2022 | 64 |
| 2023 | 65 |

These differences in reporting coverage were considered when interpreting temporal trends and led to additional sensitivity analysis using countries with consistent reporting across the study period.
