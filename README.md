# ECommerce_Dashboard
Brazilian E-Commerce Analysis Dashboard
# 📊 Project Overview
This project provides a data-driven overview of e-commerce operations in Brazil. Using Power BI, I transformed raw transactional data into actionable insights regarding sales trends, delivery efficiency, and product popularity across different Brazilian states.

The dashboard helps stakeholders understand:

Revenue Growth: How sales trend over time (2017–2018).

Logistics Efficiency: The difference between estimated and actual delivery dates.

Customer Geography: High-density sales regions like São Paulo (SP) and Rio de Janeiro (RJ).

Category Performance: Which product types drive the most value.

# 📂 Dataset Information
The analysis is powered by the brazil_ecommerce_master.csv file, which contains over 15 columns of detailed information:


Order Details: order_id, order_status, order_purchase_timestamp, and total_order_value.


Logistics Data: order_delivered_customer_date, order_estimated_delivery_date, and delivery_days_diff.


Product Info: product_id, price, freight_value, and category (e.g., housewares, perfumery, auto).


Customer Location: customer_city and customer_state (e.g., SP, BA, GO, RN).

# 🚀 Key Features of the Dashboard
Executive Summary: High-level KPIs for Total Revenue, Total Orders, and Average Freight Value.

Geographic Map: A visual representation of sales distribution across Brazil.

Delivery Performance: A breakdown of delivery_days_diff to identify logistics bottlenecks in specific states.

Product Analysis: Ranking of categories by total_order_value and volume.

Time Intelligence: Slicers for year, quarter, and month to view seasonal trends.

# 🛠️ Tools Used
Power BI Desktop: For data modeling and visualization.


Power Query: To clean the CSV and calculate fields like delivery_days_diff.

DAX (Data Analysis Expressions): Created custom measures for revenue and order counts.

# 📖 How to Run
Ensure you have Power BI Desktop installed.

Clone this repository to your local machine.

Open the project.pbix file.

If the visuals do not load, go to Transform Data > Data Source Settings and update the file path to point to the brazil_ecommerce_master.csv on your computer.

# 📸 Dashboard Preview
<img width="1081" height="691" alt="image" src="https://github.com/user-attachments/assets/659e12ee-f030-4796-971c-9902ad990511" />



