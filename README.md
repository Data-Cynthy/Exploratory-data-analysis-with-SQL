# Exploratory-data-analysis-with-SQL
This shows the use of SQL to perform EDA on a dataset for a retail company. It starts off from exploring the entire database to the products offered by the company and eventually answering important business questions.

## Project Overview
This project explores sales performance and product trends for a cycling retail store using SQL. The goal of the analysis was to uncover key insights that support data-driven decision-making around product demand, inventory planning, and revenue growth opportunities. The project focuses on identifying what drives sales, which products perform best, and potential areas for business optimization.

## Objectives
This SQL-based EDA aimed to answer the following:
- Which product categories and items generate the most sales?
- What patterns exist in customer purchasing behavior?
- Which products underperform and may require pricing, promotion, or stock adjustments?
- What opportunities exist to improve revenue, stock movement, and customer experience?

## Dataset Summary
- Industry: Cycling Retail
- Data Type: Customers, orders, and product information (3 tables)
- Contents: Bikes, frames, accessories, cycling gear, and spare parts
- Size: 60,000+ rows across 3 tables covering approximately 4 years
## Tools and Skills Used
- Language: SQL
- Concepts Applied: Joins, aggregations, CTEs

## Key Findings
- Bikes are the top-performing product category, generating a significant share of revenue (28,316,272), indicating concentrated customer demand in this category.
- The United States generated the highest revenue and has the largest customer base, making it the strongest market but also showing high reliance on a single region.
- Europe (United Kingdom, France, Germany) is underperforming relative to market potential for cycling products.
- Australia is a strong emerging market with high revenue and customer count relative to population size.
- Customer purchases are almost evenly distributed by gender (Male: 50.5%, Female: 49.5%), indicating balanced market appeal.

*Add visual: Revenue by product category (bar chart)*  
*Add visual: Revenue and customer count by country (table or bar chart)*
## Business Recommendations
- The lowest-selling products are low-value accessories, but they are frequently needed items. Bundle them with bike purchases (for example: "Maintenance Kit Add-On") to encourage cross-selling and increase order value.
- Develop a tailored go-to-market strategy for Europe and Australia (pricing, localized marketing, and product customization) to improve performance in these markets.
- Prioritize inventory for best-selling products such as the Mountain-200 series to prevent stockouts and maximize sales.
- 871 records in the revenue data and 337 in the customer table are tagged as "n/a" for country. This indicates incomplete data collection, which limits customer segmentation and targeted marketing. Improving data capture at the point of sale would provide stronger customer insights and support personalization.
- Gender distribution is nearly equal, showing that the brand appeals to both males and females. Marketing campaigns can remain gender-neutral without losing effectiveness.

## What This Project Demonstrates
This project highlights my ability to:
- Apply SQL to extract, clean, and analyze data for business insights
- Translate raw data into clear and actionable commercial recommendations
- Approach analytics from a commercial and customer-centric perspective

## Next Steps
Future improvements:
- Implement better handling of null values at the point of data collection, for example by using data validation rules so fields such as gender and country must be selected before a record is saved.
- Add a dashboard layer (Power BI or Excel) to visualize key insights and trends.
- Incorporate customer segmentation to understand shopping patterns across gender, customer lifetime value, customer feedback on products, and return rates, as some best-selling products may also have high return rates.
