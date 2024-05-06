# AdventureWorks Data Visualization 

Welcome to the AdventureWorks Visualization Project! This project involves using the AdventureWorks dataset to create various insightful visualizations in Power BI. The project encompasses data preprocessing, data modeling, and the creation of interactive dashboards for key business metrics. Below, you'll find a comprehensive overview of the project's structure, processes, and key components.

Interact with Dashboards here
https://github.com/AnushcaJoshi/AdventureWorks_Viz/blob/main/AdventureWorks_Viz.pbix

## Table of Contents
1. [Introduction](#introduction)
2. [Data Overview](#data-overview)
3. [Data Preparation and Cleaning](#data-preparation-and-cleaning)
4. [Data Modeling](#data-modeling)
5. [Dashboards](#dashboards)
6. [DAX Measures and Calculations](#dax-measures-and-calculations)
7. [Conclusion](#conclusion)

## Introduction

The purpose of this project is to analyze the AdventureWorks dataset using Power BI and create visualizations that provide insights into key business metrics such as KPI, product details, customer behavior, and manufacturing. The goal is to leverage data to drive decision-making and identify opportunities for improvement.


There are two different types of tables present in this project 
 - Lookups: Tables with non-numeric values like Customer, Product categories, Product subcategories, Products, Calendar
 - Non-Lookups: Tables with numeric values such as Sales and Returns

Lookups are connected to data through Primary Key


## Data Overview

The AdventureWorks dataset contains information across multiple categories:

- **Customer Information**: Details about customers and their purchasing behavior.
- **Product**: Information about products available for sale.
- **Subproduct**: Additional details and attributes of products.
- **Calendar**: Time-related data for sales and returns.
- **Territory Sales and Returns**: Data about sales and returns across different territories.

## Data Preparation and Cleaning

In Power Query, the data was transformed and cleaned to ensure consistency and accuracy:

- **Data Cleaning**: Removed duplicates, handled missing values, corrected any errors, renamed columns and tables, rounded decimal values, changed data types.
- **Data Transformation**: Created new columns and data to support analysis.
![Screenshot (832)](https://github.com/AnushcaJoshi/AdventureWorks_Viz/assets/111639602/81cbe210-6858-40b9-8e79-cc79533134b7)


## Data Modeling

Data modeling in Power BI involved connecting the various columns and tables to form a snowflake schema:

- **Relationships**: Established primary and secondary key relationships between tables.
- **Schema**: Created a snowflake schema to model complex relationships and enhance query performance.
![Screenshot (831)](https://github.com/AnushcaJoshi/AdventureWorks_Viz/assets/111639602/7f5b3150-c5bd-4bd0-929e-b92297b1fdfd)


## Dashboards

The project includes several dashboards to visualize and analyze key metrics:

- **KPI Dashboard**: Displays key performance indicators such as sales revenue and profit margins.
  
![Screenshot (833)](https://github.com/AnushcaJoshi/AdventureWorks_Viz/assets/111639602/093b9309-29fd-4692-83c0-19c02d1f728e)


- **Product Details Dashboard**: Provides insights into product performance, sales trends, and product attributes.
  
![Screenshot (834)](https://github.com/AnushcaJoshi/AdventureWorks_Viz/assets/111639602/001d6928-17ab-4811-a806-6ea52064c871)


- **Customer Behavior Dashboard**: Analyzes customer purchasing behavior, including segmentation and trends.
  
![Screenshot (835)](https://github.com/AnushcaJoshi/AdventureWorks_Viz/assets/111639602/be340b7a-9b78-4e08-881b-44ea0b17ce81)


- **Manufacturing Dashboard**: Focuses on manufacturing processes and metrics for production efficiency.
  
![Screenshot (836)](https://github.com/AnushcaJoshi/AdventureWorks_Viz/assets/111639602/ba46f2f9-08d1-40a3-80e5-1f2aa8d94686)


- **Low-High End Product Dashboard**: Compares low-end and high-end products to identify market trends and opportunities.
  
![Screenshot (837)](https://github.com/AnushcaJoshi/AdventureWorks_Viz/assets/111639602/2ede7f0d-2c37-4ef1-ba49-f88a374f292c)


## DAX Measures and Calculations

To support the visualizations and dashboards, DAX measures and calculations were created:

- **Measures**: Calculated key metrics such as sales totals, profit margins, and customer counts.
- **Fields**: Created calculated columns and fields to support analysis and visualization.

## Conclusion

The project effectively demonstrates how the AdventureWorks dataset can be used to generate meaningful insights through Power BI visualizations. By understanding customer behavior, product performance, and manufacturing processes, businesses can make informed decisions and optimize operations.
---

Thank you for reviewing the AdventureWorks Visualization Project! Please don't hesitate to reach out if you have any questions or feedback.
