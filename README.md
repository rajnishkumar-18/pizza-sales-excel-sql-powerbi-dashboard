🍕 Pizza Sales Dashboard


📌 Project Overview

An interactive Pizza Sales Dashboard analyzing sales data for 2015.

Provides insights into:

Total Revenue
Order Trends (daily & monthly)
Top & Bottom-Selling Pizzas
Busiest Periods
Sales by Category & Size
👉 Helps in data-driven decision-making by identifying patterns, customer preferences, and performance gaps.

🔄 Workflow
1. Data Preparation
Imported Excel data into SQL database.
Cleaned dataset (duplicates, missing values, formatting).
2. SQL Analysis
KPIs: Revenue, Orders, AOV, Pizzas Sold
Trends: Daily & Monthly orders
Sales % by Category & Size
Top/Bottom 5 pizzas by Revenue, Quantity, Orders
3. Power BI Visualization
Connected SQL → Power BI
Cleaned using Power Query
Built 2 dashboards:
📊 Trends & Sales Performance
📈 Best & Worst Sellers
📷 Sample Dashboards
Trends & Sales Performance
<img width="1142" height="627" alt="image" src="https://github.com/user-attachments/assets/51d23d9b-0a00-4ce7-8bdf-4685a9551a58" />

Trends Dashboard
Best & Worst Sellers
<img width="1140" height="628" alt="image" src="https://github.com/user-attachments/assets/871de2e3-01d9-4bea-83bb-00956b3c5b4c" />

Best Worst Dashboard
🛠️ Tools & Technologies
Excel → Raw data source
SQL → KPIs, trends & queries
Power Query → Data cleaning
Power BI → Visualization
🚀 Key Insights
Peak sales: Friday & Saturday
Classic pizzas lead in sales
Large pizzas = ~46% of revenue
Thai Chicken Pizza = top revenue driver
Brie Carre Pizza = weakest performer
Seasonal spikes in July & January
📂 Project Structure
📁 Pizza-Sales-Dashboard

 ┣ 📂 Data/       # Raw dataset (Excel/CSV)
 
 ┣ 📂 Queries/    # SQL scripts
 
 ┣ 📂 Output/     # SQL results & Power BI exports
 
 ┣ 📂 Images/     # Assets used in creating dashboard
 
 ┣ 📄 README.md   # Documentation
 
⚡ How to Use
1. Clone Repository
git clone https://github.com/rajnishkumar-18/pizza-sales-excel-sql-powerbi-dashboard.git
cd Pizza-Sales-Dashboard
2. Load Data into SQL
Create DB (pizza_sales_db)
Import dataset → pizza_sales
Run queries from SQL QUERIES
3. Open Power BI
Load .pbix file or connect to SQL
Apply transformations in Power Query
Explore dashboards with slicers
🔮 Future Enhancements
Automate SQL → Power BI refresh
Add customer segmentation
Apply predictive analytics for forecasting
Build mobile-friendly dashboards
