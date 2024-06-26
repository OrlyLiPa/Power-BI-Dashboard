# Bike Store- Power BI Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMWExODc4NjQtNDc4ZC00Y2NhLWJmNGUtN2I5ZmI4NmY0NGFkIiwidCI6IjI1Y2UwMjYxLWJiZDYtNDljZC1hMWUyLTU0MjYwODg2ZDE1OSJ9

## Problem Statement

This dashboard provides an interactive and intuitive financial and operational overview for a Bike Store, showcasing key metrics such as revenue, profit, total orders, and returns. It is structured into three comprehensive pages, enabling Bike Store's management to gain detailed insights into financial performance, product-specific metrics, and customer behavior for data-driven decision-making and strategic planning.

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
[Bike Store.pdf](https://github.com/user-attachments/files/15904460/Bike.Store.pdf)

### Summary
![Summary](https://github.com/OrlyLiPa/Test/assets/173278621/df6e600b-668e-460c-84bf-2ade83d8525f)

### Product Details
![Product Detail](https://github.com/OrlyLiPa/Test/assets/173278621/fd0a0b50-84af-49da-bfdd-0bc8e6c2eec7)

### Customers
![Customers](https://github.com/OrlyLiPa/Test/assets/173278621/5329b92b-5788-4fe6-ba50-da789af415c5)

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
    - Creating calculated columns and advanced Measures using (CALCULATE, FILTER, RELATED, SWITCH, ALL/ALLSELECTED, UNION and many more) 
- Step 5 : **Data Visualization:**
    - Designed the dashboard based on the audience:
        - **Summary page:** Executive view with high-level KPIs
        - **Product and Customer detailed views:** for sales and product professionals. 
    - Utilized different visualizations: cards, maps, charts, tables/matrix, slicers
    - Added different levels of granularity by using drill up and down and drill through
    - Adjust report interactions to customize how filters applied to one visual impact other visuals on the page
    - Create Bookmarks to allow "Remove all filter" capability and report Slicer Panel
    - Added Numeric and Field parameters for Product price adjustment and metric selection

