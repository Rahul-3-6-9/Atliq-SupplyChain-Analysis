# AtliQ Supply Chain Analysis

This repository contains a **Power BI report** analyzing the **supply chain performance of AtliQ**.  
The report highlights delivery efficiency, customer-level insights, and product category analysis to identify gaps in service performance and areas for optimization.

---

## Project Overview
AtliQ, a fast-moving consumer goods (FMCG) supplier, faced challenges in meeting **customer delivery expectations**.  
This project analyzes **On-Time, In-Full, and OTIF (On-Time In-Full) metrics** across different cities, customers, and product categories.  

The goal is to:
- Track **delivery performance vs. commitments**
- Measure **line and volume fill rates**
- Identify **weak areas in operations**
- Provide insights for **logistics and supply chain optimization**

---

## Key Metrics
- **On-Time %**: 71.12%  
- **In-Full %**: 65.96%  
- **On-Time In-Full (OTIF) %**: 47.95%  
- **Total Ordered Quantity**: 13.42M  
- **Total Delivered Quantity**: 12.97M  
- **Line Fill Rate (LiFR)**: ~66%  
- **Volume Flow Rate (VoFR)**: ~96.6%  

---

## Dashboard Highlights
1. **Overall Quantity Analysis**  
   - Comparison of ordered vs delivered quantity across months.  

2. **Customer & City Analysis**  
   - On-Time, In-Full, and OTIF performance by customer.  
   - City-wise breakdown of delivery KPIs.  

3. **Delay Analysis**  
   - Distribution of early, on-time, and late deliveries (1–3 days late).  

4. **Week & Month Analysis**  
   - Trends of Line Fill Rate %, On-Time %, and In-Full % over weeks.  

5. **Product Category Analysis**  
   - Performance of **Beverages, Dairy, and Food** in terms of LiFR and VoFR.  

---

## Tools Used
- **Power BI Desktop** → Data visualization & dashboarding  
- **DAX & Power Query** → Data modeling and calculated measures  
- **Excel/CSV (assumed source)** → Input dataset
- **EDA Tools** → (e.g., Pandas, SQL, Numpy, Matplotlib) → Exploratory Data Analysis

---

## Files
- `Atliq Analysis Report.pdf` → Exported Power BI dashboard report
- `Atliq Analysis.pbix` → Power BI dashboard file
- `DataSet` → Dataset folder with the data and Excel sheets used

---

## How to Use
1. Open `Atliq Analysis Report.pdf`
2. Navigate through sections: Order Overview → City Insights → Delay Analysis → Summary
3. Interpret dashboard charts and tables for performance insights.

---

## Insights
- **On-Time and In-Full performance are significantly below targets**, indicating operational inefficiencies.  
- **Line Fill Rate (~66%)** shows frequent partial order fulfillment.  
- **Volume Flow Rate (~96%)** suggests quantity-level deliveries are mostly consistent, but order completeness is an issue.  
- **Customer-level analysis** highlights key accounts with lower OTIF, requiring focused intervention.  
- **Category-wise trends** reveal similar performance gaps across Beverages, Dairy, and Food.  

--- 


