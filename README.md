# 🏠 Housing Market Analysis Dashboard

## 📌 Project Overview
This project analyzes housing market trends using Google BigQuery as the data source and Power BI for visualization.  
It focuses on price trends, regional sales performance, and demand-supply insights.

---

## 🛠️ Tools & Technologies
- Google BigQuery
- Google Cloud Platform (GCP)
- SQL
- Power BI

---

## 🔄 Steps Followed

- **Step 1: Google Cloud Setup**
  - Created Google Cloud account
  - Created a new project in GCP
  - Configured dataset and dataset ID in BigQuery

- **Step 2: Data Processing in BigQuery**
  - Loaded housing dataset into BigQuery
  - Used SQL queries for cleaning and transformation
  - Created structured tables for analysis

- **Step 3: Connecting BigQuery to Power BI**
  - Connected Power BI to Google BigQuery
  - Imported processed data into Power BI

- **Step 4: Data Modeling**
  - Created relationships
  - Built DAX measures
  - Organized data model

- **Step 5: Data Visualization**
  - Created dashboards including:
    - Sales by Region
    - Price Analysis
    - Offer vs Purchase Trends
    - YOY Growth
    - House Type Analysis

- **Step 6: Dashboard Design**
  - Applied clean UI layout
  - Used consistent color themes
  - Improved readability

- **Step 7: Deployment**
  - Published report to Power BI Service
  - Created workspace
  - Set up scheduled refresh

---

## 📊 Snapshot of Dashboard

![Overview](https://raw.githubusercontent.com/komalchoudhary1021-cmyk/Housing-Market-Analysis-Project-3/main/house1.png)

![Sales Performance](https://raw.githubusercontent.com/komalchoudhary1021-cmyk/Housing-Market-Analysis-Project-3/main/house2.png)

![Regional Analysis](https://raw.githubusercontent.com/komalchoudhary1021-cmyk/Housing-Market-Analysis-Project-3/main/house3.png)

![House Type Analysis](https://raw.githubusercontent.com/komalchoudhary1021-cmyk/Housing-Market-Analysis-Project-3/main/house4.png)

---

## 📈 Key Insights

- Strong correlation between offer price and purchase price  
- Zealand and Jutland show highest sales contribution  
- Negative YOY growth in some segments indicates slowdown  
- Demand varies significantly across house types  

---

## 🧾 DAX Calculations

- **Total YTD Sales**
```
  Total YTD Sales = SUM([purchase_price])
```
- **Average Price per SQM**
```
Average Price per SQM = AVERAGE([sqm_price])
```

- **YOY Sales Growth**
```
YOY Sales Growth =
DIVIDE(
[Current Year Sales] - [Previous Year Sales],
[Previous Year Sales]
)
```

---

## 📌 Conclusion
This dashboard helps in:
- Understanding housing price trends  
- Analyzing regional performance  
- Identifying demand patterns  
- Supporting data-driven decisions 
