# AtliQ Hardware — Retail Sales ETL Pipeline (Databricks & PySpark)

## Project Overview
An end-to-end ETL (Extract, Transform, Load) pipeline built in Databricks using PySpark. The pipeline processes retail sales data for AtliQ Hardware extracting raw data, transforming and enriching it, loading it into clean tables, and generating business insights through aggregation and visualisation.

## Tools & Technologies
- Databricks (Free Edition)
- PySpark (Spark DataFrames)
- Spark SQL
- Python

## Pipeline Stages

### 1. Extract
Loaded raw customer and sales data into Spark DataFrames, representing
dimension (customer) and fact (sales) data.

### 2. Transform
- Calculated revenue by multiplying sold quantity by unit price
- Joined sales data with customer dimension data using a left join
- Aggregated total revenue by market, region and platform

### 3. Load
Saved the clean, transformed data as permanent, queryable tables in Databricks
using saveAsTable.

### 4. Visualisation
Created revenue insights using Spark SQL and built-in Databricks charts,
including a revenue-by-market bar chart.

## Key Skills Demonstrated
- Building an end-to-end ETL pipeline
- PySpark DataFrame operations (withColumn, join, groupBy, agg)
- Data transformation and enrichment
- Mixing Python and SQL within a single Databricks notebook
- Saving and querying tables
- Data visualisation

## Key Concepts
| Concept | Description |
|---------|-------------|
| Extract | Loading raw data into Spark DataFrames |
| Transform | Cleaning, joining and calculating new metrics |
| Load | Saving clean data as queryable tables |
| PySpark | Python API for Apache Spark (big data processing) |
| Spark SQL | Running SQL queries on Spark data |

## Files
- `AtliQ_ETL_Pipeline.ipynb` — The complete Databricks notebook
- `Databricks_Screenshots/` — Screenshots of the pipeline and visualisations

## About Me
**Sree Lalitha Prudhvi**
Data Analyst 
Glasgow, Scotland, UK
sreelalitha52@gmail.com
