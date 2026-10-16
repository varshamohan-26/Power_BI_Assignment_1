# Power_BI_Assignment_1
Data Transformation and Data Modeling
# Power BI Assignment 1 – Data Transformation & Data Modeling
## Overview
This project focuses on e-commerce sales data analysis using Power BI. The objective was to clean, transform, merge, summarize, and model data using Power Query Editor and Power BI Model View.

## Dataset
The assignment uses three CSV files:
- List of Orders
- Order Details
- Sales Target

## Tools Used
- Microsoft Power BI Desktop
- Power Query Editor
- Power BI Data Model

## Data Transformation
The following operations were performed using Power Query:

- Imported the three CSV files into Power BI.
- Restricted the List of Orders table to the first 500 rows.
- Changed the Order Date column to the Date data type.
- Changed Amount and Target columns to Fixed Decimal Number.
- Applied proper case formatting to CustomerName.
- Created a new Location column by merging City and State.
- Created a Profit Margin column using Profit divided by Amount, expressed as a percentage.
- Created a conditional Profit Status column with Loss, Break-Even, and Profit categories.
- Identified and handled missing values and duplicate rows.
- Merged List of Orders and Order Details using Order ID to create the Orders Data table.
- Sorted orders by Order Date in descending order.
- Filtered orders by State for regional analysis.

## Grouping and Aggregation
Created summary tables using Group By in Power Query:

- Count of rows for each Order ID.
- Average Profit by Category.
- Total Target amount by Month of Order Date.

## Data Modeling
Created relationships in Power BI Model View:

- List of Orders and Order Details using Order ID (one-to-many relationship).
- Order Details and Sales Target using Category (many-to-many relationship).

## Conclusion
This assignment provided practical experience in data cleaning, transformation, merging, aggregation, and relationship creation in Power BI. These operations help prepare e-commerce sales data for further analysis and reporting.
<img width="1467" height="573" alt="Screenshot 2026-10-17 022107" src="https://github.com/user-attachments/assets/a77bd90f-c646-4979-986d-c8d37fb94080" />
