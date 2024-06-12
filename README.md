# Ecommerce-Sales-Dashboard 
Ecommerce Sales Report - Power BI Project
Overview
This Power BI project visualizes the sales data of an eCommerce store using two CSV files: Orders and Details. The project provides insights into sales performance, customer behavior, product analysis, and order trends.

Project Files
Ecommerce Sales Report.pbix: Power BI report file.
orders.csv: Contains order information.
details.csv: Contains details of each order.
Features
Sales Dashboard: Visual representation of total sales, number of orders, average order value, and other key performance indicators.
Customer Analysis: Insights into customer demographics, purchasing patterns, and top customers.
Product Analysis: Data on top-selling products, product categories, and inventory status.
Order Trends: Analysis of order volume over time, including monthly and yearly trends.
Data Description
Orders CSV File
Column Name	Description
OrderID	Unique identifier for each order
CustomerID	Unique identifier for each customer
OrderDate	Date when the order was placed
ShipDate	Date when the order was shipped
ShipMode	Shipping method used
Sales	Total sales amount for the order
Profit	Profit made from the order
Discount	Discount applied to the order
Region	Region from which the order was placed
Details CSV File
Column Name	Description
OrderID	Unique identifier for each order
ProductID	Unique identifier for each product
ProductName	Name of the product
Category	Category of the product
Quantity	Quantity of the product ordered
UnitPrice	Price per unit of the product
TotalPrice	Total price for the product (Quantity * UnitPrice)
Installation and Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/ecommerce-sales-report.git
Open the Power BI file:

Install Power BI Desktop from Microsoft Power BI.
Open Ecommerce Sales Report.pbix in Power BI Desktop.
Load the data:

Ensure the orders.csv and details.csv files are in the same directory as the .pbix file.
Power BI will automatically load the data from these CSV files into the report.
Explore the dashboard:

Navigate through the different pages of the report to explore various visualizations and insights.
