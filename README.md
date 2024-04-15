# Power-BI-Projects
## Table of Contents
  - [AdventureWorks Cycles Data Analysis using Power BI](#adventureworks-cycles-data-analysis-using-power-bi)
  - [Ecommerce Sales Analysis using Power BI-Mini project](#ecommerce-sales-analysis-using-power-bi)

# AdventureWorks Cycles Data Analysis using Power BI

## Overview
This project involves analyzing the sales data of AdventureWorks Cycles, a fictitious company selling bicycles and related accessories. Power BI is utilized for data visualization and analysis. The data is transformed and cleaned using Power Query Editor, and various DAX measures are implemented to derive meaningful insights.

## Dataset
The dataset used in this project consists of the following tables:
- `Sales lookup`: Contains information about sales transactions, including sales order number, order date, product key, Order quantity, and Tota quantity etc.
- `Product lookup`: Provides details about products, such as product key, name, category, and subcategory.
- `Customer lookup`: Includes information about customers, including customer ID, first-name, last-name and e-mail details.
- `Calendar lookup`: Contains a calendar table with date-related information, such as date, month, year, and fiscal periods.
- `Returns data`: Includes details about the product returns such as product key, return date, return quantity.
- `Territory lookup`: contains information about region such as territory key, continent and country.

## Objectives
1. Analyze sales performance by product category, subcategory, and region.
2. Track product level trends over time.
3. Identify high value customers.
4. Analyze customer segmentation based on purchasing behavior.
5. Evaluate sales performance against targets and benchmarks.

## Data Transformation and Cleaning
Power Query Editor is used for data transformation and cleaning tasks, including:
- Renaming columns for clarity.
- Removing unnecessary columns.
- Handling missing or duplicate values.
- Creating calculated columns for additional insights.

## DAX Measures
To support analysis and visualization, several DAX (Data Analysis Expressions) measures are implemented, including but not limited to:
- Total Sales: Calculates the total sales amount.
- All oeders: Calculates the total quantity of products sold.
- Average Retail price: Computes the average retail price of products.
- % All Returns: Measures the percentage returns of all product against total returns.
- Total Customer : Estimates the distinct customers.

## Power BI Reports
Power BI reports are created to visualize the insights derived from the data analysis. The reports include interactive visualizations such as:
- Metrix table and line charts to visualize sales trends.
- Pie charts and area charts to analyze sales by product category and subcategory.
- Geographic maps to visualize sales distribution by region.
- KPIs (Key Performance Indicators) to monitor sales performance against targets.

## Visuals
 ![Advworks-1](https://github.com/Gituservaish/Power-BI-Projects/assets/160588103/1d493b1c-6342-434f-8755-833fff26e1a8)

 ![Advworks-2](https://github.com/Gituservaish/Power-BI-Projects/assets/160588103/a7c1cffe-0180-449d-a7d9-fe49ab7cf59c)

 ![Advworks-3](https://github.com/Gituservaish/Power-BI-Projects/assets/160588103/14be4a73-3805-4d5b-bdd7-671a12bf8026)

 ![Advworks-4](https://github.com/Gituservaish/Power-BI-Projects/assets/160588103/9f3ba6dc-ab57-4bff-a242-ecce698c42b7)


## Conclusion
Through this Power BI project, we can gain valuable insights into AdventureWorks Cycles' sales performance, customer behavior, and market trends. The combination of data transformation in Power Query Editor and analysis with DAX measures enables comprehensive data exploration and visualization, empowering stakeholders to make informed business decisions and strategies to drive growth and profitability.


# Ecommerce Sales Analysis using Power BI

## Overview
This mini project focuses on analyzing ecommerce sales data using Power BI. The objective is to gain insights into sales performance, customer behavior, and product trends. Power BI is utilized for data visualization, enabling stakeholders to make informed decisions based on the analysis.

## Dataset
The dataset used in this project contains Two Tables about ecommerce sales , including:
- `Details`: contains information about products such as order ID, amount, profit etc.
- `Orders` : includes information such as Order date, customer name, state and city.

## Objectives
1. Analyze Total sales performance by product category and region.
2. Identify top-selling products.
3. Track Top customers by amount spent.
4. Identify Top payment modes by total amount.
5. Evaluate Profit based on months.

## Power BI Reports
Power BI reports are created to visualize the insights derived from the data analysis. The reports include interactive visualizations such as:
- Bar charts and pie charts to visualize sales trends.
- Column charts to analyze sales by customer name and month.
- KPIs (Key Performance Indicators) to monitor sales performance.

## Visuals
![e-commerce sales data](https://github.com/Gituservaish/Power-BI-Projects/assets/160588103/24482b54-756a-4e9a-b62a-a8102a2382b2)

## Conclusion
Through this Power BI mini project, stakeholders can gain valuable insights into ecommerce sales performance and customer behavior. The interactive visualizations provided by Power BI enable easy exploration of the data, empowering decision-makers to identify opportunities for growth and optimization within the ecommerce business.
