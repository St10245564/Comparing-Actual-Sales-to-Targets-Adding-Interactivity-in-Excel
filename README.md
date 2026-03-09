# 📊 Multi-Year Sales vs Target Dashboard with Scenario & Segment Analysis

> **Week 8 Group Project** — Comparing Actual Sales to Targets & Adding Interactivity in Excel  
> **Course Module:** Business Intelligence & Data Analytics  
> **Team:** Data Drifters

---

## 📸 Dashboard Preview

<img width="887" height="636" alt="56" src="https://github.com/user-attachments/assets/4c84b90c-b88f-42d6-b60e-63e90bb60ab6" />

> *Dashboard showing KPI cards, regional comparisons, monthly trends, variance analysis, and YoY growth by territory for 2003–2005.*

---

## 📋 Project Overview

This project builds a fully interactive **Multi-Year Sales vs Target Dashboard** in Microsoft Excel using Power Query, the Excel Data Model, DAX-style measures (via PivotTables), Scenario Manager, and dynamic slicers.

The dashboard enables executives and managers to:
- Compare **actual revenue vs sales targets** across years, regions, and product lines
- Identify **underperforming regions and months**
- Run **what-if scenario simulations** (price increases, volume changes)
- Slice and filter data interactively using **Year, Region, Product Category, and Month**

---

## 📁 Dataset

| File | Description |
|------|-------------|
| `sales_data_sample.csv` | Transactional sales data with fields: Order Date, Region, Product Line, Quantity, Price, Revenue |
| `sales_targets.xlsx` | Custom-built targets table with columns: Year, Month, Region, Target Revenue |

---
#### 📊 Charts
- **Actual vs Target by Region** — Clustered column chart (EMEA, NA, APAC, Japan)
- **Actual vs Target by Month (2+ Years)** — Line chart showing monthly trends
- **Variance by Product Category** — Horizontal bar chart, sorted descending
**Recommendation:**  
✅ **Scenario B (10% Volume Increase in NA)** is recommended for the next quarter. NA already shows strong baseline performance, and a volume-driven increase produces a higher revenue uplift and brings the overall % of Target Achieved closer to 100% without impacting price competitiveness in the market.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Excel (2019/365) | Dashboard, PivotTables, Scenario Manager |
| Power Query | Data import and transformation |
| Excel Data Model | Relationships between tables |
| DAX (implicit measures) | KPI calculations |
| Scenario Manager | What-if analysis |
| Excel Slicers & Timelines | Interactivity |

---

## 👥 Team — Data Drifters

| Name |
|------|
| Thato Msina |
| Fikile Noyila |
| Kaylene Martins |
| Jereshan Sinan |
| Lesedi Mphachake |

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git https://github.com/St10245564/Comparing-Actual-Sales-to-Targets-Adding-Interactivity-in-Excel.git
   cd Comparing-Actual-Sales-to-Targets-Adding-Interactivity-in-Excel
   ```

2. **Open the Excel workbook**
   ```
   excel/Sales_Dashboard_Week8.xlsx
   ```

3. **Refresh data connections**
   - In Excel: `Data` → `Refresh All`
   - Ensure the CSV path in Power Query points to `data/sales_data_sample.csv`

4. **Explore the Dashboard**
   - Navigate to the `Dashboard` sheet
   - Use slicers to filter by Year, Region, Product, or Month

---
