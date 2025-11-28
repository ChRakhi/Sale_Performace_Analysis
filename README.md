# 📊 Sales Performance Analysis (Power BI)

## 📘 Overview
A Power BI dashboard analyzing Superstore sales data (2014–2017).  
Includes KPIs, category-wise performance, segment insights, regional analysis, 
monthly trends, and top product performance.

## 🗂 Dataset
- Order Date, Sales, Profit, Quantity, Discount  
- Category, Sub-Category, Segment  
- Region, Ship Mode, Product Name  

## 📌 Features
- KPI Cards (Sales, Profit, Quantity, Discount)  
- Sales by Category & Segment  
- Sales by Ship Mode  
- Monthly Sales Trend  
- Regional Performance  
- Top 10 Products  
- Sales vs Profit Scatter Plot  
- Year Filters (2014–2017)

## 🔢 DAX Measures
```DAX
Total Sales = SUM(Orders[Sales])
Total Profit = SUM(Orders[Profit])
Total Quantity = SUM(Orders[Quantity])
Total Discount = SUM(Orders[Discount])
```

## 🔍 Insights
- Technology category yields highest sales & profit.  
- Corporate segment contributes ~50% of revenue.  
- Standard Class is most used shipping mode.  
- Sales peak in Nov–Dec each year.  
- West region performs best overall.

## 🛠 Tools Used
- Power BI Desktop  
- Power Query  
- DAX  
- Superstore Dataset  

## 🚀 How to Use
1. Clone repo  
2. Open `Sales_Analysis.pbix` in Power BI  
3. Use slicers (Year, Region) to explore insights  

