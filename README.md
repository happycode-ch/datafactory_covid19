# Designing a Data Platform for Covid-19 Analysis and Prediction in the EU and UK
### An Azure Data Factory-Focused Data Engineering Solution

Developer:  Anthony Calek \
Platform:  Microsoft Azure \
Date:  Jan 2024 

## Project Overview 

### Project Ojective:
This project focuses on developing a data platform for analyzing, reporting on and predicting the impact of the Covid-19 pandemic within the EU and UK, utilizing case numbers, mortality rates, hospital and ICU admissions, and testing statistics.

### Solution Technologies
Data Source:	HTTP, CSV \
ETL:	Azure Data Factory (ADF) \
Storage: 	Azure Blob Storage & Azure Data Lake Storage (ADLS) \
Data Warehouse:	Azure DB \
Analysis and Transformation: 	ADF - Data Flows, HDInsight & Databricks \
Reporting: 	Microsoft Power BI

### Data Sources:
Covid-19 Data:	European Center for Disease Prevention and Control, https://www.ecdc.europa.eu/en/covid-19/data
Population Data:	Eurostat, https://ec.europa.eu/eurostat/web/products-datasets/-/tps00010

### Project Deliverables:
The project creates a data platform designed for three key functions: facilitating Data Analysis, generating Reports, and supporting Machine Learning Models. It utilizes Azure Blob Storage for population data and Azure Data Lake Storage Gen2 for storing raw, transformed, and presentation datasets tailored for data science and analysis. For reporting, an Azure SQL Database integrates with Power BI to deliver insightful reports and dashboards. 

Additionally, this project's secondary aim is to explore and learn about Azure Data Factory's use as a Data Engineering platform as part of a comprehensive course created by Ramesh Retnasamy.
Links: https://www.udemy.com/course/learn-azure-data-factory-from-scratch/, https://www.linkedin.com/in/ramesh-retnasamy/

Link Project Homepage: https://www.happycode.ch/projects-1/covid19dataplatform-kaccx
