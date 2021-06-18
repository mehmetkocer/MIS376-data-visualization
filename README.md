# MIS376-data-visualization
This repository created for a data visualization project that given in scope of MIS376 Knowledge Mapping and Data Visualization Course.

### Part A - A brief description of the problem.
This project intended to investigate the effects of lockdown periods on daily new cases and daily vaccination rate specifically in Turkey. There are several lockdown periods include weekends and some complete, long-period (longer than one week) lockdowns. That project aims to visualize the effects of these variables on covid statistics and demonstrate the strength of the relationship if exists.

### Part B - Getting and Preparing Data

In this project, there are three data sources. 

First data is from ourworldindata.org, which is names as owid-covid-data.csv and it contain various covid related columns for every counrty across the globe.It can downloaded as csv with few clicks so there is not much effort to get that data.  We use some of the columns from the data and we only use rows which are related with Turkey. In our case we use 'new_cases' column. 

Second data 'df_cities_risk_weekly.csv' is not avaiable in the internet and we collect it from web news with web scraping techiques. The reason why it is now avaiable can be weekly publishing mechanism of the government sources on each separates dates and therefore there is not a colletion of all week together. Our data_scraping_weekly_risk_rate.ipynb notebook created for that purpose and at the end it export 'df_cities_risk_weekly.csv' as an complete collection of weeks. It contain 10-week data of city risk map from 16 march to 23 may 2021.
