# Advanced Sales Analysis & Forecasting Dashboard

## Business Task
Create a comprehensive reporting dashboard to analyze historical sales data, evaluate product value and demand variability through ABC-XYZ segmentation, and estimate future results using a machine learning forecasting model.

## Tools Used
- Power BI
- Power Query
- DAX
- Python (Prophet, Pandas)
- Excel & CSV

## Key Features
- **Dimensional Data Modeling:** Built a robust Star Schema connecting multiple yearly sales fact tables with Product, Country, and a custom DAX Date dimension table
- **Dynamic Interactivity:** Implemented Field Parameters allowing users to dynamically switch metrics between Total COGS, Total Revenue, and Gross Profit.
- **ABC-XYZ Analysis:** Developed a complex segmentation matrix combining Pareto (80/20) principles for profit contribution (ABC) and Coefficient of Variation for demand stability (XYZ).
- **Advanced Visualizations:** Utilized Anomaly Detection, dynamic Pareto charts with conditional formatting, and Smart Narrative summaries for automated insights.
- **Python-Driven Forecasting:** Integrated the Prophet library via Python scripts to generate time-series forecasting, trend/seasonality decomposition, and performance metric evaluations (MAPE, RMSE).
- **Seamless Navigation:** Designed a multi-page layout with interactive bookmarking and button navigation for a smooth user experience.

### 1. Sales Analysis (Main Page)
![Sales Analysis Page](sales_analysis.png)

### 2. ABC-XYZ Analysis
![ABC-XYZ Analysis Page](abc_xyz_analysis.png)

### 3. Sales Performance and Forecast
![Sales Forecast Page](sales_forecast.png)

## Result
The report enables stakeholders to optimize inventory management, adjust pricing strategies, prioritize high-value stable products, and make data-driven future projections based on historical patterns[cite: 6]. 
This report simulates an advanced, enterprise-level sales operations and data science task.
