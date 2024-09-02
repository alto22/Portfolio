# Visual_Analysis_Copenhagen_Apartment_Market


> MSc Business Administration and Data Science

> Submission Date: 18.12.23


## Authors
- Aleksander Torp


## Abstract
This project involved scraping apartment prices and locations from an online marketplace, subsequent extraction of unique addresses, and retreiving corresponding coordinates using Google’s Geocoding API using Python.  Additionally, demographic data for each region in Copenhagen was retrieved from Danish statistical banks and municipal websites. The data was then stored in a PostgreSQL database, organized using a snowflake schema, and connected to Tableau for visualization. The dashboard enabled various stakeholders, including buyers, sellers, investors, and policymakers, to dynamically explore the current status of Copenhagen’s apartment market, examine trends, and derive insights tailored to the region(s), price and apartment size range set by the user. The final dashboard featured two interactive views, market overview and price forecasting:

«Market overview» displayed median price developments, sales frequency, median square meter prices, apartment size distributions, and age demographics for regions of interest. A heatmap aided spatial analysis of apartment prices and concentrations, with aggregated data at the building level to ensure anonymity. 

«Price forecasting» extended the functionalities of the «Market overview» view in assessing the apartment market with ARIMA-based forecasting for future price trends. 

The report showcases a potential usecase of the dashboard and describes a visual analysis of the Copenhagen apartment market, specifically targeting self-owned apartments sized 80-100 square meters.

Keywords: Python, Web scraping, PostgreSQL, Tableau, ARIMA
