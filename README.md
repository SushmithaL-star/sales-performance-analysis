#  Sales Performance Analysis (Excel)

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

> **Customer segmentation is percentile-based and independent of sort order, ensuring consistent results under dynamic filtering and reporting.**

This approach reflects **professional-grade modeling practices** commonly used in business intelligence and analytics workflows.

---

## 📊 Visual Preview

### Sales Overview
![Sales Overview](screenshots/sales_overview.PNG)

High-level summary of sales performance and distribution.

---

### Segment Performance
![Segment Performance](screenshots/category_performance.PNG)

Comparison of segments built on percentile logic rather than manual thresholds.

---

### Trend Analysis
![Sales Trends](screenshots/sales_trends.PNG)

Time-based patterns used to assess performance movement and stability.

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
