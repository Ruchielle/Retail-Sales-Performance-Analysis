## Retail Sales Performance Analysis

### Project Overview 

 - This project focused on turning raw data into clear, easy to understand results by cleaning and standardizing the records, adding custom calculations, and examining trends using Pivot Tables, all brought together in an interactive dashboard that tracks performance across products, regions, months, order categories, discounts, and sales representatives.
 - Using Microsoft Excel, this analysis turned raw retail sales data into clear business information to help with better understanding of the sales performance.


### Project Objectives 
 
 - Measure overall retail sales performance.
 
 - Compare sales across different regions.
 
 - Spot the top products driving the highest net sales.
 
 - Track purchasing quantities for each product category.
 
 - Look at how discounts are distributed across regions.
 
 - Review sales performance by individual representatives.
 
 - Track monthly sales patterns.
 
 - See how orders break down by category.
 
 - Build a dashboard to display key retail metrics and findings.


### Tools Used

 - Microsoft Excel
 - Excel Functions
 - Excel Tables
 - XLOOKUP
 - Pivot Tables
 - Data Visualization
 - Dashboard Development


### Data Workflow
 
 - Data Preparation
      - The original retail sales data was separated into different sheets to preserve the raw data and provide supporting information for the analysis, with supporting tables including customer information, product and manufacturer information, and sales representative information.

 - Data Cleaning
      - The raw data was reviewed and standardized to improve consistency across dates, text fields, regions, quantities, prices, sales representatives, and order status.

 - Data Transformation
      - Additional fields were created from the cleaned data, including Month, Total Sales, Discount Amount, Net Sales, Order Category, Product Category, and Manufacturer.

 - Data Analysis
      - Pivot Tables were created to analyze sales performance by region, product, product category, month, discount, order category, and sales representative.

 - Dashboard Development
      - The results of the analysis were presented in a retail sales dashboard containing KPI cards and multiple visualizations.


### Data Cleaning and Transformation

 - Data Cleaning
The raw retail sales data was reviewed and prepared for analysis before creating the final working table.
 
 - Order Date
      - Transformed into a standard Excel date format.

 - Month
      - Extracted from Order Date using the TEXT function.
 
 - Standardization
      - Customer names, product names, sales representative names, and order status values were standardized. Extra spaces were also removed where necessary.
 
 - Region
      - Incorrect region values were identified and corrected.
 
 - Quantity
      - Reviewed with no changes required.
 
 - Unit Price
      - Reviewed with no changes required.
 
 - Duplicate Check
      - The dataset was checked for duplicate records.
 
 - Supporting Data
      - Product Category and Manufacturer were added from the Products table using XLOOKUP.

### Calculated Fields

 - Total Sales
      - Represents the total sales value generated from the quantity of products sold and their unit prices.
 
 - Discount Amount
      - Represents the discount applied to an order based on the defined regional and quantity-based discount rules.
 
 - Net Sales
      - Represents the sales value remaining after the applicable discount has been deducted.
 
 - Order Category
      - Groups orders into High, Medium, and Low categories based on their Net Sales value.


### Key Metrics 
 
 - Total Revenue
      - Represents the overall revenue generated from the orders in the dataset.
 
 - Total Orders
      - Represents the total number of orders recorded in the dataset.
 
 - Average Value
      - Represents the average sales value per order.
 
 - Total Discount
      - Represents the total discount value applied across the orders.

### Exploratory Data Analysis
The analysis focused on answering questions around sales performance, purchasing behaviour, products, regions, sales representatives, discounts, order status, manufacturers, and monthly sales patterns.
 
 - Which region generated the highest net sales? The East region generated the highest net sales.
 
 - Which product generated the highest net sales? Laptop generated the highest net sales.
 
 -  Which product category had the highest quantity purchased? Electronics had the highest quantity purchased.
 
 - What does the order category distribution show? Most orders fell into the Low category, followed by Medium and High. This shows that a larger share of orders came from customers making lower-value purchases.
 
 - What does the order status distribution show? Completed orders represented the largest share of orders, followed by Pending orders, while Cancelled orders were the smallest group.
 
 - Which manufacturers had the highest order activity? IKEA and Logitech recorded the highest order activity among the manufacturers in the dataset.
 
 - Which sales representative generated the highest sales value? Linia Jones recorded the highest sales value among the sales representatives.
 
 - Which months recorded stronger sales performance? January recorded the highest monthly net sales. February, March, April, September, and October also recorded relatively stronger sales performance compared with several other months.
 
 - How were discounts distributed across regions? The East region recorded the highest discount activity.


### Key Insights and Findings
 
 - East was the strongest region by net sales.
 
 - Laptop was the top-performing product.
 
 - Electronics was the leading product category by quantity purchased.
 
 - Most orders were in the Low order category.
 
 - Pending orders represent an area that requires further attention.
 
 - IKEA and Logitech recorded the highest manufacturer order activity.
 
 - Linia Jones recorded the highest sales value among sales representatives.
 
 - January recorded the highest monthly net sales.
 
 - East recorded the highest discount activity.


### Recommendations

 - Investigate pending orders
      - Review the reasons behind pending orders and identify opportunities to improve order processing and completion.

 - Monitor cancelled orders
      - Investigate the causes of cancelled orders and identify ways to reduce preventable cancellations.

 - Prioritize high-performing manufacturers
      - Monitor demand for products from IKEA and Logitech and maintain appropriate stock levels where necessary.

 - Focus on top selling products
      - Monitor demand and availability for laptops to avoid stock shortages and support continued sales.

 - Learn from top sales performance
      - Review Linia Jones’s sales approach and identify strategies that could be applied across the wider sales team.

 - Prioritize the East region
      - Identify the factors contributing to the East region’s strong performance and use those insights to sustain and improve sales.

 - Use targeted customer discounts
      - Consider loyalty based discounts, such as rewarding every fifth returning customer, to encourage repeat purchases while keeping discount costs controlled.

 - Plan around stronger sales periods
      - Use monthly sales patterns to prepare inventory and sales activities ahead of stronger-performing periods.


### Assumptions

 - Order ID was used to represent individual orders when analysing order volume.

 - Order Category was based on the defined Net Sales thresholds.

 - Product Category and Manufacturer information were sourced from the supporting Products table.

### Limitations

 - The analysis is based on the available retail sales records and supporting tables.

 - The dataset does not provide detailed reasons for pending or cancelled orders, limiting the ability to determine their underlying causes.

 - The analysis identifies patterns in the available data but does not establish the reasons behind those patterns.
