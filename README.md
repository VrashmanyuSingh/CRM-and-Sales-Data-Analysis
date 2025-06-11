
# CRM AND SALES DATA ANALYSIS

## Problem Statement

The dashboard aims to provide a comprehensive analysis of Superstore sales performance for the year 2017, focusing on key business metrics such as total sales, profit, orders, and return rates. It addresses the need to identify top-performing products, analyze sales trends over time, assess regional performance, and evaluate the effectiveness of promotional campaigns. By visualizing patterns across product categories, customer returns, and monthly trends, the dashboard empowers business stakeholders to make data-driven decisions to optimize inventory, improve profit margins, and enhance the impact of future marketing promotions.

##Snapshot of Dashboard (Power BI)
Page 1: Sales Performance
![Image](https://github.com/user-attachments/assets/225c767d-d87a-4754-bffc-5b5d036cc882)

Page 2: Promotion Analysis
![Image](https://github.com/user-attachments/assets/2b87c4a3-994c-45e2-b0e5-74db2486058c)

Page 3: Product Analysis
![Image](https://github.com/user-attachments/assets/752bd9be-ccc9-459b-9b66-53f84fe405ab)

Page 4:
![Image](https://github.com/user-attachments/assets/f5c793a1-5411-47ec-a27b-1525bffc9b81)

All visuals are interactive and slicers allow filtering across regions, categories, and months.

### Steps followed 

Step 1: Loaded the Superstore.csv dataset into Power BI Desktop for the year 2017.

Step 2: Opened Power Query Editor and verified that data types and column quality were appropriate; no missing values were found in key columns like Sales, Profit, or Orders.

Step 3: Applied basic transformation by filtering for Year = 2017, as all visuals were based on this year.

Step 4: In the report view, a clean visual theme was applied under the View tab to ensure consistency across all pages.

Step 5: Added four card visuals to display KPIs:

  Total Sales = $4.30M

  Total Profit = $504.17K

  Total Orders = 8,857

  Average Order Value = $485.48

Step 6: Added two more card visuals for:

  Number of Returns = 654

  Return Rate (%) = 0.07

Step 7: Inserted a clustered column and line chart to show the monthly trend of Sales and Profit:

  Highest sales in August (~$0.4M), consistent performance till November.

  Profit peaks align with sales peaks in August and October.

Step 8: Created a scatter chart to compare Orders vs Returns by Category:

  Technology had the highest orders (~3900), returns ~300.

  Furniture had fewer orders and proportionally higher returns.

Step 9: Built a Map Chart to show Sales and Profit by Region:

  Highest performing regions: Central Africa and North America.

  Used bubble size for Sales and color intensity for Profit.

Step 10: Added Bar Charts to highlight Top 5 Selling Products:

  #1: Canon imageCLASS – Sales = $35.70K

  Followed by: Apple Smart ($31.29K), Cisco, Motorola, and Hon

Step 11: Added a second Bar Chart for Top 5 Profitable Products:

  #1: Canon imageCLASS – Profit = $15.68K

  Followed by: Cisco ($7.26K), Motorola ($6.31K), Hoover, Sauder

Step 12: Developed a Promotion Analysis Dashboard on a separate page to analyze effectiveness of promotions.

Step 13: Used a Line Chart to plot monthly trends for Sales and Revenue with and without promotions:

  Revenue peaked in November (~$0.5M), dip in July (~$0.2M).

Step 14: Created a Clustered Column Chart to compare Average Sales With vs Without Promotions:

  Clear uplift seen in January, July, and October due to promotions.

Step 15: Added a Bar Chart for Sales and Profit by Promotion Bin:

  No Discount: $2.4M,
  Low Discount: $1.3M,
  Medium Discount: $0.5M,
  High Discount: $0.1M

Step 16: Inserted a Pie Chart for Orders by Promotion Type:

  Black Friday: 191 Orders (38.9%)

  Festive Offer: 142 Orders (28.92%)

  Summer Sale: 72 Orders (14.66%)

Step 17: Final formatting was applied with text boxes for title and subtitle, company branding, and slicers for fields like Region, Category, and Promotion Type.

Step 18: Published the report to Power BI Service for sharing and collaboration with stakeholders.

## Insights:
  [1] Sales & Orders KPIs
  Total Sales = $4.30M

  Total Profit = $504.17K

  Total Orders = 8,857

  Avg. Order Value = $485.48

[2] Product Insights
  Canon imageCLASS is the top product by both Sales ($35.70K) and Profit ($15.68K).

  Technology outperforms in volume, Furniture shows high return rates.

[3] Promotion Insights
  Black Friday generated the highest number of orders (191 orders, 38.9%).

  Promotions notably increase sales, especially during January, July, and October.

  No Discount offers still dominated in raw revenue terms.

[4] Regional Performance
  Central Africa and North America drive highest Sales and Profit.
