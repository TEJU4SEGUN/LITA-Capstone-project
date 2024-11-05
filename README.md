### LITA CAPSTONE PROJECT
### SALES PERFORMANCE ANALYSIS FOR A RETAIL STORE

## Project Overview
Retail businesses rely heavily on data to understand customer behavior, optimize inventory, and increase sales. This project, 
Sales Performance Analysis for a Retail Store, aims to analyze historical sales data to derive actionable insights that can help drive data-informed business decisions. 
This analysis will examine various aspects of sales performance, including trends over time, high-performing products and categories, and customer purchasing patterns. 
The insights from this project are intended to assist retail management in optimizing marketing strategies, inventory planning, and customer engagement.

### Project goals
- The main goals of this project are:
- Analyze and visualize sales trends to help the business understand seasonal effects and forecast future sales.
- Identify top-performing products and categories to assist with inventory management and targeted promotions.
- Segment customers based on purchasing behavior to enable personalized marketing strategies and improve customer retention.
- Generate actionable business insights that can inform decision-making across marketing, operations, and inventory management.

  ### Table of Contents
  - Project Overview
  - Objectives
  - _Dataset
  - Technology used
  - Project structure
  - Result and Findings
 
    ## Dataset
    **Source**: Proprietary retail sales data
    
    **Description**: The dataset includes transactions records with fields like
    'OrderID,'Customer Id','Product','Region','OrderDate','Quantity','UnitPrice'.
    
    **Note**: The data has been cleaned and anonymized for analysis purpose.

    ## Tools Used

In this project, Excel, SQL, and Power BI were used in combination to provide a comprehensive analysis of sales performance. 
Each tool served a specific purpose, ensuring that data processing, analysis, and visualization were handled efficiently and effectively.

1. *Microsoft Excel*
   - Used for initial data cleaning, exploration, and preliminary analysis.
   - Enabled rapid data inspection with pivot tables, filtering, and basic aggregations.

2. *SQL (Structured Query Language)*
   - Enabled advanced data querying and transformation, allowing efficient analysis of large datasets.
   - Facilitated complex aggregations and customer segmentation to derive deeper insights.

3. *Microsoft Power BI*
   - Used to create interactive dashboards and visualizations for presenting findings.
   - Allowed stakeholders to explore data dynamically by category, time period, and customer segment.
   - Integrated data from multiple sources, providing a unified reporting solution.
  

### Project Structure
This repository is organized to provide a clear view of the analysis process and findings for the "Sales Performance Anaysis for a Retail Sore" project.
Each folder and files servs a specific purpose, from data storage to scripts,notebooks,and reports,ensuring the project is well-documented and easy to navigate.

Below is a summary of the project structure.
### Dataset
The original dataset can be accessed directly in the ['data/'SalesData.xlsx) folder of this repository

### Data Cleaning and Transformation
To prepare the raw sales data for anaylsis, i performed the following steps:
1. **Removed Duplicates**: Ensured data accurracy by eliminating duplicate entries, allowing each sales transactions to be unique.
2. **Created Pivot Tables for Aggegation**:I used pivot tables to organize the data and calculate key metrics, such as

   A. Sum of Total revenue by Product
   
![Total sales by product](image/Total%20sales%20by%20product.JPG)

B. Regional Performance

![image/Region performance](image/Region%20performance.JPG)

C. Top Selling Product

![image/Top Selling Product](image/Top%20Selling%20Product.JPG)

D. Top Selling Product By Region

![Top_Selling_Product_Region](Top_Selling_Product_Region.JPG)



E.Sum of Total Revenue by Month

  ![Sum_of_Total_Revenue_by_Month](Sum_of_Total_Revenue_by_Month.JPG)

3. **Use Excel formulas to calculate metrics such as**:
   - average sales per product
  
     ![image/Average_sales_Per_Product](image/Average_sales_Per_Product.JPG)

     - total revenue by region
    
       ![Total_revenue_by_region](Total_revenue_by_region.JPG)


4  Then i Wrote queries to extract key insights based on the following

- retrieve the total sales for each product category.

  ![Sql _sales](Sql%20_sales.JPG)
  
- find the number of sales transactions in each region.

  ![sql_sales_transaction](sql_sales_transaction.JPG)
  
- find the highest-selling product by total sales value.

  ![sql_Sales_Top](sql_Sales_Top.JPG)
  
- calculate total revenue per product.

- ![sql_Revenue](sql_Revenue.JPG)
  
- calculate monthly sales totals for the current year.

- ![sql_Current year](sql_Current%20year.JPG)
  
- find the top 5 customers by total purchase amount.

  
![sql_top5](sql_top5.JPG)

- calculate the percentage of total sales contributed by each region.

![sql_Percentage](sql_Percentage.JPG)
  
- identify products with no sales in the last quarter.

  
  ![sql_No_Sales](sql_No_Sales.JPG)

  
5. Then i Create a dashboard that visualizes the insights found in Excel and SQL.
   The dashboard include a sales overview, top-performing products, and regional breakdowns.

   ![Sale_Performance_Dashboard](Sale_Performance_Dashboard.JPG)


   ### Key Insights
   **Product Performance**
- Product Shoes has the highest total sales accounting for 29% of total revenue.
- Product Hat showed a steady increase in sales over the last quarter.

  **Regional Analysis**:
  -The South Region generated the most revenue,with a total of $927,820 in sales.
  - Followed by East Region with a huge significant diffrence in sales.
 
  ### Implications
  These findings suggest that the company should focus on boosting the marketing efforts for Product Socks,Jacket and gloves
  and exploring strategies to enhance sales in the North and west Region.

  ### Future Recommendations
  - Conduct a more detailed analysis on customer preferences to tailor product offerings,
  - Implement targeted marketing campaigns in underperforming regions.
  - Regularly update ongoing monitoring of performance trends.

    



