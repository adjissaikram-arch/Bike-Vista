# 🚴‍♀️ Bike-Vista: Global Sales Analytics

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Analytics-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=flat-square&logo=mysql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange?style=flat-square)

> **A scalable BI solution simulating a global manufacturing company.**
> *From raw SQL data to actionable insights.*

---

## 🚀 Project Overview

**Bike-Vista** is an end-to-end analytics project focused on analyzing global bicycle sales. The goal was to build a robust BI solution that enables stakeholders to track KPIs (Revenue, Profit, Returns) and identify growth opportunities across regions.

This repository demonstrates a **professional BI lifecycle**, incorporating:
* **Advanced Data Modeling** (Star Schema, Time Intelligence).
* **Data Governance** (Dataflows, RLS, OLS).
* **DevOps Practices** (CI/CD with GitHub Actions, Deployment Pipelines).

---

## 📂 Documentation & Demos

I have prepared detailed documentation to showcase both the **Functional** (User view) and **Technical** (Back-end) aspects of this project.

### 1️⃣ [**View the Functional Storytelling**](docs/Report_Storytelling.md) 📊
> **Click above** to see the report in action!
> A guided tour through the report features: Executive Dashboard, Tooltips, Drill-Through, and Customer Intelligence.

### 2️⃣ [**View the Technical Workflow (PDF)**](docs/BikeVista_Service_Workflow.pdf) ⚙️
> **Click above** to download the architecture diagram.
> Details on: MySQL Setup, Dataflows ETL, and the Power BI Service Deployment Pipeline (Dev -> Test -> Prod).

---

## 📸 Key Visuals

| **Executive Dashboard** | **Geographic Analysis** |
|:-----------------------:|:-----------------------:|
| ![Dashboard](assets/desktop/1-Exec_dashboard.png) | ![Map](assets/desktop/6-Map_pacific.jpg) |
| *Real-time KPI monitoring* | *Regional performance tracking* |

---

## 🏗️ Technical Architecture

```mermaid
graph LR
    A[MySQL Database] -->|Gateway| B(Dataflows ETL)
    B --> C{Semantic Model}
    C -->|Desktop/Service| D[Power BI Reports]
    E[GitHub Repo] -->|CI/CD Action| D

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

## 📸 Screenshots 

This section will include:
- The **Desktop version** of the report
- The **Service version** of the report
- The **Mobile version** of the report

All images are stored separately in the `/assets/` folder.

---

## 👤 Author

**Ikram BERHAIL**  
📍 Based in France | 💼 Aspiring Data Analyst  
🔗 [GitHub](https://github.com/adjisssaikram-arch)  


---

⭐ *If you like this project, don’t forget to star the repository!*

