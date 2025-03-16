# Tokyo Olympics 2021 Medal Analysis

## Project Overview
An Azure-powered Power BI project showcasing advanced data engineering and visualization skills, featuring medal counts for 93 countries from the Tokyo Olympics 2021. This project demonstrates a comprehensive Azure data pipeline leveraging Azure Data Lake Storage, Azure Databricks with PySpark, and Azure Synapse Analytics to deliver actionable insights through an interactive report.

## Tools and Technologies
- **Power BI**: For advanced data visualization and reporting.
- **DAX**: To create calculated tables (e.g., CountryList, CountryMedals) and measures (e.g., TotalMedals) for data modeling.
- **Azure Data Lake Storage**: Stored raw medal data in a scalable, secure cloud storage solution.
- **Azure Databricks**: Processed and transformed data using PySpark for efficient data preparation.
- **Azure Synapse Analytics**: Leveraged as a serverless SQL pool for data ingestion, querying, and optimization.
- **Microsoft Remote Desktop**: Facilitated file transfer between a Windows VM and Mac.

## Methodology
1. Ingested raw Tokyo Olympics medal data into Azure Data Lake Storage, establishing a centralized data repository.
2. Utilized Azure Databricks to process and clean the data, writing PySpark scripts for transformations and aggregations.
3. Engineered a data pipeline using Azure Synapse Analytics to import and further process MedalsView data from the processed lake storage.
4. Modeled the data with DAX to summarize Gold, Silver, and Bronze medal counts across 93 countries.
5. Designed an interactive Matrix visual with conditional formatting, sorted by a custom TotalMedals measure.
6. Published the report to Power BI Service for accessibility and scalability.

## Screenshots
 [NewTokyoOlympicsReport.pdf](https://github.com/user-attachments/files/19273795/NewTokyoOlympicsReport.pdf)
 
*The Matrix visual displays 93 countries with their Gold, Silver, and Bronze medal counts, sorted by total medals, demonstrating an end-to-end Azure-driven data engineering workflow.*

## Outcome
Successfully delivered a comprehensive visualization of medal data for 93 countries, showcasing expertise in Azure Data Engineering, PySpark processing, and Power BI proficiency.
