Overview

This project is a Power BI dashboard built using the BlinkIT Grocery Sales dataset. The data was cleaned and transformed in Power Query, enriched with DAX measures, and visualized in an interactive dashboard. The dashboard provides deep insights into item sales, outlet performance, customer ratings, and category contributions across multiple dimensions.

Significance

Retail companies like BlinkIT require real-time data insights to drive decisions. This project helps in:

Monitoring key KPIs such as total sales, average sales, number of items, and ratings.

Understanding the impact of outlet type, size, and location tier on sales.

Identifying top-performing categories and outlets.

Analyzing customer purchase patterns across different item types.

Supporting business strategy with data-driven recommendations.

Dataset Structure

The dataset contains ~8,500 rows and 12 fields.

1. Item Details

Information about grocery items and their sales.

Item Identifier	Item Type	Fat Content	Item Weight	Item Visibility	Sales	Rating
FDA15	Dairy	Low Fat	9.3	0.016047	3735.14	4
DRC01	Soft Drinks	Regular	5.92	0.019278	443.42	5
2. Outlet Details

Attributes of outlets where items are sold.

Outlet Identifier	Outlet Establishment Year	Outlet Size	Outlet Location Tier	Outlet Type
OUT049	1999	Medium	Tier 1	Supermarket Type1
OUT018	2009	Small	Tier 3	Supermarket Type2
Problem Statements Solved

The dashboard addresses key business questions:

KPIs Tracking – Total Sales, Average Sales, Average Rating, and Number of Items.
<img width="600" alt="KPI Cards" src="https://github.com/user-attachments/assets/12345678-kpi-example" />

Category Contribution – Identifying which item categories (Fruits, Snacks, Dairy, etc.) drive the most sales.
<img width="400" alt="Category Chart" src="https://github.com/user-attachments/assets/23456789-category-example" />

Outlet Performance – Comparing outlet sales by type, size, and location tier.
<img width="400" alt="Outlet Chart" src="https://github.com/user-attachments/assets/34567890-outlet-example" />

Top & Bottom Items – Highlighting best-selling and underperforming items.

Outlet Age Analysis – Examining sales trends based on outlet establishment year.

KPI Table for Unified Analysis
KPI Name	Description	Formula / Symbol
Total Sales	Total revenue generated	💰 SUM(Sales)
Avg Sales	Average sales per item	📊 AVERAGE(Sales)
Avg Rating	Average customer rating	⭐ AVERAGE(Rating)
No of Items	Count of all unique items	🛒 COUNTROWS
Contribution %	Share of sales contribution per category	📈 DIVIDE
Sales per Outlet	Average sales per outlet	🏪 DIVIDE
Conclusion

This Power BI project delivers a comprehensive sales and outlet performance analysis for BlinkIT. By combining Excel preprocessing, Power Query transformations, and DAX-driven KPIs, it enables retail managers to identify high-performing categories, optimize outlet strategies, and improve customer experience.
