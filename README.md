# JCars-Logistics-PowerBI-Project
Power BI Sales Dashboard using PostgreSQL (Aiven)
Project Objective

This project analyzes the sales performance of JCars Logistics using Power BI connected to a PostgreSQL database hosted on Aiven. The objective is to provide management with an interactive dashboard that monitors key business metrics, identifies sales trends, evaluates profitability, and supports data-driven decision-making.

Data Import into Aiven

The dataset was first prepared and imported into an Aiven PostgreSQL database using DBeaver. The import process involved:

Creating a PostgreSQL database on Aiven.
Connecting DBeaver to the Aiven database using the provided SSL credentials.
Creating the required table.
Importing the CSV dataset into PostgreSQL.
Verifying that all records were successfully imported before connecting Power BI.
Connecting Power BI to the Database

Power BI Desktop was connected directly to the Aiven PostgreSQL database by:

Selecting Get Data → PostgreSQL Database.
Entering the Aiven host, port, database name, username, and password.
Enabling SSL mode as required by Aiven.
Loading the required table into Power BI.
Performing additional data cleaning and transformations using Power Query.
Measures and Calculations

The dashboard includes several calculated measures, including:

Total Revenue
Units Sold
Number of Orders
Gross Profit
Gross Profit Margin (%)
Average Order Value
Average Customer Rating
Revenue per Order
Gross Profit per Order
Percentage Discount
Service Level Performance
Dashboard Visuals

The dashboard contains the following visualizations:

KPI Cards
Total Revenue
Units Sold
Number of Orders
Gross Profit
Average Customer Rating
Revenue Trend by Month (Line Chart)
Top Car Makes / Models by Revenue
Revenue by Region
Salesperson Performance

Interactive slicers for:
Region
Branch
Car Make
Order status
Payment Status

Key Insights
Revenue remained positive throughout the reporting period.
Certain regions consistently generated the highest sales revenue.
A small number of car models contributed a significant share of total revenue.
Higher discounts generally reduced gross profit.
Most deliveries met the expected delivery target.
Salesperson productivity varied significantly across the organization.
Customer ratings showed little relationship with revenue generated.

Recommendations
Increase inventory for top-performing car models.
Review discount policies to improve profitability.
Improve delivery performance in slower-performing regions.
Provide additional training for lower-performing sales representatives.
Continue using Power BI dashboards for performance monitoring and strategic decision-making.
Tools Used
Power BI Desktop
PostgreSQL
Aiven Cloud Database
DBeaver

The skills demonstrated are;
1.Data Cleaning
2.SQL
3.PostgreSQL
4.Power Query
5.DAX
6.Data Modeling
7.Data Visualization
8.Dashboard Design
9.Business Intelligence
10.Data Storytelling
