# India_CPI_Inflation_Case_Study
An Excel-based analysis of India's CPI inflation trends (2017–2023), exploring food inflation, category contributions, COVID-19 impacts, and the relationship between crude oil price fluctuations and inflation.

## Project Overview

This project analyses India's Consumer Price Index (CPI) inflation trends using Microsoft Excel. The study focuses on identifying category-wise contributions to inflation, examining food inflation, understanding the impact of COVID-19, and investigating the relationship between imported crude oil price fluctuations and inflation in India.

The project uses CPI data from the Government of India and explores monthly and yearly inflation patterns across Rural, Urban, and Rural + Urban sectors.

## Objectives

The main objectives of this project are:

- Analyse the contribution of broader expenditure categories to CPI.
- Identify yearly inflation trends and determine the year with the highest inflation rate.
- Investigate month-on-month food inflation and identify major contributing categories.
- Compare inflation trends before and after the onset of COVID-19.
- Examine the relationship between imported crude oil price fluctuations and CPI category movements using correlation analysis.

## Problem Statement

The analysis addresses five key business questions:

1. **CPI Category Contribution:** Identify the broader category contributing the most to CPI using the latest available monthly data.
2. **Year-over-Year Inflation:** Analyse annual CPI inflation trends from 2017 onwards and identify the year with the highest inflation rate.
3. **Food Inflation Analysis:** Examine monthly food inflation trends for the 12-month period ending May 2023 and identify the categories with the largest changes.
4. **Impact of COVID-19:** Compare inflation trends before and after March 2020, focusing on food, healthcare, and essential services.
5. **Crude Oil and Inflation:** Analyse monthly imported crude oil price fluctuations from 2021 to 2023 and investigate their relationship with inflation across CPI categories.

## Tools and Technologies

- **Microsoft Excel**
- Data Cleaning and Preparation
- Missing Value Handling
- PivotTables and PivotCharts
- Data Visualization
- Month-on-Month (MoM) Analysis
- Year-over-Year (YoY) Analysis
- Correlation Analysis using the `CORREL` function
- Economic Trend Analysis

## Key Findings

### 1. CPI Category Contribution

- Food was the largest contributing category across Rural, Urban, and Rural + Urban sectors.
- Food accounted for approximately 50% of the contribution under the category grouping used in the analysis.
- Food and Clothing together represented more than 60% under the same grouping.

### 2. Year-over-Year Inflation Trends

- The analysis identified **2019 as the year with the highest inflation rate**, at approximately **7.74%**, within the 2017–2022 comparison.
- The study examined possible contributing factors, including food and vegetable price increases, supply disruptions, adverse weather conditions, and the onion price crisis.

### 3. Food Inflation Analysis

- June 2022 recorded the highest month-on-month food inflation across the three sectors in the workbook's analysis.
- Spices showed the largest category-level increase over the examined period.
- Oils & Fats and Vegetables recorded notable declines during the period analysed.

### 4. Impact of COVID-19

- The analysis compared CPI inflation trends before and after March 2020.
- Food & Beverages was a leading inflation category before COVID-19.
- The urban analysis also examined a relative shift towards essential services, defined in this project as Transport & Communication and Fuel & Light.

### 5. Crude Oil Price Fluctuations and Inflation

- The study compared monthly crude oil price changes with CPI category movements from 2021 to 2023.
- The largest month-on-month crude oil price increase in the analysed series was approximately **22.10% in March 2022**.
- Oils & Fats and Meat & Fish showed the highest positive correlations with monthly crude oil inflation in the workbook.
- Correlation was used to examine associations between oil price fluctuations and CPI category changes.

*Note: These findings reflect the calculations and assumptions used in the project workbook. Correlation indicates an association and does not establish causation.*

## Methodology

### 1. Data Preparation
- Organised monthly CPI data across Rural, Urban, and Rural + Urban sectors.
- Reviewed missing and unavailable observations.
- Prepared the data for category-wise and time-based analysis.

### 2. Category Grouping
- Grouped individual CPI expenditure categories into broader analytical buckets.
- Examined category contributions based on the approach specified in the case study.

### 3. Inflation Calculations

**Month-on-Month Percentage Change:**

```text
((Current Month CPI - Previous Month CPI) / Previous Month CPI) * 100
```

**Year-over-Year Percentage Change:**

```text
((Current Month CPI - Corresponding Month Previous Year CPI) / Corresponding Month Previous Year CPI) * 100
```

### 4. Trend Analysis
- Compared inflation across different years and sectors.
- Identified months and categories with significant changes.
- Compared inflation patterns before and after March 2020.

### 5. Correlation Analysis
- Compared monthly crude oil price changes with CPI category movements.
- Used Excel's `CORREL` function to calculate correlation coefficients.
- Identified categories with relatively stronger positive correlations.

### 6. Visualization and Interpretation
- Used charts, tables, and comparative analysis to identify trends.
- Interpreted the results in the context of the case-study questions.

## Repository Contents

| File | Description |
|---|---|
| `README.md` | Project overview, objectives, methodology, and findings |
| `CPI Inflation Case_Study.xlsx` | Excel workbook containing the analysis, calculations, and visualizations |

## Data Sources

- **CPI Dataset:** Government of India website.
- **Crude Oil Price Data:** IndexMundi, as referenced in the project workbook.

 ## Skills Demonstrated

- Data Cleaning and Preparation
- Microsoft Excel Data Analysis
- PivotTables and PivotCharts
- Data Visualization
- Inflation and Trend Analysis
- Percentage Change Calculations
- Correlation Analysis
- Business Problem-Solving
- Data Interpretation and Reporting

## Project Objective

The objective of this project is to demonstrate how spreadsheet-based data analytics can be applied to economic data to identify inflation trends, compare expenditure categories, investigate potential economic influences, and communicate meaningful insights.

---

**Author:** Karan Upadhyay  
**Project Type:** Data Analytics | Economic Trend Analysis  
**Primary Tool:** Microsoft Excel
