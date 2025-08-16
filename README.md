# BlinkIT_Sales_Analysis  
Power BI project analyzing BlinkIT grocery sales data using Excel, Power Query Editor, DAX, and Power BI.  

## 📌 Project Overview  
This project analyzes grocery sales data from BlinkIT (retail dataset) using **Excel, Power Query, DAX, and Power BI**.  
It answers key business questions such as:  
- Which categories drive the most sales?  
- How do outlet type, size, and location impact performance?  
- What are the top-performing outlets and item types?  

## 🗂️ Dataset  
- **Source:** BlinkIT Grocery Sales Dataset (`BlinkIT Grocery Data.xlsx`)  
- **Size:** ~8,500 rows × 12 columns  
- **Fields include:**  
  - Item Identifier, Item Type, Fat Content, Item Weight, Sales  
  - Outlet Identifier, Outlet Type, Outlet Size, Outlet Location Tier  
  - Outlet Establishment Year, Rating, Item Visibility  

## 🔧 Data Cleaning & Transformation  
- Standardized inconsistent outlet attributes (Size, Type, Location) using mode per outlet.  
- Imputed missing **Item Weight** values with median within each Item Type.  
- Created derived column **Outlet Age = 2025 – Establishment Year**.  
- Built a star schema model:  
  - **Fact Table:** Sales transactions  
  - **Dimension Tables:** Item and Outlet attributes  

## 🧮 DAX Measures  
Some key measures used in the dashboard:  
- `Total Sales = SUM(Fact[Sales])`  
- `Avg Sales = AVERAGE('BlinkIT Grocery Data'[Sales])`  
- `Avg Rating = AVERAGE('BlinkIT Grocery Data'[Rating])`  
- `No of Items = COUNTROWS('BlinkIT Grocery Data')`  
- `Contribution % = DIVIDE([Total Sales], CALCULATE([Total Sales], ALLSELECTED()))`  
- `Sales per Outlet = DIVIDE([Total Sales], DISTINCTCOUNT(Fact[Outlet Identifier]))`  

## 📈 Key Insights  
- **Fruits & Vegetables (~14.8%)** and **Snacks (~14.6%)** together contribute ~30% of sales.  
- **Supermarket Type1 outlets** drive ~65% of total sales.  
- **Tier-3 locations** contribute ~39% of sales, ahead of Tier-1 and Tier-2.  
- **Medium-sized outlets** perform best overall in terms of sales volume.  

## 🛠️ Tech Stack  
- **Excel** → Data profiling and exploration  
- **Power Query** → Data cleaning & transformation  
- **Power BI** → Data modeling, DAX calculations, interactive dashboards  

## 🚀 How to Use  
1. Download the `.pbix` file from this repository.  
2. Open it in **Power BI Desktop**.  
3. Interact with filters, drill-through pages, and KPI cards to explore insights.  

---


