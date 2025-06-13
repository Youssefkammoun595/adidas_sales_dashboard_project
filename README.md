# 📊 Adidas US Sales Dashboard (2020-2021)
Power BI analysis of Adidas sales performance across US regions, product categories, and retail partners

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)](https://www.latex-project.org/)

## 🔍 Project Overview
Analysis of 2.48M units sold ($899.9M total sales) during 2020-2021 to identify:
- Regional performance disparities
- Product category profitability 
- Retailer partnership effectiveness
- Impact of sales methods (Online/In-store/Outlet)

## 📂 Repository Structure
Adidas_Sales_Dashboard/
├── Data/ # Raw sales data
│ ├── adidas_sales_2021.xlsx
│ └── adidas_sales_2022.xlsx
├── Documentation/ # LaTeX report
│ ├── Power_BI_Project_Report.pdf
│ └── Report.tex
├── Images/ # Dashboard screenshots
│ ├── Home_Page.png
│ ├── Products_Page.png
│ └── Sales_Analysis.png
├── PowerBI_Files/ # Interactive dashboard
│ └── Adidas_Dashboard.pbix
└── README.md


## 📊 Key Insights
1. **Regional Performance**  
   West region generated highest sales ($269.94M • 30% of total)
   ![Regional Sales](Images/Sales_Analysis.png)

2. **Product Category Breakdown**  
   Men's Street Footwear topped sales ($208.83M) with Women's Apparel close behind ($179.04M)
   ```mermaid
   pie
       title Sales by Category
       "Men's Street Footwear" : 23.2
       "Women's Apparel" : 19.9
       "Men's Athletic Footwear" : 17.1
       "Women's Street Footwear" : 14.2
       "Men's Apparel" : 13.7
       "Women's Athletic Footwear" : 11.9

  2. ** Retailer Performance** 
West Gear outperformed others ($242.96M) with Foot Locker ($220.09M) as runner-up

🛠️ Dashboard Features
Page	Highlights	Preview
Home	Executive KPIs • Navigation	https://Images/Home_Page.png
Sales Analysis	Regional maps • Monthly trends • Retailer rankings	https://Images/Sales_Analysis.png
Products	Category drill-down • Dynamic filtering • Image integration	https://Images/Products_Page.png

Advanced Functionality:

Dynamic product image loading

Cross-filtering between visuals

Month-over-Month (MoM) DAX calculations

⚙️ Technical Implementation
Data Pipeline:

flowchart LR
    A[Raw Excel Data] --> B[Power Query Cleaning]
    B --> C[DAX Measures]
    C --> D[Data Modeling]
    D --> E[Interactive Visuals]
Responsive mobile design

🚀 Usage Instructions
Open PowerBI_Files/Adidas_Dashboard.pbix

Connect to data sources in /Data

Use filters to explore:

Region-specific performance

Product category comparisons

Retailer contribution analysis
