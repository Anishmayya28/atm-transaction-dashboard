# atm-transaction-dashboard
# 🏧 ATM Performance Dashboard - Power BI Project

This Power BI project analyzes ATM transaction data to monitor performance, detect failures, and help financial institutions make informed decisions.

## 📊 Dashboard Highlights

- 💳 Total & Failed Transactions
- 📉 Failure Rate by ATM
- 🗺️ Map of Transaction Volume by City
- 🕒 Hourly Failure Breakdown
- 📅 Date/City/ATM Slicers
- 🔍 Drill-through to ATM Profile (Zone, Install Date, Type)

## 📁 Project Structure

atm-performance-dashboard/
├── ATM_Performance_Dashboard.pbix ← Main Power BI file
├── datasets/
│ ├── atm_transactions.csv
│ ├── atm_metadata.csv
│ └── dim_date.csv
├── screenshots/
│ ├── dashboard_overview.png
│ ├── drillthrough.png
│ └── map_visual.png
└── README.md

yaml
Copy
Edit

---

## 📂 Datasets Used

| Dataset            | Description                          |
|--------------------|--------------------------------------|
| `atm_transactions` | Transaction ID, Timestamp, Status, Amount, ATM ID |
| `atm_metadata`     | ATM ID, City, Zone, Install Date, Type |
| `dim_date`         | Date, Year, Month, Day, Hour breakdown |

> 💡 All datasets are synthetic and created for demo purposes.

## 📷 Screenshots

| Overview | Drill-through | Map Visual |
|----------|---------------|------------|
| ![Overview](screenshots/dashboard_overview.png) | ![Drillthrough](screenshots/drillthrough.png) | ![Map](screenshots/map_visual.png) |

---

## 🚀 How to Use

1. Clone the repo or download the `.pbix` file
2. Open in Power BI Desktop
3. Load CSVs from the `/datasets` folder
4. Explore the report or publish to Power BI Service

---

## 🔁 Features Implemented

- Line chart: Daily transactions over time
- Stacked column chart: Hourly transaction breakdown by status
- Table visual: Transaction details with conditional formatting
- Map: City-wise transaction volume
- Slicers: Date, City, ATM ID


## 📌 Author

**Anish Mayya**  
LinkedIn: [linkedin.com/in/anishmayya](https://linkedin.com/in/anishmayya)

