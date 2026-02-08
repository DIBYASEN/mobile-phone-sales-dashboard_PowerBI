📊 Mobile Phone Sales Dashboard (Power BI)

📌 Project Overview
This project is an interactive Power BI dashboard designed to analyze mobile phone sales data across different cities, brands, payment methods, and time periods. The dashboard provides insights into sales performance, customer preferences, and product trends to support data-driven decision making.

🎯 Objectives
- 📈 Analyze total sales, total quantity sold, and number of transactions
- 📱 Identify top-performing mobile brands and models
- 💳 Understand customer payment method preferences
- 📅 Track daily and monthly sales trends
- 🏙 Compare city-wise sales performance

🛠 Tools & Technologies Used
- 📊 Power BI: Data modeling, DAX measures, and interactive visualizations
- 📁 Microsoft Excel: Data source and preprocessing
- 🧮 DAX: Used for calculated measures and KPIs

📂 Dataset Description
The dataset consists of monthly mobile phone sales data stored in Excel files:
- January_23.xlsx
- February_23.xlsx
- March_23.xlsx
- April_23.xlsx

🧾 Key Columns
- Transaction ID
- Date
- City
- Brand
- Mobile Model
- Units Sold
- Price per Unit
- Total Sales
- Payment Method
- Customer Rating ⭐

📊 Key KPIs
- 💰 Total Sales
- 📦 Total Quantity Sold
- 🔁 Total Transactions
- 📉 Average Sales Value

📈 Dashboard Features
![sales_dashboard](https://github.com/DIBYASEN/mobile-phone-sales-dashboard_PowerBI/blob/9d8464f4835b7dedc8f44f9b565528a1360396e9/Dashboard%20Screenshot/mobile%20sales%20dashboard%20crop.png)

- 📅 Month-wise slicer for time-based analysis
- 🗺 City-wise sales analysis using map visualization
- 📱 Brand and mobile model performance comparison
- 💳 Payment method distribution (UPI, Credit Card, Debit Card, Cash)
- 📈 Daily sales and quantity trend analysis
- ⭐ Customer ratings analysis

🔍 Key Insights
- 🏙 Metro cities contribute the highest share of total sales
- 💳 UPI is the most frequently used payment method
- 📱 Certain premium brands generate higher revenue
- 📆 Sales fluctuate across different days of the week

🧮 DAX Measures Used
Total Sales = SUM(Sales[Total Sales])
Total Quantity = SUM(Sales[Units Sold])
Transactions = DISTINCTCOUNT(Sales[Transaction ID])
Average Sales = AVERAGE(Sales[Total Sales])

## 🚀 Conclusion
This project demonstrates practical data analytics skills including data modeling, DAX calculations, and business-focused dashboard design using Power BI. It is suitable for showcasing entry-level Data Analyst capabilities.

👤 Author
Dibya Sen Jal  
Aspiring Data Analyst  
🔗 LinkedIn: https://www.linkedin.com/in/dibya-s-1715821a7/
