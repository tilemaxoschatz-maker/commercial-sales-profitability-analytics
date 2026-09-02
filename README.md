# Commercial Sales, Profitability & Customer Analytics

An end-to-end commercial analytics project built in Google Sheets and Microsoft Excel. The project transforms 9,994 transactional records into management-ready insights about sales growth, profitability, customers, products, regions, discounts, order value, and shipping performance.

The repository includes the analytical workbook and an executive PowerPoint presentation that translates the findings into practical commercial recommendations.

## Project Overview

| Item               | Description                                                                                |
| ------------------ | ------------------------------------------------------------------------------------------ |
| Business objective | Identify growth drivers, margin leakage, customer opportunities, and commercial risks      |
| Dataset            | Sample Superstore transactional dataset                                                    |
| Analysis period    | 2014–2017                                                                                  |
| Data volume        | 9,994 transaction rows                                                                     |
| Main tools         | Google Sheets, Excel, formulas, feature engineering, pivot tables, charts, and PowerPoint  |
| Primary metrics    | Sales, profit, profit margin, orders, customers, average order value, and loss-making rate |

## Business Questions

The analysis addresses the following management questions:

1. How have sales and profit developed over time?
2. Which categories and sub-categories generate the strongest and weakest profitability?
3. Which regions and customer segments create the most value?
4. How does discount intensity affect profitability?
5. How much revenue is associated with loss-making transactions?
6. Which customers generate high revenue but weak or negative profit?
7. How do order value and shipping mode affect commercial performance?

## Analytical Workflow

The workbook follows a structured analytics process:

1. **Raw data preservation** — retains the original dataset for traceability.
2. **Data cleaning and validation** — standardizes and checks the analytical base.
3. **Feature engineering** — creates business-oriented variables for time, shipping, margins, discounts, losses, unit economics, and order value.
4. **Pivot analysis** — analyzes performance across products, customers, regions, segments, discounts, shipping modes, and time periods.
5. **Business analysis** — connects business questions with KPI evidence, interpretations, and recommended actions.
6. **Dashboard development** — presents the most important results in an executive visual format.
7. **Executive communication** — summarizes findings and recommendations in a professional PowerPoint presentation.

## Workbook Structure

| Worksheet             | Purpose                                                                             |
| --------------------- | ----------------------------------------------------------------------------------- |
| `READ_ME`             | Project objective, workbook guide, key questions, insights, and skills demonstrated |
| `RAW_DATA`            | Original transactional dataset preserved for reference                              |
| `CLEAN_DATA`          | Cleaned and validated analytical dataset                                            |
| `FEATURE_ENGINEERING` | Business-focused variables and analytical flags                                     |
| `PIVOT`               | Multi-dimensional KPI and profitability analysis                                    |
| `BUSINESS_ANALYSIS`   | Business questions, evidence, interpretations, and actions                          |
| `DASHBOARD`           | Executive overview of commercial performance                                        |
| `EXECUTIVE_SUMMARY`   | Management findings, priorities, and strategic recommendations                      |

## Engineered Features

The project extends the source data with analytical variables including:

* Shipping days
* Order year, month, quarter, and day of week
* Weekend indicator
* Profit margin
* Sales and profit per unit
* Loss-making transaction flag
* Discount category and high-discount flag
* Order-value category
* Low-margin flag

These features make it possible to analyze not only sales volume, but also the quality and profitability of revenue.

## Executive Performance Snapshot

| KPI                          |                  Result |
| ---------------------------- | ----------------------: |
| Total sales                  |              **$2.30M** |
| Total profit                 |             **$286.4K** |
| Weighted profit margin       |              **12.47%** |
| Customers                    |                 **793** |
| Orders                       | **Approximately 5,000** |
| Loss-making transaction rate |              **18.72%** |

## Key Insights

### 1. Growth Remained Strong, but Margin Quality Came Under Pressure

2017 recorded the highest annual performance, with approximately **$733.2K in sales** and **$93.4K in profit**. Sales increased by **20.36%**, while profit increased by **14.24%**, showing that profit growth did not keep pace with revenue growth.

### 2. Commercial Performance Is Highly Seasonal

September through December generated **51.61% of total sales**. November produced the highest monthly revenue, while December delivered the highest monthly profit.

Inventory, staffing, and commercial campaigns should therefore be aligned with the Q4 demand peak.

### 3. Technology Is the Strongest Profit Engine

Technology generated **36.40% of sales** and **50.79% of total profit**, with a margin of approximately **17.40%**.

