# 🛒 Super Store Sales Analysis Project

## 📊 Project Overview
This project demonstrates a complete **data analysis workflow** using the Super Store Sales dataset. The analysis focuses on uncovering trends and insights that can drive better business decisions, with a special emphasis on **time series analysis** to identify seasonal patterns in sales and profit.

The final deliverable includes an **interactive Power BI dashboard** that visually presents key metrics such as sales performance, profit trends, and regional comparisons.

## 🎯 Objective
To contribute to the success of a business by utilizing data analysis techniques — particularly **time series analysis** — to extract valuable insights that support strategic decision-making.

## 📁 Dataset Overview
**Dataset Name:** [SuperStore Sales Dataset](https://github.com/techcareertech/Data-Analysis-project/blob/main/SuperStore_Sales_Dataset.csv) 
**Rows:** 9,800+  
**Columns:** 21

**Key Columns:**
- `Order Date` – Date when each order was placed  
- `Ship Mode` – Delivery type (Standard Class, Second Class, etc.)  
- `Segment` – Customer segment (Consumer, Corporate, Home Office)  
- `Region` – Geographic region (East, West, Central, South)  
- `Category` and `Sub-Category` – Product groupings  
- `Sales`, `Profit`, and `Quantity` – Performance indicators  
- `Payment Mode` – Mode of customer payment  

**Data Source:** Public SuperStore dataset (used widely for BI and analytics demonstrations).  

## 🧰 Tools & Technologies Used
- **Microsoft Power BI** – Data visualization and dashboard creation  
- **Data Cleaning & Preprocessing** – handling missing values, deleting extra columns , encoding categorical variables, scaling numerical variables.
- **DAX Queries** – Applied DAX queries to create calculated columns, perform complex data transformations, and generate actionable business insights

## 📈 Dashboard Preview
Key Metrics Displayed:
•	Orders: 22K
•	Total Sales: 2M
•	Total Profit: 175K
•	Average Ship Days: 10
<p align="center"> <img src="https://github.com/techcareertech/Data-Analysis-project/blob/main/PowerBI_project_Dashboard.PNG" alt="Power BI Dashboard" width="800"> </p>

## 🔍 Analysis Workflow

1. **Data Cleaning**  
   - Removed duplicates and handled missing values  
   - Formatted date columns for time series operations  

2. **Exploratory Data Analysis (EDA)**  
   - Examined sales and profit trends by month, category, and region  
   - Identified high-performing segments and shipping methods  

3. **Time Series Analysis**  
   - Analyzed monthly sales and profit trends to detect seasonal fluctuations  
   - Visualized year-over-year performance  

4. **Dashboard Development**  
   - Created an interactive Power BI dashboard for executives and analysts  
   - Integrated filters for region, segment, and ship mode  


## 💡 Key Insights Summary
| Insight                     | Observation                                                                                                                     |
| :-------------------------- | :------------------------------------------------------------------------------------------------------------------------------ |
| **1. Sales Performance**    | Sales peaked around **November–December**, indicating strong seasonal demand during holidays.                                   |
| **2. Profitability**        | Despite high sales, profit margins were uneven — **Standard Class** shipping offered higher profit efficiency than First Class. |
| **3. Regional Trends**      | The **West** region generated the highest share of total sales, while the **South** region lagged behind.                       |
| **4. Segment Contribution** | The **Consumer** segment contributed nearly half of total sales volume.                                                         |
| **5. Payment Preferences**  | Online and card payments made up the majority of transactions (≈65%), suggesting a digital shift.                               |
| **6. Product Categories**   | **Office Supplies** led sales, while **Technology** had the highest average profit per unit.                                    |

## 🧭 Conclusions & Recommendations

- Focus marketing and inventory on **holiday months (Nov–Dec)** to maximize profits.  
- Optimize **shipping and logistics** for faster modes with better margins.  
- Increase **promotions in low-performing regions** to balance sales distribution.  
- Encourage **Corporate and Home Office** customer retention programs.  
- Continue leveraging **Power BI** for real-time monitoring and decision support.



