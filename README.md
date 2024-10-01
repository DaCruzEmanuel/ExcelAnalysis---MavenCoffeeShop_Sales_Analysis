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

<img src="https://imgur.com/Y7C1SGt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

All files for each month are available for download in this repository.


3. **Import and transform the data in Power Query**

   The power query Editor is directly opened from the "Consolidated sales file"
   
   All monthly files are consolidated using Power Query, automating the data preparation for future updates. Key tasks include:
   - Data profiling
   - Cleaning and transformation
  
<img src="https://imgur.com/GvlQbAx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

4. **Load the data into the "Consolidated sales file"**

<img src="https://imgur.com/Dl4dtZi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

5. **Data Exploration & Analysis with Pivot Tables**  
   Pivot tables were used to explore and analyze the data by:
   - Revenue by month
   - Revenue by product category
   - Transactions by day, hour, and product type
   - KPIs (number of transactions, total revenue, average sales)

<img src="https://imgur.com/2a9pAKV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

6. **Data Visualization & Communication**  
   A comprehensive dashboard was created to visually communicate insights and trends, featuring interactive slicers for filtering by store and month.
   You can download the related excel file by clicking on:
[Consolidated sales file](https://github.com/DaCruzEmanuel/ExcelAnalysis_MavenCoffeeShop_Sales_Analysis/blob/main/Consolidated%20sales%20file.xlsx)

Dashboard before updating new month in "Monthly Sales report" Folder (only 3 first months):

<img src="https://imgur.com/6sUJmjC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 Dashboard after updating new months in "Monthly Sales report" Folder, and refreshing the data on the "Consolidated Sales file" (all 6 months):

<img src="https://imgur.com/re6HqUJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

7. **Final Considerations & Recommendations**
    
The dashboard and visualizations provide several actionable insights, allowing stakeholders to make data-driven decisions for optimizing sales strategies and operations.

   ### Insights:
   - **Revenue Growth**: There is a clear upward trend in revenues over the first semester of 2023, with steady growth observed each month.
   - **Top Revenue-Generating Categories**:  
     - The "Coffee" category is the highest contributor, accounting for 39% of total revenue in the first half of 2023.  
     - "Tea" category follows closely, contributing 29% of the total revenue.
   - **Top-Selling Products**:  
     - The "Barista Espresso" leads as the top revenue-generating product.  
     - However, the most popular product in terms of sales volume is the "Brewed Chai Tea," which received the highest number of orders.
   - **Sales Trends**:  
     - Sales transactions exhibit a similar trend to revenue, with a steady rise over the first semester.  
     - Mondays, Thursdays, and Fridays show the highest sales activity, though there are monthly fluctuations.
     - The busiest hours across all locations are between **8:00 AM and 11:00 AM**.
   - **Store Performance**:  
     - All three store locations are performing relatively well.  
     - However, the store in "Lower Manhattan" recorded slightly lower revenue compared to the other two locations.

   ### Recommendations:
   - **Optimize Operating Hours**:  
     Sales transactions drop significantly after **8:00 PM**, with particularly low activity between **8:00 PM and 9:00 PM** across all stores. For the Lower Manhattan store, this trend begins as early as **7:00 PM**.
     - **Recommendation**: Consider closing all stores by **8:00 PM** to reduce operational costs and improve profit margins.
     
   - **Reinvest in Marketing & Promotions**:  
     Use the resources saved from reducing operating hours to:
     - Promote less popular products to increase demand.
     - Implement targeted campaigns to attract more customers during off-peak hours, particularly at the Lower Manhattan location from **7:00 PM to 8:00 PM**.  
