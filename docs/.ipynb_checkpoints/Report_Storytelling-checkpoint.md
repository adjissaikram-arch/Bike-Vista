# 🚴‍♀️ BikeVista: Functional Demo & Data Storytelling

This document serves as a walkthrough of the **BikeVista** reporting solution. It demonstrates how raw data is transformed into actionable business insights through interactive features, adhering to a logical storytelling flow.

---

## 1. The Executive Dashboard: The Big Picture
**Goal:** Provide leadership with an immediate view of high-level metrics.

![Executive Dashboard](../assets/desktop/1-Exec_dashboard.png)

This is the command center. At a glance, we track:
* [cite_start]**Total Revenue:** €24.9M [cite: 220]
* [cite_start]**Profit Margin:** A healthy €10.5M profit [cite: 221]
* [cite_start]**Volume:** 25,200 orders processed [cite: 222]
* [cite_start]**Quality Control:** A return rate of only 2.2% [cite: 223]

[cite_start]**Key Insight:** The *Revenue Trending* chart reveals a clear upward trajectory from 2020 to 2022, signaling successful business scaling[cite: 224]. [cite_start]Accessories are the leading category by volume, while specific products like "Tires and Tubes" drive high turnover[cite: 226, 228].

---

## 2. Interactive Insights: Self-Service BI
Power BI is not about static numbers. We empower users to explore the "Why" behind the data.

### Custom Tooltips
![Tooltip Demo](../assets/desktop/2-Exec_tooltip.jpg)
[cite_start]Hovering over the trend line reveals granular details—weekly order breakdowns, revenue, and profit for that specific period[cite: 239]. Stakeholders get answers instantly without requesting custom reports.

### Drill-Down Capabilities
![Drill Down](../assets/desktop/3-Exec_drill.jpg)
Using the drill hierarchy, users can move from a yearly strategic view down to monthly or weekly tactical views. [cite_start]For instance, drilling into **January 2022** reveals a revenue peak of **€4.06M**[cite: 250].

---

## 3. Seamless Navigation: Drill-Through
![Drill Through](../assets/desktop/4-Exec_drillthrough.jpg)
To maintain a clean interface while offering depth, I implemented **Drill-Through** features. [cite_start]By right-clicking a product (e.g., in the Top 10 list), a user navigates directly to a filtered *Product Details* page[cite: 261]. This creates a cohesive analytical experience.

---

## 4. Geographic Analysis
**Goal:** Optimize logistics and identify growth territories.

![Map View](../assets/desktop/6-Map_pacific.jpg)
*(Above: Map filtered on the Pacific Region)*

The map visualizes our global footprint. [cite_start]When focusing on the **Pacific region**, we instantly identify Australia as a key market generating **6,060 orders**[cite: 272]. This geospatial insight aids in territory planning and stock distribution.

---

## 5. Product Performance Deep-Dive
**Goal:** Analyze profitability and variance against targets.

![Product Filtered](../assets/desktop/8-Product_filtered.jpg)

[cite_start]When a specific product is selected—for example, the **Mountain Tire Tube**—the entire page adapts dynamically[cite: 287]:
* [cite_start]**Orders:** 275 units (slightly under the 293 target)[cite: 288].
* [cite_start]**Financials:** €1,710 profit with a 6.41% margin[cite: 289].
* **Trend:** The bottom chart isolates the profit trend for this specific item, helping spot seasonality.

---

## 6. Customer Intelligence
**Goal:** Understand customer lifetime value (CLV) and segmentation.

![Customer Details](../assets/desktop/9-Customer_page.jpg)

[cite_start]We have **17,400 customers** with a strong average revenue of **€1,400 per customer**[cite: 302].
* [cite_start]**Segmentation:** High-income professionals make up our largest buyer segment[cite: 304].
* **Top Performer:** The table highlights our VIP clients, such as **Mrs. [cite_start]Shan Maurice**, who generated **€12,408** in revenue[cite: 307].

This view is critical for designing retention strategies and loyalty programs.

---

## 7. Data Governance
Transparency is essential. [cite_start]A dedicated **Data Dictionary** page documents every DAX measure and calculation logic, ensuring auditability and trust in the figures[cite: 320, 321].

---

*This walkthrough demonstrates the end-to-end user journey, from high-level KPIs to granular customer analysis.*