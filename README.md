# Project Overview

## Objective
The goal of this project is to analyze coffee orders to gain insights into sales performance, customer behavior, and product popularity. <br>
This analysis will help in making data-driven decisions to enhance business operations and increase sales.

### Steps followed to complete the project

### 1. Data Preparation

a.  **Open the Excel File**:
   - Open the `coffeeOrdersData.xlsx` file in Excel.

b.  **Inspect Each Sheet**:
   - Review the data in each sheet to understand its structure and content ( `orders`, `customers`, `products`).

c.  **Clean Data**:
   - Clean the data by removing duplicates if necessary.
   - Ensure columns have appropriate headers and data types.

###  2. Data Integration:

   - Combine data from different sheets (orders, customers, products) to create a comprehensive dataset for analysis.
   - Use the `XLOOKUP` and `INDEX MATCH` functions for the purpose of combining data from different sheets based on `Customer ID` and `Product ID`.
   - Ensure that the relationships between orders, customers, and products are correctly established using unique identifiers (`Customer ID`, `Product ID`).
   - Populate Sales Column (`Quantity` x `Unit Price`)

### 3. Data Enrichment: 

   - Introduce new columns (`Coffee Roast Type`, `Roast Type Name`, `Loyalty Card`) for the purpose of visualizing data in an understandable manner.
   - Use `IF` and `XLOOKUP` functions to populate these columns.

### 4. Identify Trends and Patterns:

   - Use pivot tables to analyze data by different dimensions (e.g., by month, by country)
   - Following Pivot Tables are constructed - `Total Sales`, `CountryByBarChart`, `Top5Customers`, etc.

### 5. Data Visualization:
     
   - Create pivot charts using pivot tables.
   - Consolidate key charts and metrics into the `Dashboard` sheet.
   - Use slicers and Timeline to make the dashboard interactive (Insert > Slicer).
   - Connect Slicer/Timeline to Multiple Pivot Charts.

## Dashboard Snapshot

![coffeeOrdersProject xlsx - Excel 11-06-2024 19_21_44](https://github.com/nivisdata-analysis/Excel-project-coffee-sales/assets/171444078/e978bce3-a470-49a2-8ffb-675d39e7e39f)



