# IMSales-Data-Warehouse---Microsoft-Fabric-ETL-Pipeline
Hands-on implementation of a dimensional data warehouse for IMSales, a B2B food trading company importing specialty products and selling to European retailers. 

## Core Skills:
Star schema design, Fabric Dataflows Gen2, Pipelines, SQL DW, data quality validation. (add image)

## Project Overview
- **Source**: IMSALES OLTP (Orders, Order Details, Clients, Products, etc. ~20-50k rows).
- **DW**: Fabric SQL Warehouse with surrogate keys, hierarchies enabled.
- **ETL**: Full pipeline from raw → staging → DW with quality checks.
- **Business value**: Enables sales by product/client/staff over time; inventory trends; regional analysis. 


