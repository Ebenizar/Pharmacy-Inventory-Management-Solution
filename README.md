# Pharmacy-Inventory-Management-Solution


### Table Of Content
[Background](#background)

[Problem Statement](#problem-statement)

[Analysis Objectives](#analysis-objectives)

[Data Description](#data-description)

[Tools Used](#tools-used)

[Data Cleaning Process](#data-cleaning)

[Data Analysis](#data-analysis)

[Key Insights](#key-insights)

[Business Recommendation](#business-recommendation)

## Background
Pharmacies generate large volumes of operational data daily, including sales transactions, inventory records, supplier information, customer purchases, and medication expiry dates. Without proper analysis, it becomes difficult to identify sales trends, monitor stock levels, prevent product expiration, and make informed business decisions.

This project demonstrates how Microsoft Excel can be used to transform raw pharmacy data into an interactive management dashboard that supports operational efficiency and data-driven decision-making.

## Problem Statement 
The pharmacy needed a centralized reporting system that could answer key business questions, including:

- Which products generate the highest revenue?
- Which medications are selling slowly?
- Which products are approaching expiry?
- How well is inventory being managed?
- What are the monthly sales trends?
- Which suppliers provide the highest volume of products?
- How can management make faster, data-driven inventory decisions?

## Analysis Objectives
The objective is to build an Excel dashboard that provides real-time visibility into pharmacy operations.

- Analyze pharmacy sales performance.
- Monitor inventory availability and stock movement.
- Identify fast-moving and slow-moving medications.
- Detect products nearing expiration.
- Evaluate monthly revenue trends.
- Assess supplier contributions.
- Develop an interactive dashboard for management reporting.
- Support inventory optimization and reduce product wastage.

## Data Description
The dataset contains pharmacy operational records, including:
- Product Data
- Sales Data
- Supplier Data
- Purchase Data
- Customer data

## Tools Used
- Microsoft Excel
- Power Query
- Pivot Tables
- Pivot Charts
- Slicers
- Conditional Formatting
- XLOOKUP
- INDEX-MATCH
- SUMIFS
- COUNTIFS
- IF Statements
- Data Validation
- Dynamic Named Ranges

## Data Cleaning Process
Before analysis, the dataset underwent a structured data cleaning process:

- Removed duplicate records.
- Corrected inconsistent date formats.
- Standardized medication names.
- Corrected invalid inventory values.
- Handled missing values.
- Verified pricing consistency.
- Standardized supplier names.
- Checked for invalid expiry dates.
Created calculated fields such as:
- Total Sales
- Gross Revenue
- Stock Status
- Days to Expiry
- Re-order flag
- Converted raw data into Excel Tables for dynamic reporting.

## Data Analysis

The analysis focused on answering key business questions through Excel dashboards and Pivot Table analysis.

- Sales Performance Analysis
- Monthly sales trends
- Revenue by medication category
- Top-selling products
- Bottom-performing products
- Daily transaction volume
- Inventory Analysis
- Current stock availability
- Products below reorder level
- Expiry Monitoring
- Products expiring within:30 days, 60 days, 90 days
- Estimated value of expiring inventory
- Supplier Analysis
- Products supplied by each supplier
- Purchase distribution
- Supplier contribution to inventory
- Product Performance
- Revenue contribution by product
- Quantity sold by category

## Key Insights
- A small percentage of medications contributed the majority of total pharmacy revenue, indicating a concentration of sales among high-demand products.
- Several products consistently remained below the reorder threshold, increasing the risk of stockouts.
- Certain medications showed very low sales volumes despite occupying inventory space, suggesting opportunities for inventory optimization.
- Multiple products were approaching their expiry dates, highlighting the need for proactive inventory rotation and promotional strategies.
- Monthly sales exhibited seasonal fluctuations, with peak demand occurring during specific periods.
- A limited number of suppliers accounted for most inventory purchases, presenting potential supplier dependency risks.
- Dashboard filtering revealed variations in product performance across different medication categories.

## Business Recommendation
Based on the analysis, the following recommendations were made:

- Implement automated reorder alerts for products reaching minimum stock levels.
- Prioritize procurement of high-demand medications while reducing purchases of consistently slow-moving items.
- Introduce promotional discounts or bundle offers for products nearing expiry to minimize financial losses.
- Diversify supplier relationships to reduce dependence on a small number of vendors.
- Perform monthly inventory reviews using the dashboard to improve stock planning.
- Continuously monitor product performance to optimize inventory investment.
- Utilize Excel dashboards as a routine management reporting tool to support operational and strategic decision-making.
