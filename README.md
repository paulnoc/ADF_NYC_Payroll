# ADF NYC PAYROLL
Azure data factory project for a payroll management system.


## Project Introduction
The City of New York would like to develop a Data Analytics platform on Azure Synapse Analytics to accomplish two primary objectives:

  1. Analyze how the City's financial resources are allocated and how much of the City's budget is being devoted to overtime.
  2. Make the data available to the interested public to show how the City’s budget is being spent on salary and overtime         pay for all municipal employees.
     
You have been hired as a Data Engineer to create high-quality data pipelines that are dynamic, can be automated, and monitored for efficient operation. The project team also includes the city’s quality assurance experts who will test the pipelines to find any errors and improve overall data quality.

The source data resides in Azure Data Lake and needs to be processed in a NYC data warehouse in Azure Synapse Analytics. The source datasets consist of CSV files with Employee master data and monthly payroll data entered by various City agencies.

![alt text](https://github.com/paulnoc/aaf_ncp/blob/main/db_schemaprj5.jpeg?raw=true)

Source: Udacity Nanodegree program (Data Engineering with Microsoft Azure)

### Parameters
Custom values for the fiscal year are taken into account using a pipeline parameter (integer type); this value is then passed to a data flow level parameter in the filter activity.
