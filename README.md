from pathlib import Path
readme = """# Call Center Dashboard Project

## Overview
This project contains a Call Center dataset and an Excel dashboard used to analyze customer interactions and call center performance.

## Files
- **call center data(1).xlsx** – Source data for call center analysis.
- **Call Center Dashboard.12.xlsx** – Interactive dashboard and visualizations.

## Key Metrics
- Total Calls
- Average Call Duration
- Customer Sentiment Analysis
- Calls by State
- Calls by City
- Call Channel Distribution
- Common Call Categories
- CSAT (Customer Satisfaction) Analysis

## Dashboard Features
- KPI Cards
- Line Charts
- Bar Charts
- Sentiment Analysis
- Geographic Analysis (State & City)
- Call Volume Tracking

## Tools Used
- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Dashboard Visualizations

## Purpose
The dashboard helps monitor call center performance, customer satisfaction, and operational trends to support data-driven decision making.
"""
path = "/mnt/data/README.md"
Path(path).write_text(readme, encoding="utf-8")
print(path)
# call-center-data-analysis
