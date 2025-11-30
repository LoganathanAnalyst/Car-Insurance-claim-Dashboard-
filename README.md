# 🚗 Car Insurance Claim Dashboard – Power BI Analytics

---

## 🌐 Overview
The **Car Insurance Claim Dashboard** is an interactive Power BI report designed to analyze policy data, claim patterns, risk categories, demographics, and vehicle-related insights. This dashboard helps insurance analysts, managers, and business users make smarter decisions using real-time KPIs and drill-down analytics.

---

## ⭐ Key Features

### 🔢 **Top-Level KPIs**
- **Total Policies:** 10,000  
- **Total Claims:** 3,133  
- **Claim Rate:** 31.33%  
- **High-Risk Drivers:** 3.96%  
- **Avg. Annual Mileage:** 11,712 miles  

---

### 👥 **Demographic Insights**
- Claims distribution by **Gender**  
- Claims distribution by **Age Group** (Young, Middle Age, Older Adults, Senior Citizens)  
- Claims by **Education Level** (High School, College, University, None)  
- Income-based claim segmentation (through slicers)

---

### 🚘 **Vehicle Insights**
- Claims by **Vehicle Type** (Sedan, Sports Car)  
- Claims by **Vehicle Year** (Before 2015 vs After 2015)  
- Claims by **Driver Behaviour Risk** (Low, Moderate, High Risk)

---

### 📈 **Mileage Analysis**
- Annual mileage distribution histogram  
- Binned mileage intervals to identify driving patterns  

---

### 📑 **Claims Detail Page**
- Full list of customer-level claim data  
- Attributes displayed:  
  - Age, Gender, Race  
  - Income Category  
  - Education Level  
  - Risk Category  
  - Claim Outcome  
  - Vehicle Type & Vehicle Year  
- Row-level sorting and filtering  
- Additional filters for Age Group, Gender, Income  

---

## 🧱 Architecture
```
   ┌────────────────────────┐
   │      Data Sources       │
   │   Excel • CSV • SQL DB  │
   └────────────┬───────────┘
                │
   ┌────────────▼────────────┐
   │     Power Query (ETL)    │
   │ Clean • Transform • Merge│
   └────────────┬────────────┘
                │
   ┌────────────▼────────────┐
   │     Data Model (Star)    │
   │ Fact Claims / Dim Driver │
   │ Dim Vehicle / Dim Policy │
   └────────────┬────────────┘
                │
   ┌────────────▼────────────┐
   │         Power BI         │
   │ KPIs • Visuals • Filters │
   └──────────────────────────┘
```

---

## ⚙️ Installation & Setup

### **1️⃣ Open the Dashboard**
```
Car Insurance Claim Dashboard.pbix
```

### **2️⃣ Connect Your Data**
Supported sources:
- Excel  
- CSV  
- SQL Server / Database  

### **3️⃣ Refresh the Data**
Use:
```
Home → Refresh
```

---

## 🖼️ Sample Dashboard (Screenshots)
<img width="921" height="544" alt="Car claim dashboard" src="https://github.com/user-attachments/assets/76b69acc-7a71-4884-be33-41b59466233a" />


- **Overview Page** (KPIs, demographics, vehicle insights, mileage histogram)  
- **Claim Details Page** (detailed table with filters)

---

## 🏷️ Badges
```md
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=power-bi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-1F6FEB)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-008272)
![Data Modeling](https://img.shields.io/badge/Data%20Modeling-Star%20Schema-blue)
![Status](https://img.shields.io/badge/Status-Active-success)
```

---

## 🧠 Skills Demonstrated
- KPI creation using DAX  
- Power BI interactive reporting  
- Power Query data transformation  
- Data modeling with Star Schema  
- Insurance domain analysis  
- Visual storytelling with charts, slicers, and drillthrough  

---

## 🧩 Roadmap
- Add policy-level drillthrough  
- Add fraud insight indicators  
- Add claims forecasting with analytics  
- Add mobile layout version  
- Add AI-based outlier detection  

---

## 🤝 Contributing
Have suggestions or improvements?  
Feel free to open issues or submit pull requests.

---

## ⭐ Support This Project
If you liked this dashboard, please give this repository a ⭐ on GitHub.  
Your support encourages more Power BI projects!

---

## 👨‍💻 About the Author
Hi, I’m **Loganathan**, a Data Analyst & Power BI Developer focused on turning raw data into actionable insights.  
Thank you for reviewing this project! 🚀📊  

📩 **Contact:**  
**loganathanvizasia@gmail.com**

