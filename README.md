# Coffee Shop Sales Analysis - Excel Project

## Project Overview
This project analyzes transaction data for Maven Roaster, a fictional coffee shop with three NYC locations. The dataset, sourced from [Maven Analytics](https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&search=coffee%20shop), spans the first half of 2023 and includes transaction timestamps, locations, and product-level details.

To showcase the powerful functionalities of Power Query, the original dataset (which comes as a single file) was split into six monthly reports, stored in a folder titled "Monthly Sales Reports." Power Query automates the process of combining these files into one consolidated dataset, demonstrating how updates can be efficiently handled. Initially, only the first three months were added, and the remaining months will be incorporated later to illustrate how refreshing the data automatically updates the analysis.

The objective is to automate data preparation and create insightful visualizations that drive data-based decisions, all while optimizing efficiency by reducing manual tasks.

## Tools & Techniques
- **Power Query**: Automates data cleaning, transformation, and consolidates multiple files from a folder.
- **Pivot Tables**: Summarizes large datasets quickly and efficiently.
- **Data Visualization**: Uses pivot charts to display trends, patterns, and insights clearly.

## Key Steps
1. **Define Business Questions**  
   - How have sales trended over time?
   - What are the busiest days of the week?
   - Which products generate the most revenue?

2. **Explore & Organize Data**  
   For the purpose of this project, the dataset was divided into six monthly reports. Initially, only three months were added to the folder to demonstrate the flexibility of Power Query, which will allow for the easy consolidation of the remaining months later by simply refreshing the data.

3. **Load Data into Power Query**  
   All monthly files are consolidated using Power Query, automating the data preparation for future updates. Key tasks include:
   - Data profiling
   - Cleaning and transformation

4. **Data Exploration & Analysis with Pivot Tables**  
   Pivot tables were used to explore and analyze the data by:
   - Revenue by month
   - Revenue by product category
   - Transactions by day, hour, and product type
   - KPIs (number of transactions, total revenue, average sales)

5. **Data Visualization & Communication**  
   A comprehensive dashboard was created to visually communicate insights and trends, featuring interactive slicers for filtering by store and month.

6. **Final Considerations & Recommendations**  
   The dashboard and visualizations provide actionable insights for stakeholders, enabling data-driven decisions.
