# Adventure-Works-Analysis
Documentation for Adventure Works Data Analysis Project
## Overview
This repository contains documentation for the Adventure Works data analysis project. It includes data cleaning procedures, analysis insights, recommendations, and ER diagrams.

## Documentation
- Data Cleaning Procedures(Fact_Sales_New)
- Analysis Insights
- Recommendations
- ER Diagram

## PowerBI Visualization
- [image](https://github.com/user-attachments/assets/97192876-df55-4808-a9ca-d8fc9222273c)
- ![image](https://github.com/user-attachments/assets/247b88a4-c866-4d9b-bd41-97c75e5e92b4)

  

# Data Cleaning Procedures

## Data Sources
- `Fact_Sales_New`
- `AdventureWorks_Customers`

## Steps
1. **Fact_Sales_New**: 
   - Created table with primary and foreign keys.
   - Transferred data from `Fact_Sales`.

2. **AdventureWorks_Customers**:
   - Verified schema.
   - Cleaned customer data.
  

# Analysis Insights

## Sales Trends
- Analyzed sales data over time to identify peaks and dips in performance.

## Customer Behavior
- Examined customer demographics and purchasing patterns.
- Identified key customer segments that drive the most sales.

## Product Performance
- Evaluated the performance of various products.
- Highlighted best-selling and underperforming items.

## Territorial Differences
- Compared sales performance across different regions.
- Identified high and low-performing areas.

## Seasonal Impact
- Assessed the influence of seasonal trends on sales for different product categories.

  ## Database Schema and ER Diagram
The AdventureWorks database consists of several related tables, such as Fact_Sales_New and AdventureWorks_Customers, designed to capture sales data and customer information.

![ER Diagram] ![image](https://github.com/user-attachments/assets/55e7a212-d942-403d-ace2-8436554c0efd)

## Key Findings
- Peak Sales Periods: Most sales occur in Q4, with significant dips in Q2.
- Customer Insights: High-income customers tend to buy luxury items, while younger demographics prefer fast-moving products.
- Territorial Trends: Region 9 consistently outperforms others in sales of Product.

## Recommendations
- Target Marketing Campaigns: Focus marketing efforts on high-income customers for luxury products.
- Optimize Inventory: Adjust inventory to reflect higher demand for certain products during peak seasons.

## Tools/Software Used
- SQLite: Database setup and query execution.
- DBVisualizer: Visualization of ER diagrams and database management.
- Power BI: Visualization and dashboard creation.
- GitHub: Documentation and version control.

## How to Run the Project
1. Clone the repository: `git clone https://github.com/your-repo-name.git`
2. Set up the AdventureWorks database in SQLite.
3. Use the provided SQL scripts to create and populate tables.
4. Open Power BI and load the `Fact_Sales_New` and `AdventureWorks_Customers` tables for visualization.

## Conclusion
This analysis provided valuable insights into sales trends, customer behavior, and product performance. The findings offer clear pathways for optimizing sales strategies and enhancing product offerings to improve overall business performance.
