# IMSales-Data-Warehouse---Microsoft-Fabric-ETL-Pipeline
Hands-on implementation of a dimensional data warehouse for IMSales, a B2B food trading company importing specialty products and selling to European retailers. 
**Business value**: Enables sales by product/client/staff over time; inventory trends; regional analysis. 

## Core Skills:
Star schema design, Fabric Dataflows Gen2, Pipelines, SQL DW, data quality validation. 
<img width="1584" height="846" alt="image" src="https://github.com/user-attachments/assets/ad304f27-9c02-4cfc-ace9-21445eb9abb2" />


## Project Overview
- **Source**: IMSALES OLTP (Orders, Order Details, Clients, Products, etc. ~20-50k rows).
- **DW**: Fabric SQL Warehouse with surrogate keys, hierarchies enabled.
- **ETL**: Full pipeline from raw → staging → DW with quality checks.



