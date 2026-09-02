# Commercial Sales, Profitability & Customer Analytics

**End-to-end commercial analytics portfolio project built natively in Google Sheets**

This project transforms **9,994 transactional records** from the Sample Superstore dataset into management-ready insights about **sales growth, profitability, customers, products, regions, discounts, order value, and shipping performance**.

> **Best viewing experience:** open the native Google Sheets version below. The `.xlsx` file is included as a downloadable copy, but some chart positions, formatting, merged cells, and Google Sheets-specific features may look different after Excel export.

## Live Project

**[▶ View the full native Google Sheets workbook](https://docs.google.com/spreadsheets/d/1Ns3utzGzkob_6FDs5UfKkbWYPI-DN6F8f-mIIG_66-Y/edit?usp=sharing)**

### Downloads

- **[Download the Excel export](./Commercial%20Sales%2C%20Profitability%20%26%20Customer%20Analytics%20-%20Google%20Sheets.xlsx)**
- **[Download the executive PowerPoint presentation](./Commercial_Sales_Profitability_Customer_Analytics_Insights.pptx)**

---

## Dashboard Preview

<p align="center">
  <img src="dashboard_preview/Screenshot%202026-09-02%20160747.png" alt="Commercial Sales and Profitability Dashboard" width="100%">
</p>

<p align="center">
  <img src="dashboard_preview/Screenshot%202026-09-02%20161300.png" alt="Commercial Analytics Dashboard Detail" width="100%">
</p>

---

## Project Overview

| Item | Description |
|---|---|
| **Business objective** | Identify growth drivers, margin leakage, customer opportunities, and commercial risks |
| **Dataset** | Sample Superstore transactional dataset |
| **Analysis period** | 2014–2017 |
| **Data volume** | 9,994 transaction rows |
| **Primary tool** | Google Sheets |
| **Supporting tools** | Excel export, formulas, feature engineering, pivot tables, charts, PowerPoint |
| **Primary metrics** | Sales, profit, profit margin, orders, customers, average order value, loss-making rate |

---

## Business Objective

The analysis goes beyond basic sales reporting to answer a more important management question:

> **What is driving profitable growth, where is margin being lost, and what actions should management take to improve commercial performance?**

The project evaluates not only revenue volume, but also the **quality of revenue** across products, customers, regions, discount levels, order values, and shipping methods.

---

## Business Questions

1. How have sales and profit developed over time?
2. Which categories and sub-categories generate the strongest and weakest profitability?
3. Which regions and customer segments create the most value?
4. How does discount intensity affect profitability?
5. How much revenue is associated with loss-making transactions?
6. Which customers generate high revenue but weak or negative profit?
7. How do order value and shipping mode affect commercial performance?

---

## Analytical Workflow

```text
RAW DATA
   ↓
CLEAN DATA
   ↓
FEATURE ENGINEERING
   ↓
PIVOT ANALYSIS
   ↓
BUSINESS ANALYSIS
   ↓
DASHBOARD
   ↓
EXECUTIVE SUMMARY
   ↓
EXECUTIVE PRESENTATION
```

The workbook follows a structured end-to-end analytics process:

1. **Raw data preservation** — retains the original source dataset for traceability.
2. **Data cleaning and validation** — standardizes and checks the analytical base.
3. **Feature engineering** — creates business-oriented variables for time, shipping, margins, discounts, losses, unit economics, and order value.
4. **Pivot analysis** — analyzes performance across products, customers, regions, segments, discounts, shipping modes, and time periods.
5. **Business analysis** — connects business questions with KPI evidence, interpretations, and recommended actions.
6. **Dashboard development** — presents the most important findings in an executive visual format.
7. **Executive communication** — summarizes the conclusions and recommendations for management.

---

## Workbook Structure

| Worksheet | Purpose |
|---|---|
| `READ_ME` | Project objective, workbook guide, key questions, insights, and skills demonstrated |
| `RAW_DATA` | Original transactional dataset preserved for reference |
| `CLEAN_DATA` | Cleaned and validated analytical dataset |
| `FEATURE_ENGINEERING` | Business-focused variables and analytical flags |
| `PIVOT` | Multi-dimensional KPI and profitability analysis |
| `BUSINESS_ANALYSIS` | Business questions, evidence, interpretations, and recommended actions |
| `DASHBOARD` | Executive visual overview of commercial performance |
| `EXECUTIVE_SUMMARY` | Management findings, priorities, and strategic recommendations |

---

## Engineered Features

The source data was extended with analytical variables including:

- Shipping days
- Order year, month, quarter, and day of week
- Weekend indicator
- Profit margin
- Sales per unit
- Profit per unit
- Loss-making transaction flag
- Discount category
- High-discount flag
- Order-value category
- Low-margin flag

These variables make it possible to analyze not only sales volume, but also the **profitability and economic quality of revenue**.

---

## Executive Performance Snapshot

| KPI | Result |
|---|---:|
| **Total Sales** | **$2.30M** |
| **Total Profit** | **$286.4K** |
| **Weighted Profit Margin** | **12.47%** |
| **Total Orders** | **5,008** |
| **Total Customers** | **793** |
| **Average Order Value** | **$458.61** |
| **Loss-Making Transaction Rate** | **18.72%** |

---

# Key Business Insights

## 1. Growth remained strong, but margin quality came under pressure

2017 recorded the strongest annual performance, with approximately **$733.2K in sales** and **$93.4K in profit**. Sales increased by **20.36%**, while profit increased by **14.24%**, showing that profit growth did not keep pace with revenue growth.

**Business implication:** growth is healthy, but management should protect margin quality as the business scales.

## 2. Commercial performance is highly seasonal

September through December generated **51.61% of total sales**. November produced the highest monthly revenue, while December delivered the highest monthly profit.

**Business implication:** inventory, staffing, and commercial campaigns should be aligned with the Q4 demand peak.

## 3. Technology is the strongest profit engine

Technology generated **36.40% of sales** and **50.79% of total profit**, with a margin of approximately **17.40%**.

**Business implication:** Technology combines scale with strong profitability and should remain a protected growth area.

## 4. Furniture generates revenue without sufficient profit

Furniture produced **32.30% of sales** but only **6.44% of total profit**, resulting in a margin of approximately **2.49%**.

**Business implication:** high revenue does not automatically translate into economic value; pricing, discounting, and product mix require review.

## 5. Tables are the primary product profitability risk

Tables generated approximately **$207.0K in sales** but produced a loss of approximately **$17.7K**, equivalent to a **-8.56% margin**.

Bookcases and Supplies were also loss-making, while Machines generated substantial revenue at a margin of only **1.79%**.

**Business implication:** Tables should be the first product-level profitability recovery target.

## 6. Discount intensity is the strongest profitability warning signal

| Discount Category | Weighted Profit Margin |
|---|---:|
| No Discount | **29.51%** |
| Low Discount | **11.91%** |
| Medium Discount | **-19.70%** |
| High Discount | **-97.37%** |
| Very High Discount | **-180.03%** |

Profitability becomes structurally negative beyond the Low Discount category.

**Business implication:** deeper discounts should require stronger commercial justification and approval.

## 7. Loss-making activity represents a material commercial problem

Approximately **1,871 transaction lines** were loss-making. These transactions represented:

- **18.72%** of transaction lines
- Approximately **$468.7K** in sales
- **20.40%** of total revenue
- Approximately **-$156.1K** in profit impact

**Business implication:** revenue growth should always be evaluated together with profitability and loss exposure.

## 8. Regional profitability varies significantly

The West was the strongest region, with approximately:

- **$725.5K in sales**
- **$108.4K in profit**
- **14.94% profit margin**

Central delivered the weakest regional margin at approximately **7.92%**.

**Business implication:** management should identify the commercial practices supporting West performance and test whether they can be transferred to weaker regions.

## 9. The largest customer segment is not the most margin-efficient

Consumer generated more than half of total sales, but Home Office achieved the strongest segment margin at approximately **14.03%**.

Corporate also outperformed Consumer on margin efficiency.

**Business implication:** segment strategy should balance revenue scale with margin quality.

## 10. Revenue rank can hide customer losses

Tamara Chand was the most profitable customer, generating approximately **$9.0K in profit** at a **47.14% margin**.

In contrast, Sean Miller ranked first in sales with approximately **$25.0K**, but generated an overall loss of approximately **$2.0K**.

**Business implication:** customer value should be measured using both sales and profit.

---

# Strategic Recommendations

### 1. Strengthen discount governance
Use Low Discount as the standard ceiling and require approval and documented deal economics for deeper discounts.

### 2. Recover Furniture profitability
Begin with Tables and review pricing, discount exposure, product mix, and cost structure before pursuing additional volume.

### 3. Scale proven winners
Protect Technology and the West region, and identify commercial practices that can be transferred to weaker areas.

### 4. Manage customer quality
Rank customers using both revenue and profit, and investigate high-sales accounts that generate weak or negative returns.

### 5. Monitor loss-making activity
Include loss-making rate, discount mix, category margin, customer profit, and regional margin in recurring management reporting.

### 6. Prepare for Q4 demand
Align inventory, staffing, and commercial activity with the September-to-December peak while protecting margin discipline.

---

## Executive Presentation Preview

<p align="center">
  <img src="presentation-preview/Screenshot%202026-09-02%20161645.png" alt="Executive Presentation Preview" width="100%">
</p>

<p align="center">
  <img src="presentation-preview/Screenshot%202026-09-02%20161702.png" alt="Executive Presentation Recommendation Slide" width="100%">
</p>

**[Download the full PowerPoint presentation](./Commercial_Sales_Profitability_Customer_Analytics_Insights.pptx)**

---

## Repository Structure

```text
commercial-sales-profitability-analytics/
├── README.md
├── Commercial Sales, Profitability & Customer Analytics - Google Sheets.xlsx
├── Commercial_Sales_Profitability_Customer_Analytics_Insights.pptx
├── dashboard_preview/
│   ├── Screenshot 2026-09-02 160747.png
│   └── Screenshot 2026-09-02 161300.png
└── presentation-preview/
    ├── Screenshot 2026-09-02 161645.png
    └── Screenshot 2026-09-02 161702.png
```

---

## How to Use the Project

1. **Open the native Google Sheets workbook first** for the intended layout and formatting.
2. Review the dashboard screenshots above for a quick management-level overview.
3. Use the `READ_ME` worksheet for project context.
4. Review `BUSINESS_ANALYSIS` for detailed analytical reasoning.
5. Review `DASHBOARD` and `EXECUTIVE_SUMMARY` for management-level findings.
6. Download the PowerPoint presentation for the final executive narrative and recommendations.
7. Use the `.xlsx` export only when a local Excel copy is required; visual formatting may differ from the native Google Sheets version.

---

## Skills Demonstrated

### Data Preparation
- Data cleaning and validation
- Structured analytical workflow
- Source-data preservation

### Feature Engineering
- Date-based features
- Profitability metrics
- Unit economics
- Business classification flags

### Spreadsheet Analytics
- Google Sheets
- Excel interoperability
- Spreadsheet formulas
- Dynamic references
- Calculated business metrics

### Pivot Analysis
- Multi-dimensional aggregation
- KPI development
- Segmentation analysis
- Profitability analysis

### Data Visualization
- Executive dashboard design
- KPI cards
- Trend analysis
- Comparative profitability charts

### Business Analytics
- Revenue analysis
- Margin analysis
- Discount analysis
- Customer profitability
- Product profitability
- Regional analysis
- Operational performance

### Business Communication
- Translating analytical findings into business insights
- Executive reporting
- Strategic recommendations
- Management-focused storytelling

---

## Tools

- **Google Sheets**
- **Microsoft Excel**
- **Microsoft PowerPoint**
- Spreadsheet formulas
- Pivot Tables
- Feature Engineering
- Data Visualization
- Business Analytics

---

## Data Source

This portfolio project uses the **Sample Superstore** dataset, a commonly used public demonstration dataset for analytics and business-intelligence projects.

---

## Disclaimer

This project is intended for **portfolio and educational purposes**. The data represents a sample business dataset and should not be interpreted as the financial performance of a real company.
