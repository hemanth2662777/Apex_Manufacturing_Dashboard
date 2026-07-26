# 🏭 Apex Manufacturing Dashboard

<div align="center">

### 📊 Enterprise Business Intelligence Solution for Manufacturing Performance Analytics

Transforming manufacturing operations into actionable business insights using **Microsoft Power BI**, **DAX**, **Power Query**, and **Star Schema Data Modeling**.

<br>

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-02569B?style=for-the-badge)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-742774?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

# 📌 Project Overview

Manufacturing organizations generate large volumes of operational data every day from production lines, quality inspections, procurement, inventory, suppliers, employees, and machine maintenance. Without centralized reporting, decision-makers often struggle to monitor business performance efficiently.

The **Apex Manufacturing Executive Dashboard** is a comprehensive Business Intelligence solution built with **Microsoft Power BI** that transforms raw manufacturing data into interactive dashboards and meaningful business insights.

The dashboard enables executives, plant managers, and operations teams to monitor manufacturing performance, evaluate operational efficiency, analyze production trends, identify quality issues, optimize inventory, and improve procurement planning through real-time visual analytics.

This project demonstrates the complete Business Intelligence lifecycle, including:

- Business Requirement Analysis
- Data Collection
- Data Cleaning & Transformation
- Data Modeling (Star Schema)
- DAX Measure Development
- Interactive Dashboard Design
- KPI Development
- Business Insight Generation

---

# 🎯 Business Problem

Manufacturing companies often face several operational challenges that impact productivity and profitability.

### Major Challenges

- Limited visibility into production performance
- Difficulty tracking manufacturing KPIs
- High machine downtime
- Increasing maintenance costs
- Inventory shortages
- Procurement delays
- Product quality issues
- Manual reporting processes
- Slow executive decision-making

These challenges reduce operational efficiency and make strategic planning more difficult.

---

# 💼 Business Objectives

The primary objective of this project is to develop a centralized executive dashboard that enables stakeholders to monitor manufacturing performance through interactive visual analytics.

### Objectives

- Build an executive-level manufacturing dashboard
- Monitor production performance across plants
- Track production efficiency
- Analyze product quality
- Evaluate machine performance
- Monitor maintenance activities
- Analyze inventory availability
- Measure procurement performance
- Track supplier performance
- Enable interactive filtering and drill-down analysis
- Support strategic business decision-making

---

# ⭐ Project Highlights

| Feature | Description |
|----------|-------------|
| 📊 Executive Dashboard | High-level business overview |
| 🏭 Production Analytics | Production monitoring across plants |
| ⚙ Maintenance Analytics | Machine health and downtime |
| 📦 Inventory Analytics | Inventory stock monitoring |
| 🛒 Procurement Analytics | Supplier and purchase analysis |
| ✅ Quality Analytics | Defect monitoring and quality trends |
| 📈 KPI Dashboard | Executive performance indicators |
| 🎯 Interactive Filters | Dynamic report exploration |
| 🔍 Drill-Down Analysis | Detailed operational insights |
| ⭐ Star Schema | Optimized data model |

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| Microsoft Power BI | Dashboard Development |
| Power Query | ETL & Data Cleaning |
| DAX | KPI Calculations |
| Microsoft Excel | Source Data |
| Data Modeling | Star Schema |
| SQL | Data Analysis |
| Git | Version Control |
| GitHub | Project Repository |

---

# 🏗 Solution Architecture

```text
                  Manufacturing Data Sources
                           │
      ┌────────────────────┼────────────────────┐
      │                    │                    │
 Production          Inventory          Procurement
      │                    │                    │
      └──────────────┬─────┴──────────────┬─────┘
                     │
             Power Query (ETL)
                     │
                     ▼
          Data Cleaning & Transformation
                     │
                     ▼
             Star Schema Data Model
                     │
                     ▼
               DAX Calculations
                     │
                     ▼
          Interactive Power BI Dashboard
                     │
                     ▼
            Business Insights & KPIs
```

---

# 📂 Dataset Overview

The dashboard integrates multiple manufacturing datasets representing various operational departments.

## Data Sources

| Dataset | Description |
|----------|-------------|
| Production | Manufacturing production records |
| Product Master | Product information |
| Plant | Manufacturing plant details |
| Employees | Employee information |
| Machines | Machine information |
| Inventory | Inventory stock |
| Procurement | Purchase records |
| Suppliers | Supplier information |
| Maintenance | Machine maintenance logs |
| Quality | Product quality inspections |

---

# 📊 Dataset Summary

| Dataset | Approximate Records |
|----------|-------------------:|
| Production | 5,000 |
| Quality | 2,000 |
| Inventory | 500 |
| Maintenance | 800 |
| Procurement | 1,000 |
| Products | 250 |
| Employees | 500 |
| Machines | 120 |
| Suppliers | 50 |
| Plants | 4 |

---

# 🎯 Business KPIs

The dashboard tracks key manufacturing performance indicators.

| KPI | Description |
|------|-------------|
| Total Production | Total units manufactured |
| Production Target | Planned production output |
| Production Efficiency % | Actual vs Target production |
| Defective Units | Total defective products |
| Defect Rate % | Manufacturing quality |
| Inventory Stock | Current inventory |
| Maintenance Cost | Maintenance expenditure |
| Procurement Cost | Purchasing expenditure |
| Purchase Orders | Procurement volume |
| Machine Availability | Machine utilization |
| Supplier Count | Active suppliers |
| Employee Productivity | Workforce performance |

---
