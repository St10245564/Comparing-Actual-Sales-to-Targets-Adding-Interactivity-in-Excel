# 📊 Multi-Year Sales vs Target Dashboard with Scenario & Segment Analysis

> **Week 8 Group Project** — Comparing Actual Sales to Targets & Adding Interactivity in Excel  
> **Course Module:** Business Intelligence & Data Analytics  
> **Team:** Data Drifters

---

## 📸 Dashboard Preview

![Multi-Year Sales vs Target Dashboard](./assets/dashboard_preview.png)

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

#### 🎛️ Slicers
- **Year** (2003, 2004, 2005)
- **Region** (APAC, EMEA, Japan, NA)
- **Product Category** (Classic Cars, Motorcycles, Planes, Ships, Trains, Trucks & Buses, Vintage Cars)
- **Month** (Timeline slicer)

#### 📝 Insight Text Box
> **Which regions are consistently below target?**  
> APAC, Japan, and NA.
>
> **Which months show strong recovery or decline?**  
> - Jan 2003–Aug 2000: Strong decline until recovery in September  
> - March 2004–July 2004: Strong decline  
> - April 2005: Showed strong decline

---

### Q4 — What-If & Scenario Analysis

Two scenarios simulated using **Excel Scenario Manager**:

| Scenario | Region | Change | Impact on Revenue | Impact on % Target |
|----------|--------|--------|-------------------|-------------------|
| **Scenario A** | EMEA | +5% Price Increase | +R142,000 approx. | +1.4% |
| **Scenario B** | NA | +10% Volume Increase | +R290,000 approx. | +2.8% |

**Recommendation:**  
✅ **Scenario B (10% Volume Increase in NA)** is recommended for the next quarter. NA already shows strong baseline performance, and a volume-driven increase produces a higher revenue uplift and brings the overall % of Target Achieved closer to 100% without impacting price competitiveness in the market.

---

### Q5 — Documentation

A **1-page User Guide** (`docs/User_Guide.pdf`) is included, with screenshots explaining how a manager can:

1. **Refresh the data** — Go to `Data > Refresh All` after updating the CSV source file
2. **Update the Targets table** — Open `data/sales_targets.xlsx`, edit values, save, then refresh
3. **Use slicers** — Click Year, Region, or Product buttons to filter; use the Timeline to filter by month

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
   git clone https://github.com/your-org/week8-sales-dashboard.git
   cd week8-sales-dashboard
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
