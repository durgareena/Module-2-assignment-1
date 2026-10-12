# 📊 Power BI – Data Cleaning and Transformation Assignment

## 📌 Project Overview

This project focuses on data import, data cleaning, data transformation, data aggregation, and data modeling using Microsoft Power BI. The assignment demonstrates how raw CSV datasets can be transformed into structured data for analysis using Power Query Editor.

## 📂 Dataset Structure

The assignment consists of three CSV files:

* **List of Orders.csv** – Contains order-related information, including Order ID, Order Date, Customer Name, City, and State.
* **Order Details.csv** – Contains order details used for analyzing Amount, Profit, Category, and Sub-Category.
* **Sales Target.csv** – Contains sales target information used for target-based analysis.

## 🧹 Data Cleaning and Transformation

The following data preparation steps were performed using Power Query Editor:

* Imported three CSV files into Power BI.
* Limited the List of Orders table to the first 500 rows.
* Changed Order Date to the Date data type.
* Converted Amount and Target columns to Fixed Decimal Number.
* Applied Proper Case formatting to CustomerName.
* Merged City and State columns to create a Location column.
* Created a Profit Margin column using Profit / Amount and formatted it as a percentage.
* Created a conditional column named Profit Status.
* Checked missing values using Column Quality.
* Identified and removed duplicate records based on Order ID, as specified in the assignment.
* Merged List of Orders and Order Details using Order ID to create Orders Data.
* Sorted orders by Order Date in descending order.
* Applied filters to analyze orders from a specific state, such as Tamil Nadu.

## 📈 Data Aggregation

The following aggregations were performed:

* Count of Order ID
* Average Profit by Category
* Total Amount by Sub-Category
* Total Sales Target by Month of Order Date

These aggregations help summarize order details and sales target information for further analysis.

## 🔗 Data Modeling

Established relationships between the tables using Power BI's Manage Relationships feature:

* List of Orders and Order Details using Order ID.
* Order Details and Sales Target using Category.

Verified that the relationships were active and correctly defined.

## 🛠️ Tools and Technologies

* Microsoft Power BI
* Power Query Editor
* Data Transformation
* Data Cleaning
* Data Aggregation
* Data Modeling
* Table Relationships

## 🎯 Key Learning Outcomes

* Importing multiple datasets into Power BI.
* Transforming and formatting columns using Power Query.
* Creating custom and conditional columns.
* Identifying missing values and duplicate records.
* Merging tables using common columns.
* Applying sorting and filtering operations.
* Performing grouping and aggregation.
* Establishing relationships between multiple tables.

## 📝 Conclusion

This assignment provided hands-on experience in preparing and transforming datasets using Power BI. It strengthened my understanding of Power Query, data quality checks, aggregation techniques, and data modeling, which are essential skills for a Data Analyst.
