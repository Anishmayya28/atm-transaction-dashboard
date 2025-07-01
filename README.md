# 🏧 ATM Transaction Dashboard – Power BI Project

This Power BI project analyzes ATM transaction data to monitor performance, detect failures, and help financial institutions make informed decisions using interactive visualizations and KPIs.

## 📊 Dashboard Highlights

- 💳 **Total & Failed Transactions**
- 📉 **Failure Rate (%) by ATM**
- 🗺️ **Map View**: Transaction Volume by City
- 🕒 **Hourly Breakdown** of Failed Transactions
- 📅 **Filters/Slicers**: Date, City, ATM ID
- 🔍 **Drillthrough View**: ATM Profile (Zone, Install Date, Type)

## 🧾 DAX Measures Used

```DAX
Failure Rate (%) = DIVIDE([Failed Transactions], [Total Transactions], 0) * 100

📁 Project Structure
mathematica
Copy
Edit
atm-transaction-dashboard/
├── atm transactions.pbix           ← Power BI dashboard file
├── datasets/
│   ├── atm_transactions.csv
│   ├── atm_metadata.csv
│   └── dim_date.csv
├── screenshots/
│   ├── dashboard_overview.png
│   ├── drillthrough.png
│   └── map_visual.png
└── README.md
📂 Datasets Used
Dataset	Description
atm_transactions	Transaction ID, Timestamp, Status, Amount, ATM ID
atm_metadata	ATM ID, City, Zone, Install Date, Type
dim_date	Calendar breakdown by Date, Year, Month, Day, Hour

🔒 Note: All data is synthetic and created for demonstration purposes.

🚀 How to Use
Clone this repo or download the .pbix file.
Open it in Power BI Desktop.
Load the CSV files from the datasets/ folder.
Explore the report or publish it to the Power BI Service.

🔁 Features Implemented
📈 Line Chart: Daily transaction trends
📊 Stacked Column: Hourly status breakdown
📋 Table Visual: Transaction detail with formatting
🗺️ Map Visual: City-level volumes
🎛️ Slicers: Date, City, ATM ID

👤 Author
Anish Mayya
LinkedIn Profile

