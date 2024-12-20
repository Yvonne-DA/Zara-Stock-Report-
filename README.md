# Zara Stock Report at February 2024

## Description
This repository contains a Power BI dashboard that visualizes the Zara Stock Report for February 2024. The dashboard provides insights into product quantity, revenue, unique terms, sections, and product positions. The dataset used for this analysis was sourced online as a CSV file and cleaned and transformed in Power Query Editor before creating the visualization.

---

## Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Data Cleaning and Transformation](#data-cleaning-and-transformation)
4. [Dashboard Features](#dashboard-features)
5. [Findings](#findings)
6. [Recommendations](#recommendations)

---

## Overview
The **Zara Stock Report** dashboard provides key insights into the stock performance during February 2024. It tracks the following metrics:
- Total Unique Products
- Total Quantity Sold
- Total Revenue
- Unique Terms, Seasons, and Sections
- Product Positions and Distribution

The dashboard also includes the following visualizations:
- Top 10 Quantity by Time
- Revenue by Product Position
- Quantity by Sections
- Revenue by Product
- Quantity by Seasons and Terms

---

## Dataset
The dataset used in this project:
- **File Name:** `zara_stock_report_feb_2024.csv`
- **Source:** Online public dataset.
- **Description:** Contains stock data for Zara during February 2024, including product details, quantity, revenue, and metadata.

---

## Data Cleaning and Transformation
The following steps were performed in the Power Query Editor:
1. **Dropped Columns:** Removed unnecessary columns to streamline the dataset.
2. **Renamed Columns:** Updated column headers to be more descriptive and standardized.
3. **Changed Data Types:** Converted columns to appropriate data types (e.g., Date, Text, Numeric).
4. **Filtered Rows:** Removed irrelevant or null rows.
5. **Replaced Values:** Replaced incorrect or inconsistent values in the dataset.
6. **Date Formatting:** Converted dates to a short date format.
7. **Created Custom Columns:** Added calculated columns for better analysis (e.g., revenue per product).

---

## Dashboard Features
1. **KPI Tiles:**
   - **Total Unique Products**
   - **Total Quantity Sold**
   - **Total Revenue**
   - Unique Terms, Seasons, and Sections.

2. **Visualizations:**
   - **Top 10 Quantity by Time:** Line chart showing trends.
   - **Revenue by Product Position:** Donut chart displaying revenue breakdown.
   - **Quantity by Sections:** Bar chart comparing MAN and WOMAN sections.
   - **Revenue by Product:** Horizontal bar chart of the top-performing products.
   - **Quantity by Seasons and Terms:** Donut and bar charts to segment quantities.
     ![zara dashboard](https://github.com/user-attachments/assets/a9b89c96-3cff-486a-9400-aaa5b7454232)


3. **Slicers:**
   - Product Name filter.
   - Section selection filter for MAN and WOMAN categories.

---

## Findings
  - ﻿MAN had 396,199 Sum of Quantity and WOMAN had 63,374.
  - Aisle accounted for 39.71% of Sum of Revenue.
  - At 651521, VINTAGE EFFECT LEATHER BOMBER JACKET had the highest Sum of Revenue and was 68.91% higher than LEATHER JACKET, which had the lowest Sum of Revenue at 385710.

---

## Recommendations
1. **Stock Management:**
   - Focus on the top-performing products to optimize stock levels.
   - Reduce inventory for low-performing categories.

2. **Revenue by Product Position:**
   - Invest more in high-performing positions (e.g., Front of Store) to maximize revenue.

3. **Seasonal Insights:**
   - Leverage insights from the "Seasons" analysis to predict stock requirements for upcoming seasons.

4. **Gender-Specific Insights:**
   - Prioritize the MAN section for its higher quantities sold compared to WOMAN.

---
