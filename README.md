# 📊 Revenue, Commission & Settlement Analytics Dashboard

## 🔍 Project Overview
This project analyzes transactional payment data processed through Edviron’s platform.  
The objective is to compute and visualize revenue distribution across multiple pricing layers and evaluate partner, gateway, and settlement performance.

---

## 💰 Revenue Model

The dashboard is built around three pricing layers:

1. **Edviron Buying Price** (Cost to Edviron)
2. **Partner Pricing (ERP Pricing)**
3. **Merchant Pricing (School Pricing)**

### Revenue Formulas

- **ERP Revenue** = Merchant Pricing – Partner Pricing  
- **Edviron Net Revenue** = Partner Pricing – Edviron Buying  
- **Edviron Gross Revenue** = Merchant Pricing – Edviron Buying  

All percentage-based pricing was normalized into absolute INR values.

---

## 📈 Dashboard Features

### 🔹 KPI Overview
- Total Transactions
- Total GMV
- ERP Revenue
- Edviron Net Revenue
- Edviron Gross Revenue
- Pending Exposure
- Unique Users

### 🔹 Performance Analysis
- Revenue Split (ERP vs Edviron)
- Time-based Revenue Trend
- Gateway-wise Contribution
- Payment Method Mix
- Partner-wise Performance Matrix

---

## ⚙️ Tools & Technologies Used
- Power BI
- Power Query (Data Cleaning & Transformation)
- DAX (Revenue Modeling & Calculations)
- Data Modeling & Relationships

---

## 🔎 Validations Implemented
- Revenue reconciliation check
- Negative margin detection logic
- Dynamic slicer-based filtering
- No hard-coded financial calculations

---

## 📂 Repository Contents
- Power BI Dashboard (.pbix)
- Explanation Note (PDF)
- Dashboard Screenshot

---

## 👤 Author
**Surya Jai**  
Aspiring Data Analyst  
