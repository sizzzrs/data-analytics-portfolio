# Fast-Food Operations Analytics

## Overview

This project analyzes 1,000 fast-food transactions to identify peak periods, product demand, revenue drivers, and operational workload.

The analysis was completed in Google Sheets using data cleaning, formulas, pivot tables, KPI calculations, charts, and dashboard design.

## Business Questions

- Which time periods have the highest order volume?
- Which time periods generate the highest revenue?
- Which products are sold most often?
- Which products generate the most revenue?
- Which products are popular but generate relatively low revenue?
- Which periods create the highest workload?
- When should employee breaks be avoided?
- Which products should be prepared before peak hours?

## Tools

- Google Sheets
- Pivot tables
- Spreadsheet formulas
- KPI analysis
- Charts and dashboard

## Data Cleaning

The dataset was checked for missing values, duplicates, inconsistent capitalization, extra spaces, mixed date formats, text-formatted numbers, invalid values, and transaction amount errors.

Key cleaning steps:

- standardized dates to `YYYY-MM-DD`;
- replaced 107 missing payment method values with `NULL`;
- standardized text formatting;
- converted numeric values stored as text;
- verified that `item_price × quantity = transaction_amount`;
- confirmed that no duplicate rows were present.

## Key KPIs

| KPI | Result |
|---|---:|
| Total Revenue | $275,230 |
| Total Orders | 1,000 |
| Total Items Sold | 8,162 |
| Average Order Value | $275.23 |
| Top-Selling Product | Cold Coffee |
| Highest-Revenue Product | Sandwich |
| Peak Revenue Period | Night |
| Highest Workload Period | Night |

## Key Insights

- Night and Afternoon had the highest order volume, with 205 transactions each.
- Night generated the highest revenue at $62,075.
- Cold Coffee was the top-selling product, with 1,361 units sold.
- Sandwich generated the highest product revenue at $65,820.
- Panipuri and Sugarcane Juice had high sales volume but relatively low revenue.
- Night created the highest estimated workload, with 1,759 items sold.
- Cold Coffee had the highest combined demand during Afternoon and Night.

## Recommendations

- Schedule more employees during Night and Afternoon.
- Avoid employee breaks during peak periods.
- Prepare ingredients and organize workstations before peak hours.
- Maintain sufficient stock for Cold Coffee, Sugarcane Juice, Frankie, and Sandwich.
- Consider bundles or small price adjustments for popular lower-revenue products.

## Dashboard

![Dashboard Part 1](https://github.com/sizzzrs/data-analytics-portfolio/blob/main/fast-food-operations-analytics/dashboard/dashboard_1.png)

![Dashboard Part 2](https://github.com/sizzzrs/data-analytics-portfolio/blob/main/fast-food-operations-analytics/dashboard/dashboard_2.png)

![Dashboard Part 3](https://github.com/sizzzrs/data-analytics-portfolio/blob/main/fast-food-operations-analytics/dashboard/dashboard_3.png)

![Dashboard Part 4](https://github.com/sizzzrs/data-analytics-portfolio/blob/main/fast-food-operations-analytics/dashboard/dashboard_4.png)

## Files

- [Excel workbook](workbook/workbook_v1.xlsx)
- [Raw dataset](data/raw/Balaji%20Fast%20Food%20Sales.csv)
- [Cleaned dataset](data/processed/cleaned_data_v1.csv)

## Links

[View the Google Sheets workbook](https://docs.google.com/spreadsheets/d/1lbwTOSLoPViESLjuF8jgXyzfVqb-uP65h6rm6tzUhGM/edit?usp=sharing)

[View the original dataset](https://www.kaggle.com/datasets/rajatsurana979/fast-food-sales-report)

## Limitations

- Exact hourly analysis was not possible because the dataset contains broad time periods instead of timestamps.
- Workload was estimated using total quantity sold.
- The dataset does not include staffing levels, preparation time, ingredient costs, or profit margins.
