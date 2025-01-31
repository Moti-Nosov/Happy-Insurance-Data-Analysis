# Happy Insurance Data Analysis Project: 
This is a data analysis project based on historical data of insurance company. The objective is to present analytical information about company's performance, by looking for significant trends in various types of indicators.

## Description
This project demonstrates the process of pulling data from a database, performing ETL in Power Query, building a star-schema model in Power Pivot, making quick and insightful visualisations within Microsoft Excel, creating a semantic layer in PowerBI, and making interactive dashboards for data visualization and further analysis.

## Files and Structure
The project cosists of 4 files:
- Happy Insurance Project.xlsx - ETL processed data from database to star schema using M language. Development of a tabular model (Power Pivot) that provides quick and high-quality answers to the organization's business questions with minimum effort
- Happy Insurance Project.pbix - Interactive reports and visualization with Power BI
- Happy Insurance Project.dax - DAX-query script for complex KPI's
- Happy Insurance Project.pptx - presentation of an overview of the project and key insights

## Detailed Explanation of Each Step:
### 1. ETL:
  - Data loading to Power Query
  - Creating the Dim & Fact tables
  - Data Clearing
### 2. Power Pivot:
  - Star Scheme: Creating the table connections by using the SK columns we created in the ETL step
  - Defining the measures, calculated columns and KPIs
  - Building a dashboard by using all we had created
### 3. Power BI: Semantic Layer:
  - Loading the Model into Power BI
  - Changing the names of tables and columns to daily used names
  - Formatting the proper Data Types and Sorting by needed columns
  - Hiding unnecessary columns. For example: SK columns and column we have placed in a hierarchical group
  - Building a measure table and defining new measures
  - Building the dashboard by using graphs and KPIs
  - Using DAX Studio to build complex measures
### 4. Analysis and Conclusions:
  - Drawing findings based on the outcomes from dashboards and graphs
