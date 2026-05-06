# 📊 Enterprise Sales Business Intelligence System

<p align="center">
  ⚙️ SSIS | 🧠 SSAS | 📈 Power BI | 🗄️ SQL Server | ⭐ Star Schema
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Database-SQL%20Server-blue">
  <img src="https://img.shields.io/badge/ETL-SSIS-green">
  <img src="https://img.shields.io/badge/Analytics-SSAS-orange">
  <img src="https://img.shields.io/badge/Dashboard-PowerBI-yellow">
  <img src="https://img.shields.io/badge/Architecture-Business%20Intelligence-red">
</p>

---

# 📊 Project Overview

This project demonstrates the implementation of a complete Business Intelligence solution using the Microsoft BI Stack.

The solution extends a sales data warehouse by integrating:

- ETL pipelines using SSIS
- Star schema modelling
- SSAS multidimensional cube development
- Interactive Power BI dashboards
- Enterprise-style sales analytics

The project uses the AdventureWorks sales dataset to simulate real-world business reporting and decision-making workflows.

---

# 🏗️ Solution Architecture

## 🔹 Core Components

### 📦 Data Warehouse
- Fact table for sales transactions
- Dimension tables for:
  - Customer
  - Product
  - Store
  - Time

### ⚙️ ETL Layer (SSIS)
- Data extraction from flat files
- Data transformation and cleansing
- Data loading into SQL Server warehouse

### 🧠 OLAP Layer (SSAS)
- Cube creation
- Measures and dimensions
- Hierarchies and aggregations
- Multidimensional analytics

### 📈 Reporting Layer (Power BI)
- Interactive dashboard
- KPI analysis
- Sales trends and visual analytics

---

# ⭐ Star Schema Design

The warehouse follows a Star Schema architecture for optimized analytical querying.

## Fact Table
- FactTable
  - SalesAmount
  - Quantity
  - ProductKey
  - CustomerKey
  - DateKey
  - StoreKey

## Dimension Tables
- CustomerData
- ProductData
- StoreData
- TimeData

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| SQL Server | Data Warehouse |
| SSIS | ETL Pipeline |
| SSAS | OLAP Cube Development |
| Power BI | Dashboard & Reporting |
| Star Schema | Dimensional Modelling |

---

# 🔄 ETL Pipeline (SSIS)

The ETL process performs:

- Data extraction from source files
- Data cleansing and transformation
- Data validation
- Loading into warehouse tables
- Relationship mapping between dimensions and fact table

---

# 🧠 SSAS Cube Model

The project includes a multidimensional cube designed for business analytics.

### Cube Features
- Dimensions
- Measures
- Hierarchies
- Aggregations
- Drill-down analysis

This enables high-performance analytical querying for decision-making.

---

# 📈 Power BI Dashboard

The dashboard provides insights into:

- Revenue performance
- Product sales trends
- Customer purchasing behaviour
- Store-level performance
- Time-based sales analytics

### Dashboard Features
- KPI cards
- Interactive filtering
- Trend analysis
- Comparative visuals
- Regional performance analysis

---

# 🗄️ Dataset Information

The project uses structured sales data including:

- Customer information
- Product details
- Store data
- Time dimension
- Sales transaction records

The dimensional structure supports enterprise-level reporting and analytics.

---

# 📊 Business Insights

The BI system enables analysis of:

- Sales growth trends
- Top-performing products
- Customer purchasing patterns
- Regional sales performance
- Monthly and quarterly revenue analysis

---

# 🚀 Key Features

✅ Enterprise-style BI architecture  
✅ Automated ETL workflows  
✅ Multidimensional cube analytics  
✅ Interactive Power BI dashboards  
✅ Star schema implementation  
✅ Business-focused reporting  

---

# 💼 Skills Demonstrated

- Data Warehousing
- ETL Development
- SSIS
- SSAS
- Power BI
- SQL Server
- OLAP Analytics
- Star Schema Modelling
- Business Intelligence Reporting

---

# 🔮 Future Enhancements

- Real-time data integration
- Cloud deployment
- Predictive analytics
- Automated reporting workflows
- Advanced KPI forecasting
- Role-based dashboard access

---

# ⭐ Conclusion

This project demonstrates the implementation of an enterprise-level Business Intelligence system using SQL Server, SSIS, SSAS, and Power BI. The solution combines ETL automation, multidimensional analytics, and interactive reporting to support data-driven business decision-making.
