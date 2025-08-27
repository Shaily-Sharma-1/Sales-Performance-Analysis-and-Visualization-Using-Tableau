# Regional Sales Dashboard – Tableau

##  Project Overview
This Tableau dashboard was developed as part of my Data Analyst internship, designed to help sales teams and executives monitor regional performance and product trends. It uses the Sample Superstore dataset to simulate real-world business intelligence scenarios.

##  Objectives
- Monitor **key performance metrics** like Sales, Profit, and Orders through KPI cards.
- Analyze **regional variations** and product segment contributions.
- Identify **time-based trends** to detect seasonal peaks and slumps.
- Enable users to **interactively explore** by Region and Product Category.

##  Data Preparation
- Utilized the "Sample - Superstore" dataset (Excel format).
- Derived additional fields:  
  - **Profit Margin** (Profit ÷ Sales)  
  - **Monthly/Y-o-Y Trends** using calculated fields  
  - **Category Ranking** for performance comparisons

- Visual data model:
  ![Data Model Diagram](link-to-your-image-or-diagram)

##  Dashboard Components
- **KPI Cards** – Total Sales, Profit, Orders (with YOY or % change).
- **Regional Sales Bar Chart** – Highlights high and low-performing regions.
- **Product Performance View** – Visual comparison across product categories/subcategories.
- **Time Series Analysis** – Monthly trend line for Sales and Profit.
- **Interactive Filters** – Filters for **Region** and **Category** allowing detailed slicing.

##  Interactive Features
- **Hover tooltips** reveal exact values and variance.
- **Dynamic Titles** update based on selected filters.
- Designed for intuitive navigation and user-friendly insights.

##  Key Insights (Sample-Based)
- The **West** region leads in average **Profit Margin**, outperforming the East by ~25%.
- **Furniture** category consistently underperforms in Sales but shows moderate Profit Margin.
- Monthly trend indicates a spike in **November**, suggesting holiday-related lifts.

##  Design & Visual Rationale
- Clean layout with KPI cards at the top for instant impact.
- Consistent color palette and legible typography.
- Layout optimized for both desktop presentations and full-screen dashboards.

##  Future Enhancements
- Integrate real-time data from databases using **SQL** or ETL pipelines.
- Add more slicing options (e.g., Sub-Category, Year, Customer Segment).
- Improve performance—optimize calculated fields and data aggregations.
- Adapt for mobile dashboards or export-ready presentation formats.

##  How to Explore
1. Clone the repository  
   ```bash
   git clone https://github.com/Shaily-Sharma-1/Sales-Performance-Analysis-and-Visualization-Using-Tableau.git
   cd Sales-Performance-Analysis-and-Visualization-Using-Tableau

