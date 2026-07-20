# Insurance Claims Dashboard

## Project Overview

This Power BI dashboard analyzes insurance claim performance across status, category, region, territory, tactic, and time. The goal is to help business users monitor claim volume, compare requested, eligible, and approved amounts, and understand approval trends.

## Business Problem

Insurance teams need a clear way to track how claims are submitted, evaluated, and approved. This dashboard helps answer:

- How many claims were submitted and approved?
- What is the total requested, eligible, and approved amount?
- Which territories have the highest claim count?
- Which tactics contribute the highest approved amount?
- How are claims and approval rates changing over time?
- How does current-year performance compare with the previous year?

## Tools Used

- Power BI Desktop
- Power Query
- DAX
- Data modeling
- Custom visual: Chiclet Slicer

## Dashboard Pages

### 1. Claims Overview

Includes KPI cards, claim trends, requested vs approved amount comparison, claims by status, top territories by claim count, and top tactics by approved amount.

### 2. Category and Detail Analysis

Includes category-level claim analysis, requested vs eligible vs approved comparison, matrix view, table view, and treemap analysis.

### 3. Year-over-Year Performance

Includes current-year vs previous-year claim trends, running total approved amount, approved amount comparison, and approval rate trend.

## Key Features

- Interactive slicers for filtering the report
- KPI cards for high-level performance tracking
- Claims trend analysis
- Requested, eligible, and approved amount comparison
- Claim status breakdown
- Territory and tactic performance analysis
- Year-to-date and previous-year comparison
- Approval rate trend monitoring

## Files

- [Power BI File](./Insurance_Dashboard.pbix)
- [PDF Preview](./Insurance_Dashboard.pdf)

## Dashboard Preview

Screenshots can be added in the `screenshots` folder after exporting them from Power BI Desktop.

Recommended screenshot names:

- `page-1-claims-overview.png`
- `page-2-category-detail-analysis.png`
- `page-3-yoy-performance.png`

## Key Insights

Add exact values from the dashboard before sharing publicly:

- Total claims: `[add value]`
- Total requested amount: `[add value]`
- Total eligible amount: `[add value]`
- Total approved amount: `[add value]`
- Approval rate: `[add value]`
- Highest claim territory: `[add value]`
- Highest approved amount tactic: `[add value]`
- Current-year vs previous-year change: `[add value]`

## Business Recommendations

- Review territories with high claim counts to identify operational or policy-related patterns.
- Compare requested, eligible, and approved amounts to detect categories where claim reductions are frequent.
- Monitor approval rate trends monthly to identify process changes early.
- Review tactics with high approved amounts, especially where year-over-year growth is high.
- Use category-level claim analysis to support forecasting and claim planning.

## Portfolio Summary

This project demonstrates my ability to build an end-to-end Power BI reporting solution using data modeling, DAX measures, Power Query, and interactive dashboard design. The report helps users move from high-level claim performance to detailed analysis using slicers, KPI cards, charts, matrix views, and tables.
