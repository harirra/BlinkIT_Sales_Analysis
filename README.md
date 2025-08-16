# 🛒 BlinkIT Sales Analysis Dashboard  

## 📌 Project Overview  
This project analyzes grocery sales data from BlinkIT to uncover insights into product performance, customer preferences, and outlet-level sales trends.  
The goal is to provide business intelligence through an interactive Power BI dashboard that helps stakeholders make **data-driven decisions**.  

---

## 🎯 Problem Statement  
BlinkIT wants to optimize its sales strategy by identifying:  
- Which products contribute most to revenue.  
- How **fat content** and **item type** impact sales.  
- Which outlets perform best and why.  
- How outlet size, location, and type influence performance.
- The challenge was to clean, model, and visualize the dataset effectively so decision-makers can quickly identify growth opportunities.

---

## 🗂 Sample Dataset Structure  

| Item Fat Content | Item Identifier | Item Type            | Outlet Establishment Year | Outlet Identifier | Outlet Location Type | Outlet Size | Outlet Type           | Item Visibility | Item Weight | Sales    | Rating |
|------------------|-----------------|----------------------|---------------------------|------------------|----------------------|-------------|-----------------------|----------------|-------------|----------|--------|
| Regular          | FDX32           | Fruits and Vegetables| 2012                      | OUT049           | Tier 1               | Medium      | Supermarket Type1     | 0.1000135      | 15.1        | 145.4786 | 5      |
| Low Fat          | NCB42           | Health and Hygiene   | 2022                      | OUT018           | Tier 3               | Medium      | Supermarket Type2     | 0.008596051    | 11.8        | 115.3492 | 5      |
| Regular          | FDR28           | Frozen Foods         | 2016                      | OUT046           | Tier 1               | Small       | Supermarket Type1     | 0.025896485    | 13.85       | 165.021  | 5      |
| Regular          | FDL50           | Canned               | 2014                      | OUT013           | Tier 3               | High        | Supermarket Type1     | 0.042277867    | 12.15       | 126.5046 | 5      |
| Low Fat          | DRI25           | Soft Drinks          | 2015                      | OUT045           | Tier 2               | Small       | Supermarket Type1     | 0.033970195    | 19.6        | 55.1614  | 5      |
| Low Fat          | FDS52           | Frozen Foods         | 2020                      | OUT017           | Tier 2               | Small       | Supermarket Type1     | 0.005505481    | 8.89        | 102.4016 | 5      |
| Low Fat          | NCU05           | Health and Hygiene   | 2011                      | OUT010           | Tier 3               | Small       | Grocery Store         | 0.098312421    | 11.8        | 81.4618  | 5      |
| Low Fat          | NCD30           | Household            | 2015                      | OUT045           | Tier 2               | Small       | Supermarket Type1     | 0.026903714    | 19.7        | 96.0726  | 5      |
| Low Fat          | FDW20           | Fruits and Vegetables| 2014                      | OUT013           | Tier 3               | High        | Supermarket Type1     | 0.024129332    | 20.75       | 124.173  | 5      |
| Low Fat          | FDX25           | Canned               | 2018                      | OUT027           | Tier 3               | Medium      | Supermarket Type3     | 0.101561568    | —           | 181.9292 | 5      |


---

## 🛠️ Technologies Used  
- **Excel** → Data exploration & cleaning.  
- **Power BI** → Data modeling, DAX measures, and dashboard creation.  

---

## 📊 Dashboard Features  
- **KPIs**: Total Sales, Average Sales, Total Items, Outlet Count.  
- **Sales/Avg Sales/Total Items/Avg Rating Analysis (Matric)**:  
  - Sales by Item Type  
  - Sales by Fat Content  
  - Sales by Outlet Size & Location  
  - Year of Establishment impact  
- **Filters**: Dynamic slicers for Outlet, Item Type, and Year.  

---

## 📈 Insights  
1. **Regular fat content items** generate higher sales than low-fat items.  
2. **Tier 3 locations** contribute the highest sales, showing strong local demand.  
3. **Medium-sized outlets** outperform both small and large outlets in sales volume.  
4. Certain **item types** (Fruits, Dairy, Snacks) drive the majority of revenue.  
5. Newer outlets show competitive performance compared to older ones.  

---

## ✅ Conclusion  
The dashboard helps BlinkIT understand sales drivers across outlets and product categories.  
By focusing on high-performing outlets, optimizing fat-content product distribution, and expanding in Tier 3 cities, BlinkIT can **increase profitability and market share**.  

---