It represents the strongest combination of revenue scale and profitability in the portfolio.

### 4. Furniture Generates Revenue Without Sufficient Profit

Furniture produced **32.30% of sales** but only **6.44% of total profit**, resulting in a margin of approximately **2.49%**.

This indicates significant pricing, discount, cost, or product-mix inefficiency.

### 5. Tables Are the Primary Product Profitability Risk

Tables generated approximately **$207.0K in sales** but produced a loss of approximately **$17.7K**, equivalent to a **-8.56% margin**.

Bookcases and Supplies were also loss-making, while Machines generated substantial revenue at a margin of only **1.79%**.

### 6. Discount Intensity Is the Strongest Profitability Warning Signal

| Discount category  | Weighted profit margin |
| ------------------ | ---------------------: |
| No Discount        |             **29.51%** |
| Low Discount       |             **11.91%** |
| Medium Discount    |            **-19.70%** |
| High Discount      |            **-97.37%** |
| Very High Discount |           **-180.03%** |

Profitability becomes structurally negative beyond the Low Discount category.

Medium, High, and Very High Discount transactions generated a combined loss of approximately **$135.4K**.

### 7. Loss-Making Activity Represents a Material Commercial Problem

Approximately **1,871 transaction lines** were loss-making. These transactions represented:

* **18.72%** of transaction lines
* **$468.7K** in sales
* **20.40%** of total revenue
* Approximately **-$156.1K** in profit

The result demonstrates why revenue growth should always be evaluated together with profitability.

### 8. Regional Profitability Varies Significantly

The West was the strongest region, with approximately:

* **$725.5K in sales**
* **$108.4K in profit**
* **14.94% profit margin**

Central generated a meaningful share of revenue but delivered the weakest regional margin at approximately **7.92%**.

### 9. The Largest Customer Segment Is Not the Most Margin-Efficient

Consumer generated more than half of total sales, but Home Office achieved the strongest segment margin at approximately **14.03%**.

Corporate also outperformed Consumer on margin efficiency.

### 10. Revenue Rank Can Hide Customer Losses

Tamara Chand was the most profitable customer, generating approximately **$9.0K in profit** at a **47.14% margin**.

In contrast, Sean Miller ranked first in sales with approximately **$25.0K**, but generated an overall loss of approximately **$2.0K**.

Customer value should therefore be measured using both sales and profit.

## Strategic Recommendations

1. **Strengthen discount governance**
   Use Low Discount as the standard ceiling and require approval and documented deal economics for deeper discounts.

2. **Recover Furniture profitability**
   Begin with Tables and review pricing, discount exposure, product mix, and cost structure before pursuing additional volume.

3. **Scale proven winners**
   Protect Technology and the West region, and identify commercial practices that can be transferred to weaker areas.

4. **Manage customer quality**
   Rank customers using both revenue and profit, and investigate high-sales accounts that generate weak or negative returns.

5. **Monitor loss-making activity**
   Include loss-making rate, discount mix, category margin, customer profit, and regional margin in recurring management reporting.

6. **Prepare for Q4 demand**
   Align inventory, staffing, and commercial activity with the September-to-December peak while protecting margin discipline.

## Repository Structure

```text
commercial-sales-profitability-analytics/
├── README.md
├── data/
│   └── Commercial-Sales-Profitability-Customer-Analytics.xlsx
├── presentation/
│   └── Commercial-Sales-Profitability-Customer-Analytics-Insights.pptx
├── images/
│   ├── dashboard-preview.png
│   └── presentation-preview.png
└── LICENSE
```

## How to Use the Project

1. Download or clone the repository.
2. Open the workbook in Microsoft Excel or upload it to Google Sheets.
3. Begin with the `READ_ME` worksheet for project context.
4. Review the `DASHBOARD` and `EXECUTIVE_SUMMARY` worksheets for management-level findings.
5. Open the PowerPoint presentation for the executive narrative and recommendations.

## Skills Demonstrated

* Data cleaning and validation
* Feature engineering
* Spreadsheet formulas and calculated metrics
* Pivot-table analysis
* KPI design
* Sales and profitability analysis
* Customer and product segmentation
* Discount and margin analysis
* Dashboard design
* Data storytelling
* Executive business communication

## Data Source

This portfolio project uses the **Sample Superstore** dataset, a commonly used public demonstration dataset for analytics and business-intelligence projects.

## Disclaimer

This project is intended for portfolio and educational purposes. The data represents a sample business dataset and should not be interpreted as the financial performance of a real company.
