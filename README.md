# Nigeria Sales Data Analysis
**By Aziret Asanov**

## Overview
Analysis of a Nigerian retail sales dataset covering transactions across 20 states, 8 product types, and 4 sales channels between July 2023 and July 2025. The project covers the full data analytics workflow — from raw data cleaning through to statistical analysis and visualisation.

## Questions Answered
- What is the overall revenue and how does it break down by year?
- Which state performs best by units sold and by revenue?
- What is the best-selling product in each state?
- What is the most sold product nationally?
- Is there a relationship between unit price and units sold?
- Which sales channel is the most effective?

## Key Findings
- Total revenue over the period: **₦783,604,676.23**
- Best state by revenue: **Rivers** (₦71,889,881.04) — differs from best state by units sold (**Benue**, 500 units), highlighting that volume and revenue do not always align
- Most sold product nationally: **Keyboard** (1,076 units), dominant in 6 out of 20 states
- Price vs. units sold correlation: **r = -0.0261** — virtually no relationship, suggesting price is not a key driver of purchasing behaviour
- Most effective sales channel: **Online** — leads in both units sold (1,657) and revenue (₦235,803,200)

## Tools & Libraries
- **Python** — pandas, matplotlib, scipy, numpy
- **Google Sheets** — initial exploration using formulas and pivot tables

## Files
| File | Description |
|------|-------------|
| `SalesData.ipynb` | Main analysis notebook — cleaning, analysis, and visualisation |
| `Sales_Data_Report.docx` | Written report summarising findings |
| `Sales_Data_-_nigeria_messy_sales_dataset.csv` | Raw dataset |
| `Sales_Data_-_Proper_Set__1_.csv` | Cleaned dataset reference |
| `Sales_Data_-_Pivot_Table_1.csv` | Pivot table reference |

## Dataset
Source: [Kaggle](https://www.kaggle.com) — Nigerian messy sales dataset
