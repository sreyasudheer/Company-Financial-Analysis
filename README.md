# Corporate Financial Health & Bankruptcy Prediction Analysis

## Executive Summary
This project delivers a deep-dive analytical investigation into corporate financial stability. By utilizing historical financial datasets, this analysis identifies critical indicators of financial distress and maps the trajectory of bankruptcy trends. The project demonstrates an end-to-end data pipeline, moving from raw data extraction and methodical cleaning to the deployment of high-fidelity, interactive dashboards.

## Methodology & Steps Taken
My approach was structured to ensure both statistical accuracy and clear communication of financial insights through the following key steps:

*   **Data Audit & Identification**: Evaluated the raw dataset (`Raw Company Bankruptacy Prediction Data.csv`) to identify inconsistencies, outliers, and missing values.
*   **Data Cleaning & Refinement**: Performed systematic data cleaning to handle null values, normalize financial ratios, and optimize column structures for analysis.
*   **Feature Selection**: Filtered the dataset to retain only the most impactful and relevant financial columns, ensuring a focused and efficient analysis.
*   **Data Transformation**: Engineered and exported the refined dataset as `cleaned_bankruptacy_data.xlsx` to ensure readiness for advanced modeling.
*   **Power BI Enhancement**: Within Power BI, I created custom calculated columns and measures to derive complex financial metrics that were not explicitly present in the source data.
*   **Visual Narrative Construction**: Designed interactive dashboards to translate complex financial relationships into actionable visual insights.

## Key Analytical Results
The analysis of the financial dataset (1999–2009) yielded significant insights into corporate performance:

*   **Bankruptcy Trends**: The analysis identified a total of 220 bankrupt companies, with a notable peak in bankruptcy rates occurring around the year 2002.
*   **Financial Performance Indicators**: 
    *   The dataset shows an average debt ratio of 0.11 and an average asset turnover of 0.14.
    *   Financial leverage metrics indicate an average degree of financial leverage of 187.80.
*   **Strategic Insights**: The dashboards highlight critical profitability and efficiency trends, including Average Operating Gross Margin and Operating Profit Per Share, providing a clear view of corporate stability relative to interest rate fluctuations over the decade.

## Dashboard Capabilities
The dashboards serve as a decision-support tool for visualizing complex financial relationships:
*   **Financial Risk & Trend Overview**: Provides a longitudinal view of bankruptcy rates, allowing users to pinpoint high-risk periods.
*   **Strategic Insights Module**: Offers a high-level summary of critical KPIs including **Average Asset Turnover**, **Degree of Financial Leverage**, and **Current Liquidity**.
*   **Interactive Functionality**: The inclusion of time-based filters allows stakeholders to perform granular analysis by year or aggregated views.

## Tools Used
*   **Python**: Employed for robust data cleaning and preprocessing workflows.
*   **Power BI**: Used for designing high-fidelity, interactive dashboards, including the creation of custom calculated columns/measures for deeper financial metrics.
*   **Excel**: Used for final data validation and storage of the `cleaned_bankruptacy_data.xlsx` dataset.

## Repository Contents
| File Name | Description |
| :--- | :--- |
| `Raw Company Bankruptacy Prediction Data.csv` | Unprocessed source data for historical financial tracking. |
| `cleaned_bankruptacy_data.xlsx` | Refined dataset curated for accuracy and advanced modeling. |
| `Bankrupt dashboard 1.png` | Snapshot of financial risk and bankruptcy rate visualizations. |
| `Bankrupt dashboard 2.png` | Detailed view of financial health metrics and strategic insights. |

---
*Developed by Sreya Sudheer. This project showcases the application of advanced statistical modeling, systematic data cleaning, feature selection, and data visualization to solve complex financial challenges.*
