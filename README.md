# AdventureWorks Data Warehouse Project

## Overview
This project focuses on building a comprehensive data warehouse for HR and Sales analytics using the AdventureWorks2014 database. The workflow includes setting up a staging database, importing data through SSIS ETL pipelines, transforming and cleaning data, and finally creating a data warehouse for analysis.

## Workflow
![Blank diagram](https://github.com/Bishworajkdk/ADW_DW_2014/assets/42015144/9722d9df-c737-46c8-81a0-a7d63a204910)
### 1. Staging Database Setup
- Created a staging database (`AWN_STG_Demo`) to store raw data from the source.
- Utilized SSIS ETL pipelines for efficient data extraction, transformation, and loading into the staging area.

### 2. Data Import
- Employed SSIS packages to import data from the source (`AdventureWorks2014`) into the staging database.
- Ensured data quality and consistency during the import process.

### 3. Data Transformation
- Implemented necessary transformations in the staging database to prepare the data for analysis.
- Cleaned, validated, and standardized data to meet the requirements of the data warehouse.

### 4. Data Warehouse Creation
- Established a data warehouse (`AWN_DW_Demo`) as the central repository for HR and Sales data.
- Migrated cleansed and transformed data from the staging database to the data warehouse.

### 5. Stored Procedure Utilization
- Implemented stored procedures to optimize the movement of data from the staging database to the data warehouse.

## Database Table Example
![Uploading Screenshot 2024-01-08 143336.png…]()
