# 📊 End-to-End Azure SQL + Power BI Data Analytics Project

![Azure SQL](https://img.shields.io/badge/Azure%20SQL-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Azure Server](https://img.shields.io/badge/Azure%20Server-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Firewall Config](https://img.shields.io/badge/Firewall%20Configuration-FF6F00?style=flat&logo=windowssecurity&logoColor=white)
![CSV Import](https://img.shields.io/badge/CSV%20Import-217346?style=flat&logo=microsoft&logoColor=white)
![SQL Data Cleaning](https://img.shields.io/badge/SQL%20Data%20Cleaning-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![Power%20BI%20Integration](https://img.shields.io/badge/Power%20BI%20Integration-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX Calculations](https://img.shields.io/badge/DAX%20Calculations-005571?style=flat)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-4CAF50?style=flat)

## 📌 Project Overview
This project demonstrates an end-to-end data pipeline using Microsoft Azure, SQL Server Management Studio (SSMS), and Power BI. 

<img width="1280" height="721" alt="{DD9AD161-6CE0-49DE-BBD9-321617371249}" src="https://github.com/user-attachments/assets/570c3be4-c4ab-45df-a9ad-c73a85d88c7b" />

## 📸 Project Screenshots

### Azure SQL Database
<img width="1340" height="934" alt="{C73B1F5A-AE7A-4B4C-B59E-1F8FD008BEAE}" src="https://github.com/user-attachments/assets/22410890-f907-475e-9b65-0bb46ea17f85" />
<img width="1920" height="991" alt="{768E1076-A51B-4A43-B01E-6A2FCB062A97}" src="https://github.com/user-attachments/assets/2eca5a83-8281-4ff0-adf2-c48e8f4206fa" />

### SSMS Connection
<img width="481" height="589" alt="{B056F67E-077E-4109-9AF8-1FCEAADC63CF}" src="https://github.com/user-attachments/assets/6cd7d9fa-027a-4b9a-b210-c30840b804d6" />
<img width="1920" height="1051" alt="{D4CB53C8-A34D-40C0-8C99-2D83D6E08362}" src="https://github.com/user-attachments/assets/29d68da1-f152-48eb-a195-e75e1e78f1ce" />

### Power BI Dashboard
<img width="1280" height="721" alt="{DD9AD161-6CE0-49DE-BBD9-321617371249}" src="https://github.com/user-attachments/assets/570c3be4-c4ab-45df-a9ad-c73a85d88c7b" />


The workflow includes:
- Creating Azure SQL Database and Server
- Configuring firewall and security
- Importing CSV data into Azure
- Performing data cleaning in SQL
- Connecting Power BI to Azure SQL
- Creating calculated columns and advanced visualizations

---

## 🏗 Architecture

CSV File → Azure SQL Database → SSMS (Data Cleaning) → Power BI → Dashboard Visualization

---

## ⚙️ Technologies Used

- Microsoft Azure SQL Database
- SQL Server Management Studio (SSMS)
- Power BI Desktop
- CSV Flat File Import
- T-SQL
- DAX

---

## 🚀 Project Steps

### 1️⃣ Azure Setup
- Created Azure SQL Server
- Created Azure SQL Database
- Configured Server Firewall Rules
- Added client IP address to allow external connection

### 2️⃣ Database Connection
- Connected Azure SQL Database to SSMS
- Verified server authentication and credentials

### 3️⃣ Data Import
- Imported CSV file using SSMS Flat File Import Wizard
- Created structured table in Azure SQL

### 4️⃣ Data Cleaning (Azure SQL)
Performed:
- Basic null handling
- Data type corrections
- Removed unnecessary columns
- Standardized data formatting

### 5️⃣ Power BI Integration
- Connected Power BI to Azure SQL Database
- Loaded cleaned dataset
- Performed additional transformation in Power Query

### 6️⃣ Data Modeling & Calculations (DAX)
Created new calculated columns:
- Discount
- Profit
- Cost Price
- Profit %

---

## 📊 Dashboard Visualizations

- 📊 Stacked Bar Chart – Top 5 by Average Discount
- 🍩 Donut Chart – Top 5 Brands by Highest Number of Varieties
- 🥧 Pie Chart – Bottom 5 by Average Profit %
- 🎀 Ribbon Chart – Top Brands by Highest Average Sales Price
- 📈 Top 5 by Highest Average Profit %

---

## 📈 Key Insights

- Identified brands offering highest discount rates
- Analyzed product variety distribution
- Determined most profitable and least profitable brands
- Evaluated average sales price trends across brands

---

## 🎯 Skills Demonstrated

- Cloud Database Deployment (Azure)
- SQL Data Management
- Data Cleaning & Transformation
- Firewall & Security Configuration
- Power BI Data Modeling
- DAX Calculations
- Business Intelligence Dashboarding

---

## 👨‍💻 Author
Carl John Haro Data Analyst | Data engineer
