## Project Overview
This project demonstrates how to transform raw sales data into meaningful business insights using **Power BI**.  
The dataset includes transaction-level details such as customer demographics, product brands, payment methods, ratings, and purchase locations.

## 📂 Dataset
- **File:** `Mobile Sales Data.xlsx`
- **Sheet Name:** `Data`
- **Columns:**
  - Transaction ID, Date, Day/Month/Year
  - Brand, Mobile Model
  - Units Sold, Price Per Unit
  - City, Payment Method
  - Customer Age, Ratings
 
## 🛠 Data Transformation
- Created calculated column for `Sales = Units Sold * Price Per Unit`
- Added helper columns (`WeekdayNumber`, `MonthNumber`, `MonthName`) for sorting visuals
- Created DAX measures for KPIs:
  - `Total Sales`
  - `Total Quantity`
  - `Transaction Count`
  - `Avg Sales per Transaction`

## 🚀 Features
- **KPIs**: Total Sales, Avg Sales per Transaction, Total Quantity, Transaction Count
- **Map**: Sales distribution across Indian cities
- **Line Chart**: Quantity sold by Month
- **Donut Chart**: Transactions by Payment Method
- **Waterfall/Line Chart**: Sales trend by Day of Week
- **Table**: Brand performance (Sales, Quantity, Transactions)
- **Bar Charts**: Customer Ratings, Sales by Brand

## 📂 Files
- `Data.xlsx` → Dataset
- `Mobile Sales Dashboard.pbix` → Power BI Dashboard
- `README.md` → Documentation 
- `dashboard-preview.png` → Dashboard Preview  

![Dashboard Preview](https://github.com/user-attachments/assets/47a008d3-ed0c-4c0d-9669-1070c3a3b336)

## 🎯 Key Insights
- Apple & Samsung lead sales, closely followed by OnePlus, Vivo, and Xiaomi
- Sales show seasonal fluctuations with peak months around March & July
- UPI, Debit, Credit, and Cash are used almost equally
- High customer satisfaction ratings (majority 4–5 stars)
- Delhi, Mumbai, and Bangalore are major sales hubs

## 👤 Author
**[Ayush Aman](https://www.linkedin.com/in/ayush-aman-039817161/)**
