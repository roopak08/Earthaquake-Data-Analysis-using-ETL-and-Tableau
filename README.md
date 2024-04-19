
<h4 align='center'> Leveraging <a href='https://azure.microsoft.com/en-us' target='_blank'>Azure Cloud Services,</a> a daily data pipeline is in action, fetching and transforming earthquake data with a magnitude of 4.5 or higher. The pipeline taps into the <a href='https://earthquake.usgs.gov'>United States Geological Survey (USGS) </a> as its source, delivering real-time insights into earthquake activity over the past 7 days.</h4>

## Overview


Earthquake Data Analysis is an extensive project leveraging the capabilities of Azure services and GitHub to streamline the collection, processing, and analysis of critical earthquake data. Drawing inspiration from similar projects, this endeavor seamlessly acquires data from the United States Geological Survey (USGS) and applies Azure Data Factory for efficient ETL (Extract, Transform, Load) operations. The data is then deposited into Azure Data Lake Storage Gen2 for centralized storage and further undergoes transformations and exploratory analysis using Azure Databricks. Azure Key Vault plays a pivotal role in ensuring the security of sensitive credentials and secrets. Processed data is stored in an Azure SQL Database for optimized querying, with Azure Data Lake Gen2 serving as an intermediary and repository for refined datasets. Ultimately, the project utilizes Tableau to create dashboards that offer valuable insights into recent seismic activities.

## Tools 

To build this project, the following tools were used:

- Azure Databricks
- Azure KeyVault
- Azure Active Directory
- Azure DataLake Gen 2
- Azure Blob Storage
- Azure Data Factory
- Azure SQL Database
- Azure Monitor
- Azure Cost & Billing
- Tableau
- Pyspark
- SQL
- Git

## Architecture

Following is the architecture of the project.

<p align='center'>
  <img src='https://github.com/roopak08/Earthaquake-Data-Analysis-using-ETL-and-Tableau/blob/main/Resources/architecture.png' height=385 width=1100>
</p>  

## Dashboard

These are the dashboards made in Tableau. 

Tableau Public Links: 

<a href='https://public.tableau.com/app/profile/muhammad.waqar.gul/viz/earthquake_dashboard_16952292430070/Dashboard1'>USGS Earthquake Dashboard</a>

<a href='https://public.tableau.com/app/profile/muhammad.waqar.gul/viz/historical_earthquake_dashboard/Dashboard12'>Historical Earthquake Dashboard</a>

<p align='center'>
  <img src='https://github.com/roopak08/Earthaquake-Data-Analysis-using-ETL-and-Tableau/blob/main/Resources/usgs_dashboard.png' height=400 width=650>
</p>  

<p align='center'>
  <img src='https://github.com/roopak08/Earthaquake-Data-Analysis-using-ETL-and-Tableau/blob/main/Resources/hist_dashboard.png' height=400 width=650>
</p>  
