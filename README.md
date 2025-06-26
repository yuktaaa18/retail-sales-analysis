# retail-sales-analysis
Project Overview

This repository contains the Power BI dashboard and supporting files for analyzing daily sales and inventory data. The interactive dashboard provides key performance indicators (KPIs), time-series trends, and forecasting to help stakeholders monitor performance and make data-driven decisions.

Files in this Repository

mock_kaggle.csv — Raw dataset containing daily sales (Units Sold), ending inventory, and unit price for each date.

dashboard_summary.pptx — PowerPoint summary deck with project overview, insights, and next steps.

visual analysis of retail sales.pbix — Power BI report file (dashboard) containing data model, transformations, measures, and visuals.

README.md — This file, providing an overview and instructions.

Dataset Description

The dataset (mock_kaggle.csv) includes:

Date — Transaction date (YYYY-MM-DD)

Units Sold — Number of units sold on that date

Ending Inventory — Inventory remaining at the end of the date

Unit Price — Price per unit (constant)

Sales Amount — Calculated column (Units Sold × Unit Price)

Dashboard Contents

The Power BI dashboard includes:

KPI Cards

Total Sales

Average Daily Units

Days of Inventory

Time-Series Trend

Line chart of Total Sales over time with 30-day forecast

Inventory vs. Units Sold

Combo chart showing Average Daily Units (columns) and Days of Inventory (line) with dual axes

Slicers

Date range selector

Year filter

Interactivity

Drill-through and cross-filtering enabled via DateTable relationships
