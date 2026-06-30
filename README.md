# cafe-sales-analysis-2026
# Cafe Sales Analysis & Performance Optimization

## Project Overview
This project involves the end-to-end data analysis of cafe transaction records. The objective was to analyze sales performance, identify seasonal trends, and uncover operational bottlenecks to provide actionable business recommendations.

## Business Objective
To analyze cafe transaction data to identify quarterly revenue trends, peak sales periods, and item performance. The goal was to provide recommendations to optimize inventory procurement, improve staffing schedules, and resolve data integrity issues identified in the Point of Sale (POS) system.

## Data Processing Methodology
To ensure high-quality, reliable insights, the following pipeline was implemented:

*   **Data Extraction & Cleaning**: Imported raw CSV data and corrected structural inconsistencies to ensure a stable dataset.
*   **Data Integrity & Filtering**: Eliminated irreparable rows—specifically those lacking critical date or product information—while utilizing non-destructive filtering for remaining null values to preserve revenue totals.
*   **Data Repair**: Repaired corrupted `Quantity`, `Price`, and `Total Spent` values using logical formulas to maintain mathematical integrity across the dataset.
*   **Data Transformation**: Standardized inconsistent location labels and categorized transactions by Quarter and Month for longitudinal analysis.
*   **Insight Generation**: Utilized Pivot Tables on the master dataset to aggregate performance metrics, allowing for clear identification of trends and operational gaps.

## Key Findings
*   **Best-Seller**: Salads are the highest-selling product across the entire fiscal year.
*   **Peak Period**: June is the peak turnover month, indicating a need for optimized staffing and inventory management heading into Q2.
*   **Operational Risk**: Over 1/3 of transaction data is missing location information, indicating a systemic failure in current POS data entry protocols.

## Strategic Recommendations
*   **Promotional Strategy ("The Balanced Choice")**: Implement a promotional bundle pairing the top-selling item (Salad) with a secondary item (Cookie). This strategy aims to increase the Average Transaction Value (ATV) by utilizing high-traffic volume from Salad sales to improve the inventory turnover of Cookies.
*   **Operational Audit**: Conduct a comprehensive audit of the POS system configuration and staff training protocols to resolve the location data gap and ensure accurate future reporting.

## Tools Used
*   **Excel**: Data cleaning, logical formula application, and Pivot Table generation.
