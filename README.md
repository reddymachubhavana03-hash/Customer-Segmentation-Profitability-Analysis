# Customer Revenue–Profit Segmentation Analysis (Excel)

## Project Overview
This project focuses on identifying which customer segments truly drive business value by analyzing both revenue and profitability.  
Instead of assuming that high revenue automatically means high profit, the analysis emphasizes **profit margins**, **customer-level profit**, and **clear segmentation logic**.

The entire project is built in **Microsoft Excel**, replicating a real-world data analyst task commonly expected in interviews and business scenarios.

---

## Business Problem
Many organizations prioritize revenue growth without understanding profitability.  
This often leads to:
- Over-discounting high-revenue customers
- Retaining customers who destroy margin
- Poor allocation of sales and marketing resources

**Objective:**  
Segment customers based on **Revenue vs Profitability** and provide actionable business recommendations.

---

## Dataset Description
The dataset contains customer-level transactional data including:
- Revenue
- Cost
- Return Rate
- Customer Profit (calculated)
- Profit Margin (calculated)

All calculations are performed at the **row level** before aggregation.

---

## Key Metrics Calculated
- **Customer Profit** = Revenue − Cost  
- **Profit Margin** = Customer Profit / Revenue  
- **Revenue Threshold** (used for segmentation)
- **Profit Threshold** (used for segmentation)

⚠️ No metrics are calculated inside pivot tables to maintain transparency.

---

## Customer Segmentation Logic
Customers are classified into four segments using revenue and profit thresholds:

| Segment | Business Meaning |
|------|----------------|
| High Revenue – High Profit | Core profit drivers |
| High Revenue – Low Profit | High risk, margin leakage |
| Low Revenue – High Profit | Growth opportunities |
| Low Revenue – Low Profit | Low priority / cost control |

Segmentation is implemented using Excel formulas, not manual tagging.

---

## Analytical Approach
1. Data cleaning and normalization
2. Row-level metric calculations
3. Threshold-based segmentation
4. Pivot table aggregation for validation
5. Dashboard creation for executive insights

This mirrors how analysis is done in real business environments.

---

## Dashboard Design
The dashboard answers one critical question:

**“Which customer segments should the business retain, grow, fix, or exit?”**

### Dashboard Elements
- Total Revenue
- Total Profit
- Average Profit Margin
- Highest Profit Segment
- Bubble Chart:
  - X-axis: Revenue
  - Y-axis: Profit Margin
  - Bubble Size: Customer Profit
  - Color-coded by Customer Segment

The design intentionally avoids over-decoration to keep insights clear.

---

## Key Insights
- High revenue does not always indicate high profitability
- A small segment contributes a disproportionate share of profit
- Margin control matters more than volume growth
- Discounting high-revenue, low-margin customers is dangerous

---

## Business Recommendations
- Retain and protect high-profit customers
- Reduce discounting in low-margin segments
- Invest in growing high-margin, low-revenue customers
- Reevaluate low-profit, low-revenue customers

---

## Tools Used
- Microsoft Excel
  - Advanced formulas
  - Pivot tables
  - Bubble charts
  - Dashboard reporting

---

## How to Use This Project
1. Download the Excel file from the repository
2. Review calculation sheets to understand logic
3. Open the Dashboard sheet for insights
4. Use insights to simulate business decision-making

---

## Project Extensions
- SQL-based implementation of segmentation logic
- Python (Pandas) replication of analysis
- Power BI interactive dashboard version

---

## About the Author
This project was created by **Bhavana Reddy** to demonstrate practical data analysis skills, business thinking, and interview-ready reporting using Excel.
