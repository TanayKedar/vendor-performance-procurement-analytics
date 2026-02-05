# Vendor Performance & Procurement Efficiency Analysis

## Overview
This project analyzes vendor performance, procurement spend, and operational efficiency using SQL, Python, and Power BI.

The objective is to identify:
- High-performing vs underperforming vendors
- Cost leakage due to pricing inconsistencies
- Delivery delays impacting operations
- Procurement spend distribution

## Tools Used
- SQL (MySQL)
- Python (Pandas, NumPy, Matplotlib)
- Power BI (DAX, Power Query)
- Excel

## Dataset
Synthetic procurement dataset containing:
- Vendor information
- Purchase orders
- Delivery timelines
- Pricing details
- Quality metrics

## Project Workflow

1. Data Ingestion
   - Loaded raw procurement and vendor datasets into MySQL.

2. Data Cleaning
   - Removed duplicates and handled missing values.
   - Standardized vendor names and product categories.

3. SQL Analysis
   - Created vendor KPIs (cost, delivery performance, quality score).
   - Identified top 25% vendors contributing ~60% of procurement value.
   - Detected pricing inconsistencies causing ~12% cost leakage.

4. Python Analysis
   - Performed exploratory analysis.
   - Analyzed delivery delays and cost variance.
   - Generated summary statistics.

5. Visualization
   - Built Power BI dashboard to track:
     - Vendor performance
     - Procurement spend
     - Delivery timelines
     - Cost leakage

## Key Insights
- Top vendors contribute majority of procurement value.
- Certain vendors show 15–20% higher delivery delays.
- Pricing inconsistencies result in measurable cost leakage.

## Folder Structure
- data/ : raw and processed datasets
- sql/ : SQL scripts for analysis
- notebooks/ : Python EDA notebook
- powerbi/ : Power BI dashboard
- images/ : dashboard screenshots

## Future Improvements
- Automate ETL using Python pipelines
- Add vendor risk scoring model
- Deploy dashboard using Power BI Service

---

Built by Tanay Kedar
