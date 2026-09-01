# CRM-Power-Bi-analysis
CRM Power Bi analysis

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
