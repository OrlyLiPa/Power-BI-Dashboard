# Boutique Store - Power BI Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/b3e991f0-bf3f-4b97-ab83-999199cb5691/0b352420daf864086960?experience=power-bi


## Problem Statement

This dashboard provides an interactive financial and operational overview of a Boutique Store, showcasing key metrics such as revenue, profit, total orders, and returns. It is structured into three comprehensive pages, enabling Bike Store's management to gain detailed insights into financial performance, product-specific metrics, and customer behaviour for data-driven decision-making and strategic planning.

The dashboard is divided into three pages:

- Summary: Overview of total revenue, profit, total orders, and returns over selected time periods
    - KPIs: Monthly results vs. targets for revenue, orders, and returns
    - Map: Geographical representation showing total orders and revenue per city
    - Top 20 Products: ranked list based on sales, highlighting bestsellers and key revenue drivers.
- Product Details: In-depth look at specific categories or products
    - KPIs: Monthly actual vs. target for orders, revenue, and profit
    - Profit Analysis: Display total and adjusted profit based on the current product prices, with the ability to change prices using a slicer
    - Metric selection: Allows tracking of Orders, Revenue, Profit, Returns, and Return % over time based on the selected metric
- Customers:  Analysis of customer purchasing behaviour and identification of top customers
    - Over Time overview: Total orders and revenue per customer
    - Customer Distribution: Total orders, revenue, and average revenue per customer per city
    - Top 100 customers: Ranked list based on the number of orders and revenue






### Final Dashboard
[Boutique Store.pdf](https://github.com/user-attachments/files/16180101/Boutique.Store.pdf)

### Summary
![Summary](https://github.com/OrlyLiPa/Power-BI-Dashboard/assets/173278621/51eb30ec-166b-4c9f-ab91-36da3461bff0)

### Product Details
![Product Details](https://github.com/OrlyLiPa/Power-BI-Dashboard/assets/173278621/d63f3252-0834-42fa-823a-1a270d8cb3cc)

### Customers
![Customers](https://github.com/OrlyLiPa/Power-BI-Dashboard/assets/173278621/24a43e23-0f48-47b0-b3f3-d4b5bb2fc0af)

### Steps followed 
- Step 1 : **Load data into Power BI Desktop**
- Step 2 : **Transform and Profile Data in Power Query Editor:**
    -  Data Profiling: remove errors, delete duplicates, check data quality, distribution and profile
    -  Rename columns, change data types, and split or merge columns
    -  Create new columns based on conditions
    -  Merge and Append data from multiple tables
- Step 3 : **Creating data model:**
    - Use primary and foreign keys to create relationships between fact and dimension tables
    - Add inactive relationships and update relationship cardinality and filter flow
    - Update data formats and categories
    - Create data hierarchies
- Step 4 : **Create calculated fields (DAX):**
    - Creating calculated columns and advanced Measures using (CALCULATE, FILTER, RELATED, SWITCH, ALL/ALLSELECTED, SUMX, DATEADD and many more) 
- Step 5 : **Data Visualization:**
    - Designed the dashboard based on the audience:
        - **Summary page:** Executive view with high-level KPIs
        - **Product and Customer detailed views:** for sales and product professionals. 
    - Utilized different visualizations: cards, maps, charts, tables/matrix, slicers
    - Added different levels of granularity by using drill up and down and drill through
    - Adjust report interactions to customize how filters applied to one visual impact other visuals on the page
    - Create Bookmarks to allow "Remove all filter" capability and report Slicer Panel
    - Added Numeric and Field parameters for Product price adjustment and metric selection

