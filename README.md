# CRM-Power-Bi-analysis
CRM Power Bi analysis
Project Overview

This project analyzes a B2B CRM sales pipeline to understand what drives revenue and where commercial performance differs across products and customer segments.

The dataset contains information on sales opportunities, deal stages, products, customer accounts, company characteristics, sales teams, and closed deal values. SQL Server was used to clean and validate the data, investigate data quality issues, and perform exploratory analysis. The validated data was then connected to Power BI for interactive business analysis and visualization.

Business Impact

This analysis provides a structured view of the factors associated with sales performance and can support more informed commercial decision-making.

By combining revenue, conversion, product, and customer-level analysis, the dashboard can help stakeholders:

Identify key revenue drivers by distinguishing between revenue generated through higher sales volume and higher average deal values.
Evaluate revenue concentration and understand the business's dependence on its highest-performing products.
Improve customer targeting by identifying differences in deal value and conversion performance across Small, Mid-Market, and Large accounts.
Assess product–customer fit by highlighting products that perform differently across customer segments.
Identify conversion opportunities where valuable customer/product combinations show comparatively lower win rates.
Support sales prioritization by focusing attention on customer segments and products with stronger revenue potential and conversion performance.
Monitor performance trends to detect changes in revenue, deal value, and conversion over time.
Potential Business Value

The analysis can support decisions around customer targeting, product positioning, sales resource allocation, and pipeline prioritization, helping commercial teams focus on opportunities with the strongest potential business value.

The Power BI dashboard is designed to answer the following business questions:

How is the business performing, and what are the key drivers of revenue?
Which products contribute the most to revenue, and is performance driven by sales volume or deal value?
How does customer size influence revenue and average deal value?
Which products perform best across different customer segments?
Where are the biggest conversion opportunities?
How has sales performance changed over time?

Rather than focusing only on overall sales KPIs, the analysis explores the relationship between revenue, product mix, customer size, deal value, and conversion performance to identify patterns that can support commercial decision-making.
## SQL Data Preparation & Analysis

The raw CRM data was imported into SQL Server and validated before being used for analysis in Power BI.

### Key Steps

- Reviewed table structure, data types, and data quality.
- Standardized inconsistent categorical values.
- Identified and corrected 1,480 inconsistent product records (`GTXPro` → `GTX Pro`).
- Validated missing values and checked for duplicate opportunity IDs.
- Validated relationships between pipeline, account, product, and sales team tables.
- Calculated revenue, win rate, average deal value, sales cycle, and opportunity volume.
- Created customer segments based on company revenue.
- Analyzed product performance across customer segments.

### Key Findings

- Won deals generated approximately **$10.01M in revenue** with a **63.15% win rate**.
- The top three products generated approximately **83.5% of total won revenue**.
- Large accounts generated approximately **$6.75M in won revenue**.
- Large and Mid-Market accounts had almost identical average deal values of **~$2.42K**, compared with **~$2.13K for Small accounts**.
- Small accounts achieved the highest win rate at **64.09%**, while Mid-Market accounts had the lowest at **61.22%**.
- Product conversion performance varied across customer segments.
