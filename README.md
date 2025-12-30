# Sales Performance Dashboard (Power BI)

<img width="1037" height="585" alt="dashboard summary" src="https://github.com/user-attachments/assets/719d5d09-776b-4d17-a372-fa245826bb1a" />

This project is a beginner-level Power BI dashboard designed to analyze sales performance using a simulated dataset.  
The goal of the dashboard is to provide a clear and interactive overview of revenue trends, product performance, and sales distribution across different dimensions.


## Overview

The dashboard allows users to:
- Monitor overall sales performance through key KPIs
- Analyze revenue evolution over time
- Identify top-performing products
- Explore sales distribution by product category
- Filter results dynamically by date, region, and salesperson

The report is fully interactive and responds to all slicers and filters.


## Dataset

The dataset is a simulated sales dataset created for learning purposes.

**Fields included:**
- Date
- Product
- Category
- Region
- Salesperson
- Quantity
- Revenue

The dataset covers several months of sales data and includes multiple products, regions, and salespeople to allow meaningful analysis.


## Key Metrics (KPIs)

The dashboard includes the following KPIs:
- **Total Revenue**
- **Total Units Sold**
- **Average Daily Revenue**
- **Top Product (by Revenue)**

All KPIs are calculated using DAX measures and dynamically update based on the selected filters.


## Visualizations

The report contains the following visuals:
- **Line chart**: Revenue over time
- **Bar chart**: Revenue by product
- **Donut/Pie chart**: Revenue distribution by category
- **KPI cards**: High-level performance indicators
- **Slicers**: Date, Region, and Salesperson


## DAX Highlights

The project includes custom DAX measures, such as:
- Total Revenue
- Average Daily Revenue
- Top Product (calculated using virtual tables and ranking logic)

These measures respect the current filter context and demonstrate basic to intermediate DAX concepts.

<img width="1039" height="585" alt="filtered dashboard" src="https://github.com/user-attachments/assets/a662e09c-492b-4191-9e09-8ccc565663f0" />

## Tools Used

- Power BI Desktop
- DAX
- Excel (for dataset creation)


## Notes

This is a learning project using simulated data and does not represent real business information.


## Licence
This project is released under the [MIT License](https://choosealicense.com/licenses/mit/). Feel free to modify and reuse for personal or educational purposes.
