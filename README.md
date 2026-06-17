# 📊 BCRP Macroeconomic Monitoring Dashboard

<p align="center">
  <img src="Images/dashboard_overview.png" width="900">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black">
  <img src="https://img.shields.io/badge/SQL%20Server-Data%20Warehouse-CC2927?logo=microsoftsqlserver&logoColor=white">
  <img src="https://img.shields.io/badge/SSIS-ETL-0078D4?logo=microsoft&logoColor=white">
  <img src="https://img.shields.io/badge/API-Integration-00A4EF">
  <img src="https://img.shields.io/badge/Data%20Model-Star%20Schema-blue">
</p>

---

## 📌 Project Overview

Business Intelligence solution designed to monitor Peru's key macroeconomic indicators through an interactive dashboard developed in Power BI.

The project integrates economic data from APIs and structured sources, processes it through ETL workflows built in SSIS, stores it in a SQL Server Data Mart using a Star Schema model, and visualizes the results through executive dashboards.

---

## 🎯 Objectives

- Monitor Peru's macroeconomic performance.
- Track inflation trends and forecasts.
- Analyze the Central Bank reference interest rate.
- Monitor exchange rate fluctuations.
- Demonstrate Data Warehouse, ETL, and Business Intelligence best practices.

---

## 📊 Dashboard Features

### 💱 Exchange Rate Monitoring
- Real-time exchange rate obtained from external APIs.
- Automatic refresh and update timestamp.

### 🏦 Reference Interest Rate
- Latest BCRP reference rate.
- Executive KPI visualization.

### 📈 Inflation Analysis
- Historical inflation monitoring.
- Trend analysis over time.

### 🤖 Inflation Forecasting
- Comparison between actual and forecasted inflation.
- Predictive analytics integration.

### 🧩 IPC Components Analysis
- Breakdown of Consumer Price Index components.
- Interactive treemap visualization.

### 📅 Time Filtering
- Dynamic date slicers.
- Historical period analysis.

---

## 🏗️ Solution Architecture

```text
External APIs
(BCRP / Exchange Rate)

        │
        ▼

      SSIS
   ETL Process

        │
        ▼

   SQL Server
    Data Mart
  (Star Schema)

        │
        ▼

    Power BI
 Executive Dashboard
```

---

## ⭐ Data Model

### Dimensions

- Dim_Fecha
- Dim_Indicador
- Dim_Fuente
- Dim_ComponenteIPC

### Fact Tables

- Fact_IndicadoresEconomicos
- Fact_IPC_Componentes
- Fact_PronosticoInflacion

---

## 🔄 ETL Process

The ETL workflow was developed using SQL Server Integration Services (SSIS) and includes:

- Data extraction from APIs.
- Data transformation and validation.
- Data loading into SQL Server.
- Historical data consolidation.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Power BI | Dashboard & Data Visualization |
| SQL Server | Data Warehouse |
| SSIS | ETL Processes |
| DAX | Business Calculations |
| REST APIs | Real-time Data Integration |
| Star Schema | Dimensional Modeling |

---

## 📸 Dashboard Preview

### 📊 Main Dashboard

![Dashboard](Images/dashboard_overview.png)

---

## 🚀 Key Skills Demonstrated

- Business Intelligence
- Data Warehousing
- Dimensional Modeling
- Star Schema Design
- ETL Development
- SQL Development
- Data Visualization
- KPI Design
- Forecasting Analytics
- API Integration

---

## 👨‍💻 Author

### Leonardo Martín Angulo Mogollón

Data Analyst | BI Developer | Data Governance

🔗 LinkedIn: https://linkedin.com/in/leonardo-martín-angulo-mogollón

🔗 GitHub: https://github.com/langulomogollon

---
