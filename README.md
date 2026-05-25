# Interactive-E-commerce-Report-Creation-Using-Dax-KPIs-Interactive-Visuals
This project focuses on analyzing an e-commerce dataset using Power BI to generate meaningful business insights. Advanced DAX measures were created to calculate KPIs such as sales, profit, revenue growth, and customer performance. Interactive visualizations and dashboards were designed to improve data storytelling and decision-making.
Got it! Let me read the Power BI file properly.​​​​​​​​​​​​​​​​

📊 SalesMetrics
Sales Performance Dashboard — Power BI Assignment

📋 Table of Contents
	•	About
	•	Dataset Overview
	•	Column Reference
	•	Dashboard Pages
	•	Visuals Breakdown
	•	Key Insights
	•	How to Use
	•	Author

📌 About
SalesMetrics is a multi-page Power BI dashboard built to analyze sales performance, target tracking, and order-level insights across categories, sub-categories, cities, and states.
💡 Built as part of an AI-Driven Data Analytics Program assignment — using real-world sales order data
What this dashboard covers:
	•	✅ Sales vs Target comparison across categories
	•	✅ Profit and quantity analysis by sub-category
	•	✅ Geographic performance mapping by city and state
	•	✅ Order-level drill-down via pivot table
	•	✅ KPI tracking with cards and gauge visuals

📊 Dataset Overview



|🏷️ Property         |📋 Details            |
|-------------------|---------------------|
|**Total Tables**   |`3`                  |
|**Table 1**        |`List of Orders`     |
|**Table 2**        |`Order Details`      |
|**Table 3**        |`Sales Target`       |
|**Dashboard Pages**|`2` — Page 1 & Page 2|
|**Total Visuals**  |`14`                 |

🗂️ Column Reference
List of Orders Table



|#|Column Name          |Description                    |
|-|---------------------|-------------------------------|
|1|`City`               |City where the order was placed|
|2|`State`              |State of the order             |
|3|`Month of Order Date`|Month extracted from order date|
|4|`Orders`             |Total number of orders         |
|5|`Total Order`        |Aggregated order count         |

Order Details Table



|#|Column Name     |Description               |
|-|----------------|--------------------------|
|1|`Category`      |Product category          |
|2|`Sub-Category`  |Product sub-category      |
|3|`Sales`         |Sales amount in INR       |
|4|`Profit`        |Profit generated          |
|5|`Quantity`      |Units sold                |
|6|`Catorgize Sale`|Categorized sales grouping|

Sales Target Table



|#|Column Name      |Description                 |
|-|-----------------|----------------------------|
|1|`Target`         |Sales target value          |
|2|`Total Target`   |Aggregated target           |
|3|`Min Target`     |Minimum target threshold    |
|4|`Profit in Delhi`|Delhi-specific profit metric|
|5|`pm`             |Period/month reference      |

📄 Dashboard Pages



|Page|Name      |Focus                                        |
|----|----------|---------------------------------------------|
|1   |**Page 1**|*Sales vs Target · KPIs · Category Analysis* |
|2   |**Page 2**|*Geographic Map · Treemap · Funnel · Scatter*|

📈 Visuals Breakdown
Page 1



|#|📊 Visual Type             |📋 Fields Used                                                     |Purpose                    |
|-|--------------------------|------------------------------------------------------------------|---------------------------|
|1|**Card**                  |`Sales`                                                           |Total Sales KPI            |
|2|**Card**                  |`Target`                                                          |Total Target KPI           |
|3|**Card**                  |`Profit`                                                          |Total Profit KPI           |
|4|**Card**                  |`Orders`                                                          |Total Orders KPI           |
|5|**Gauge**                 |`Sales` *(Value)* · `Min Target` *(Min)* · `Total Target` *(Max)* |Sales vs Target progress   |
|6|**Clustered Column Chart**|`Category` *(X-axis)* · `Sales` + `Target` *(Y-axis)*             |Sales & Target by Category |
|7|**Donut Chart**           |`Category` *(Legend)* · `Sales` *(Values)*                        |Sales share by Category    |
|8|**Pivot Table**           |`Sub-Category` *(Rows)* · `Sales`, `Profit`, `Quantity` *(Values)*|Order-level drill-down     |
|9|**Slicer**                |`Month of Order Date`                                             |Filter all visuals by month|

Page 2



|# |📊 Visual Type    |📋 Fields Used                                                       |Purpose                         |
|--|-----------------|--------------------------------------------------------------------|--------------------------------|
|10|**Map**          |`City` / `State` *(Location)* · `Sales` *(Bubble Size)*             |Geographic sales distribution   |
|11|**Map**          |`State` *(Location)* · `Profit in Delhi` *(Values)*                 |State-level profit heatmap      |
|12|**Treemap**      |`Sub-Category` *(Category)* · `Sales` *(Values)*                    |Sales proportion by sub-category|
|13|**Funnel Chart** |`Category` *(Group)* · `Total Order` *(Values)*                     |Order volume funnel by category |
|14|**Scatter Chart**|`Sales` *(X-axis)* · `Profit` *(Y-axis)* · `Sub-Category` *(Legend)*|Sales vs Profit correlation     |

💡 Key Insights
	•	💰 Dashboard tracks Sales vs Target at both category and overall level
	•	🗺️ Two map visuals — city-level sales bubbles + state-level profit heatmap
	•	📦 Scatter chart reveals which sub-categories are high-sales but low-profit
	•	🌳 Treemap shows proportional sales contribution across all sub-categories
	•	🔽 Funnel chart visualizes order volume drop-off across categories
	•	🎚️ Month slicer makes all Page 1 visuals fully dynamic




📄 License
Shared for educational and portfolio purposes only.
Not for commercial redistribution.

🙋 Author
Sriram Aditya M — Data Analyst · Power BI Developer



📊 Last updated: May 2026
