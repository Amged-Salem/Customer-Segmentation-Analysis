
# Customer Segmentation Analysis

## Overview
This project focuses on analyzing and segmenting customer sales data using SQL queries. The goal is to uncover insights from the `sales_data_sample` dataset by exploring key metrics such as product line performance, revenue trends over time, and deal size contributions. Additionally, the project introduces **RFM (Recency, Frequency, Monetary) analysis**, a widely used customer segmentation technique to help identify high-value customers and optimize marketing strategies.

## Dataset
The analysis is based on the `sales_data_sample` dataset, which includes the following dimensions:
- **Status**
- **Year**
- **Product Line**
- **Country**
- **Deal Size**
- **Territory**
- **Month**

## SQL Queries

### 1. Unique Values Exploration
The initial queries check for unique values in the dataset for different dimensions, including:
- Status
- Year
- Product Line (useful for plotting and visualizations)
- Country (useful for plotting and visualizations)
- Deal Size (useful for plotting and visualizations)
- Territory
- Month

### 2. Revenue Analysis
Several queries are used to analyze revenue performance by different dimensions:
- **Product Line**: Grouping sales by product line and summing up the revenue.
- **Year**: Analyzing total revenue grouped by year to understand sales trends over time.
- **Deal Size**: Grouping sales by deal size to segment customer orders and their contributions to total revenue.

### 3. RFM (Recency, Frequency, Monetary) Analysis Overview
RFM analysis is a customer segmentation technique that ranks and scores customers based on their purchasing behavior. This analysis provides insights into customer loyalty and value by evaluating three key metrics:
- **Recency**: How recently a customer made a purchase.
- **Frequency**: How often a customer makes a purchase.
- **Monetary**: How much money a customer spends on purchases.

#### Purpose of RFM Analysis:
RFM helps businesses:
- Identify the most valuable customers who are more likely to respond to promotions.
- Develop targeted marketing strategies by focusing on different customer segments.
- Understand customer behavior and lifecycle, such as which customers are at risk of leaving and which are loyal.

#### How to Implement RFM in SQL:
- **Recency**: Calculate the time since the last purchase for each customer.
- **Frequency**: Count the total number of transactions made by each customer.
- **Monetary**: Sum up the total spending for each customer.

The RFM values can then be assigned scores (e.g., 1 to 5) based on percentile rankings, allowing the business to classify customers into segments such as high-value, medium-value, and low-value customers.

## How to Use
1. **Database**: Make sure the dataset `sales_data_sample` is imported into a database accessible via SQL.
2. **Run the Queries**: Run each section of the SQL script individually to analyze the data by the respective dimensions.
3. **RFM Analysis**: Expand on the existing queries to calculate Recency, Frequency, and Monetary values for each customer.
4. **Visualizations**: The script provides several useful grouping operations that can be visualized using BI tools like Power BI or Tableau for better insight.
   ## Visualizations




## Future Improvements
- Incorporate additional dimensions like **country** and **territory** into the analysis.
- Build further insights using advanced segmentation techniques like RFM analysis.
- Use visualization tools to map trends and create dashboards based on the query outputs.

## Conclusion
This SQL-based analysis helps segment customers by key factors such as product line, deal size, and time (year), aiding businesses in identifying high-performing segments and areas for improvement. **RFM analysis** provides an additional layer of insight into customer behavior, helping businesses identify their most valuable customers and tailor their marketing strategies for maximum impact.
