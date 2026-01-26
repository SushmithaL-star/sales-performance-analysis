#  Sales Performance Analysis (Excel)
Excel sales analysis project exploring revenue trends, customer value tiers,
and product performance using automated summaries and dashboards.

## At a Glance
- Headphones generate the highest revenue despite lower sales volume.
- East region contributes the lowest revenue share.
- Q4 2024 revenue declined as December sales were limited to Headphones.
- Top 3 products account for over 60% of total revenue, with 2 being accessories.

## Project Overview
This project analyzes **sales performance data** using Microsoft Excel to uncover trends, evaluate segment performance, and produce business-ready insights.

The analysis emphasizes **model correctness, consistency under filtering, and clear visual interpretation**, mirroring real-world reporting scenarios.

---

## Objective
- Evaluate overall sales performance  
- Compare performance across segments and time periods  
- Build **robust analytical logic** that remains correct under sorting and filtering  
- Present insights clearly using Excel-based visuals  

---

## Data Modeling & Methodology
Special care was taken to ensure the analysis remains **stable and accurate under dynamic reporting conditions**.

- Customer segmentation is **percentile-based**, not rank-order dependent  
- Segment assignment remains consistent even when data is sorted or filtered  
- Prevents category drift caused by visual or report-level changes  

## Modeling Decisions
> **Customer segmentation is percentile-based and independent of sort order, ensuring consistent results under dynamic filtering and reporting.**

This prevents tier distortion when users apply filters or re-sort tables during analysis.

---

## Visual Preview

### Customer Segmentation & Ranking
![Customer Ranking](screenshots/customer_ranking.PNG)

Customers are ranked by total revenue contribution and segmented into value tiers using percentile-based thresholds.  
Segmentation is independent of sort order, ensuring consistent results under dynamic filtering and reporting.

---

### Revenue Trends (2023 vs 2024)
![Revenue Trends](screenshots/revenue_trends.PNG)

Monthly revenue comparison across two years highlights seasonality, category performance shifts, and Q4 decline patterns.

Interactive slicers allow filtering by:
- Product category
- Year
- Date range

---

### Key Business Insights
![Key Insights](screenshots/key_insights.PNG)

---

## Key Questions Answered
- Which segments consistently drive the most revenue?
- How does performance evolve over time?
- Are segment definitions reliable under different views?
- Where should business focus be directed?

---

## Excel Techniques Used
- Percentile-based segmentation logic  
- Conditional formulas for classification  
- Aggregation using `SUM` and `AVERAGE`  
- Structured tables for analysis stability  
- Charts for trend and performance visualization  

---

## Key Insights
- Percentile segmentation produces **more reliable comparisons** than static thresholds  
- Visual trends re
