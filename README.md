# Udacity_NYCPayroll

## Project Introduction
The City of New York would like to develop a Data Analytics platform on Azure Synapse Analytics to accomplish two primary objectives:
1.	Analyze how the City's financial resources are allocated and how much of the City's budget is being devoted to overtime.
2.	Make the data available to the interested public to show how the City’s budget is being spent on salary and overtime pay for all municipal employees.

As a Data Engineer, we are required to create high-quality data pipelines that are dynamic, can be automated, and monitored for efficient operation. 
The source data resides in Azure Data Lake and needs to be processed in a NYC data warehouse. The source datasets consist of CSV files with Employee master data and monthly payroll data entered by various City agencies.

We use Azure Data Factory:
1. Copy data from ADLS to Azure SQL DB
2. Transform data
3. Store transformed data into Azure SQL DB and ADLS
4. Connect Azure Synapse Analytics to ADLS to read the transformed data
