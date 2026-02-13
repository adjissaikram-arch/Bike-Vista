# 🚴‍♀️ Bike-Vista

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Analytics-yellow?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-lightgrey?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange?style=flat-square)
![Made With](https://img.shields.io/badge/Made%20With-Power%20BI%20Desktop%20%26%20Service-yellow?style=flat-square)
![Data Source](https://img.shields.io/badge/Data%20Source-Excel%20→%20MySQL%20→%20Power%20BI-lightblue?style=flat-square)
![Workspace](https://img.shields.io/badge/Environment-Dev%20%7C%20Test%20%7C%20Prod-lightgreen?style=flat-square)

---

## 📖 About the Project

*Bike-Vista* is a complete Power BI analytics project focused on analyzing global bicycle sales.  
It simulates a **global manufacturing company** that produces cycling equipment and accessories.  

The goal is to build an interactive BI solution that enables users to:
- Track **key performance indicators (KPIs)** such as sales, revenue, profit, and returns  
- Compare **regional performance**  
- Analyze **product-level trends**  
- Identify **high-value customers**

The project is built using a **MySQL relational database** as the primary data source, connected through **dynamic connection parameters** for flexible and secure access.  
It includes **desktop, mobile, and service versions** of Power BI reports, and implements **Row-Level Security (RLS)** and **Object-Level Security (OLS)** to protect sensitive data.  

The solution follows a **professional BI lifecycle** with three dedicated Power BI workspaces:
- **Development** – used for building, modeling, and testing new datasets, reports, and **Dataflows**.  
- **Test** – used for validating datasets, transformations, and dashboard performance before production release.  
- **Production** – used for publishing and maintaining the final dashboards and datasets. In this environment, the final **Power BI Dashboard** and a corresponding **Power BI App** are created and shared with end users.  

A **Power BI Deployment Pipeline** automates the migration between environments (Dev → Test → Prod), ensuring version control, governance, and data consistency.  

The entire project is **hosted on GitHub**, following a **Continuous Integration / Continuous Deployment (CI/CD)** workflow to manage version control and automate updates to Power BI Service.  

---

## 🧱 Project Architecture

### 1. Data Source Layer
- **Technology:** MySQL Relational Database  
- Contains structured data for customers, products, sales, and returns  
- Connection established using **dynamic connection parameters** for environment flexibility  

### 2. Data Preparation Layer (Power BI Service – Dataflows)
- Data extracted from MySQL into **Power BI Dataflows**  
- Each **Dataflow** handles transformation, cleaning, and standardization using Power Query (M language)  
- Follows a **star schema** design for optimized reporting performance  
- Shared across environments for **reusability and consistency**  

### 3. Data Modeling and Visualization (Power BI Desktop)
- Power BI Desktop used for data modeling, relationships, and DAX calculations  
- Visual dashboards created for both **desktop and mobile** experiences  
- Published to Power BI Service for centralized access  

### 4. Security and Governance
- **Row-Level Security (RLS)** restricts data visibility by user roles and regions  
- **Object-Level Security (OLS)** hides specific tables or fields from unauthorized users  
- Consistent governance with clear naming conventions and role-based permissions  

### 5. Deployment and Environment Management
- The project is structured into three environments:  
  - **Development** – creation and testing of reports and Dataflows  
  - **Test** – validation of models and performance tuning  
  - **Production** – final publication and app deployment for business users  
- Automated migration between environments using **Power BI Deployment Pipelines**  

### 6. Version Control and CI/CD
- Source files, SQL scripts, and documentation are **hosted on GitHub**  
- **CI/CD workflow** automates version control and deployment to Power BI Service  
- Ensures consistent synchronization between environments  

### 7. End-User Experience
- End users access the solution through the **Power BI App** in the Service environment  
- Reports optimized for **desktop, mobile, and service** versions for seamless experience  

---

## ⚙️ Technical Stack & Tools Used

| Category | Tool / Technology | Purpose |
|-----------|------------------|----------|
| Database | MySQL | Data storage and management |
| BI Tool | Power BI Desktop / Power BI Service | Data modeling and visualization |
| ETL | Power BI **Dataflows** | Data transformation and cleaning |
| Security | RLS / OLS | Data access control |
| Version Control | Git & GitHub | Source code and version tracking |
| Automation | GitHub Actions | CI/CD deployment pipeline |
| Documentation | Markdown | Technical documentation and README |

---

## 🧩 Project Structure
Bike-Vista/
│
├── Data/ # Sample datasets (CSV, SQL dumps)
├── SQL/ # MySQL scripts (create tables, load data)
├── PowerBI/ # Power BI reports (.pbix)
├── Docs/ # Architecture diagrams and documentation
├── Screenshots/ # Power BI screenshots (to add later)
└── README.md

---

## 📸 Screenshots (coming soon)

This section will include:
- The **BikeVista Dashboard**
- The **Dataflows** structure
- The **Deployment Pipeline**
- The **Mobile version** of the report

All images will be stored separately in the `/Screenshots/` folder.

---

## 👤 Author

**Ikram BERHAIL**  
📍 Based in France | 💼 Aspiring Data Analyst  
🔗 [GitHub](https://github.com/adjisssaikram-arch)  


---

⭐ *If you like this project, don’t forget to star the repository!*
