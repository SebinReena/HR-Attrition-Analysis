# HR Attrition Analysis

End-to-end analysis of employee attrition using a **synthetic dataset** of 5,000 employees (generated for practice).

## Tools
MySQL, SQL, Power BI, DAX

## What I did
- Loaded the CSV into MySQL and checked data quality
- Built a star schema (fact table + department, job role and date dimensions)
- Analysed attrition with SQL (CASE bands, window functions, views)
- Built a 4-page Power BI dashboard (Overview, Drivers, Risk, About)

## Key findings (associations, not proven causes)
- Overall attrition: 16.8% (840 of 5,000)
- Overtime: 27.5% vs 11.7% without overtime
- 200+ monthly hours: 31.4%
- 199 active employees show 4+ risk signals

## Files
- SQL scripts and the dashboard PDF in this repository
- Dataset: synthetic, for practice only

Author: Sebin Reena
