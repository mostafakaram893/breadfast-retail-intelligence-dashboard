# 🥐 Breadfast Executive E-Commerce & Product Intelligence Dashboard

[![Power BI](https://img.shields.io/badge/Power_BI-Desktop-F2C811?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Advanced_Measures-005FB8)](https://learn.microsoft.com/en-us/dax/)
[![HTML5 & CSS3](https://img.shields.io/badge/Visuals-HTML5%20%7C%20CSS3%20%7C%20SVG-E34F26)](https://en.wikipedia.org/wiki/HTML5)
[![Status](https://img.shields.io/badge/Status-Completed-success)]()

## 📌 Executive Summary
An enterprise-grade, two-page interactive Business Intelligence portal designed for **Breadfast** (Egypt's leading quick-commerce & on-demand grocery delivery platform). 
The project moves beyond native Power BI visuals by incorporating **custom HTML5, CSS3 `@keyframes` animations, and dynamic SVG graphics** to deliver an interactive web-app experience adhering strictly to Breadfast's corporate visual identity (`#AA0082` Berry and `#FDF1E7` Warm Blush).

---

## 🎯 Key Business Questions Answered
1. **High-Level Revenue Health:** What are the company-wide sales, profit margins, completed orders, and active customer counts?
2. **Regional Expansion & Fulfillment:** Which geographical regions drive revenue, and how is order delivery speed distributed (Same Day vs Express vs Standard)?
3. **Product & Sub-Category Profitability:** Which product lines generate the highest profit margins, and which sub-categories are loss-makers?
4. **Unit Economics:** What is the Average Order Value (AOV), Profit per Order, and average Basket Size across customer segments?

---

## 📊 Core Business Metrics (KPIs)
* **Total Sales:** `$2.30M`
* **Total Profit:** `$286K` (*12.4% Overall Profit Margin*)
* **Total Orders:** `9,994 Completed Orders`
* **Total Quantity Sold:** `38K Units`
* **Active Customer Base:** `793 Unique Customers`
* **Catalog Coverage:** `1,862 Active SKUs`

---

## 🛠️ Technical Implementation Highlights
* **Dynamic HTML/CSS/SVG DAX Measures:** Developed animated radial progress rings, glowing badges, and customized horizontal bar charts rendered live via the HTML Content custom visual.
* **Monthly Seasonality Curve:** Built a mathematical SVG curve rendered directly through DAX variables (`LOOKUPVALUE` & `MAXX`) with gradient shading and pulsing data nodes.
* **Segmented Unit Economics:** Calculated real-time Cart Size (`Quantity / Orders`) and Average Order Value (`Sales / Orders`).
* **Interactive Navigation:** Implemented customized Page Navigation buttons matching brand pill styles with hover states.

---

## 📁 How to View the Project
1. Clone this repository or download the `.pbix` file.
2. Open the file in **Power BI Desktop**.
3. Explore the interactive cross-filtering, slicers, and animated custom visuals.
