📊 Superstore Sales Dashboard

An interactive data analysis and visualization dashboard built using Python, Pandas, NumPy, Streamlit, Matplotlib, and Plotly. This project transforms raw Superstore sales data into actionable business insights through data preprocessing, KPI monitoring, interactive filtering, visual analytics, and data quality alerts.

🚀 Features

📁 Data Preprocessing
Removed duplicate records
Converted date columns to datetime format
Created new engineered features:
Shipping Days
Order Year
Profit Margin %
Renamed columns for cleaner code
Exported cleaned dataset as superstore_clean.csv

📊 Interactive Dashboard
Region filter
Year filter
Date range filter
Dynamic KPI cards:
Total Sales
Total Profit
Average Discount

📈 Visual Analytics
Overview Tab
Interactive sales data table
Year-over-year sales trend (Plotly line chart)
By Category Tab
Top 10 Sub-Categories by Sales (Matplotlib horizontal bar chart)
Sub-Category Sales & Profit summary table
Sales vs Profit scatter plot (Plotly)
By Region Tab
Profit share by region (Plotly donut chart)
Quality Alerts Tab
Profit margin health monitoring
High discount detection using NumPy percentiles
Sales outlier detection using Z-score analysis
Expandable outlier records table

⚡ Performance Features
Streamlit data caching with TTL
Manual refresh button
Download filtered data as CSV
Custom Streamlit theme

🛠️ Technologies Used
Python
Pandas
NumPy
Streamlit
Matplotlib
Plotly

📂 Project Structure
superstore_app/
│
├── data/
│   ├── samplesuperstore.csv
│   └── superstore_clean.csv
│
├── .streamlit/
│   └── config.toml
│
├── dashboard.py
├── requirements.txt
├── README.md
└── screenshots/

📸 Dashboard Preview


<img width="720" height="480" alt="dashboard_preview" src="https://github.com/user-attachments/assets/bc7ef772-5568-4fa2-b09c-a010fa1a36a6" />










📊 Dataset

Dataset: Sample Superstore Dataset

The dataset contains:

Orders
Customers
Products
Sales
Profit
Discounts
Shipping Information

Used for business intelligence and sales performance analysis.

🔍 Key Insights Generated
Sales performance by category and region
Profitability analysis
High-discount order detection
Shipping efficiency tracking
Loss-making order identification
Regional profit contribution
☁️ Streamlit Cloud Deployment

Live Dashboard:

https://superstoredashboard-sanoobiya.streamlit.app/


👨‍💻 Author

Sanoobiya P

Data Analytics & Visualization Project

DBI Skill Park – Superstore Data Analysis Capstone Project

⭐ Future Enhancements
Forecasting using Machine Learning
Customer Segmentation
Sales Prediction Models
Advanced KPI Alerts
Export Charts as PDF
Dark Mode Support
