## Polling Dynamics Navigator

### Table of Content

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Modelling and Analysis](#data-modelling-and-analysis)
- [Results or Findings](#results-or-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

  
### Project Overview

This analysis is Polling Dynamics Navigator for Voltrox. We are considering voters' assessment by gender, revenue, profit, race, country, and education.

![Polling Analytics](https://github.com/AndersonOzakpo/Polling-Dashboard/assets/169863628/30d5f1f9-e05c-440c-bc8c-5f61eb8bfa97)

### Data Sources

Voltrox Test Files: The primary dataset used for this analysis is the "Voltrox_test_dataset.csv" file containing detailed information about voters.

### Tools Used

- Google Sheet - Data cleaning
  - [Try Google Sheet here](https://docs.google.com/spreadsheets/)
 
### Data Cleaning

The following tasks were performed:
1. Data loading and inspection
2. Handling missing values
3. Removing duplicate values
4. Properly formatting the data
5. Ensured data was uniform

### Exploratory Data Analysis

The EDA involved exploring the datasets to answer the following questions:
1. What part of the region is bringing in more Profit?
2. What part of the region is less profitable?
3. Is there a correlation between educated and less-educated voters?
4. What else does the data say?

### Data Modelling and Analysis

The following tasks were performed:
1. Definition and computation of derived metrics
2. Computed the total sales with  unit price and duration
3. Leveraged the use of Pivot tables for data aggregation

### Results or Findings
The analysis results are as follows:
1. Product name is the dataset responsible for conversion. This will be done by upselling "free" customers who spend longer duration
2. Japan seems to be most profitable if both voters and no-voters are considered. However, the USA is the most profitable if only voters are considered.
3. Malaysia is the least profitable across board
4. The correlation between educated and uneducated is that the majority of voters are White
5. Argentina and Spain have the highest Average Revenue Per User (ARPU) of $315 and $124 respectively			

### Recommendations
Based on the analysis, we recommend the following actions:
1. Device entice ways to involve black communities involvement in elections
2. The data shows a strong correlation between voters to education hence providing affordable education and incentives for learning will positively impact voters' participation
3. Scrutinize the Malaysia team to understand their challenges to better position them for coming elections
4. Invest interests in Argentina and Spain to involve in elections owing to growth and earning potentials of these economies.

### Limitations
There were duplicate data, and most of the fields were not uniform for instance, "f" and "female" were both filled in the gender field. Also, there were null values.

### References
No external resources used

