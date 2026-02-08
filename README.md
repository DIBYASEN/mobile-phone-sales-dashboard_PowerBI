###📊 Mobile Phone Sales Dashboard (Power BI)###
📌 Project Overview

This project is an interactive Power BI dashboard built to analyze mobile phone sales data across different cities, brands, payment methods, and time periods.
The goal is to help stakeholders understand sales performance, customer behavior, and product trends through clear visual insights.

🎯 Objectives

Analyze total sales, quantity sold, and number of transactions

Identify top-performing mobile brands and models

Understand customer payment preferences

Track daily and monthly sales trends

Compare city-wise sales performance

🛠 Tools & Technologies Used

Power BI – Data modeling, DAX, and visualization

Microsoft Excel – Raw data storage and preprocessing

DAX – Measures and calculated KPIs

📂 Dataset Description

The dataset consists of monthly mobile sales data stored in Excel files:

January 2023

February 2023

March 2023

April 2023

Key columns include:

Transaction ID

Date

City

Brand

Mobile Model

Units Sold

Price per Unit

Total Sales

Payment Method

Customer Rating

📈 Key KPIs

Total Sales

Total Quantity Sold

Total Transactions

Average Sales Value

📊 Dashboard Features

📅 Month-wise slicer for time-based analysis

🏙 City-wise sales visualization using map

📱 Brand & mobile model performance comparison

💳 Payment method distribution (UPI, Credit Card, Debit Card, Cash)

📈 Daily sales and quantity trends

⭐ Customer ratings analysis

🔍 Key Insights

Certain metro cities contribute the highest sales volume

UPI is the most preferred payment method

Premium brands generate higher revenue despite lower quantities

Sales show noticeable variation across days of the week

🧮 DAX Measures Used
Total Sales = SUM(Sales[Total Sales])

Total Quantity = SUM(Sales[Units Sold])

Transactions = DISTINCTCOUNT(Sales[Transaction ID])

Average Sales = AVERAGE(Sales[Total Sales])

🖼 Dashboard Screenshot

📁 Repository Structure
mobile-phone-sales-dashboard/
│── Dataset/
│   ├── January_23.xlsx
│   ├── February_23.xlsx
│   ├── March_23.xlsx
│   └── April_23.xlsx
│── Dashboard/
│   └── Mobile_Sales_Dashboard.pbix
│── Images/
│   └── dashboard_screenshot.png
│── README.md

🚀 Conclusion

This dashboard demonstrates practical skills in data cleaning, modeling, DAX calculations, and business-focused visualization using Power BI.
It is designed to support data-driven decision-making for sales and marketing teams.

👤 Author

Dibya Sen Jal
Aspiring Data Analyst
🔗 LinkedIn: (add your LinkedIn link here)
