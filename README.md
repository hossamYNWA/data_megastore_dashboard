# 📊 Advanced Sales Intelligence Platform for megastore data

A sophisticated multi-dashboard Power BI analytics solution processing **millions of rows** of sales, marketing, and promotional data. Built collaboratively with advanced DAX measures, field parameters, and role-based security.

---

## 🎯 Quick Overview

| Aspect | Detail |
|--------|--------|
| **Dashboards** | 4 core analysis modules |
| **In-Depth Analysis** | 9 supplementary deep-dive pages |
| **Data Scale** | Millions of rows |
| **DAX Measures** | 70+ complex calculations |
| **Advanced Features** | Field parameters, User roles |
| **Team** | Collaborative build (3 colleagues) |

---

## 📁 Repository Structure

sales-intelligence-platform/  

├── dashboards/  

│ ├── Sales Analysis  

│ ├── Products Analysis  

│ ├── Categories Analysis  

│ └── Promotions Analysis  

│
└── in-depth-analysis/ 

├── Marketing Engagement (YTD, Custom Periods, Time Range)  

├── Target Achievement  

├── Delivery vs Total Sales  

├── Active Promotions Timeline  

├── Geographic Distribution  

└── Order Fulfillment Tracking  

---


---

## 🎯 Core Dashboards

### 1️⃣ Sales Analysis
**Total Sales: $8.34B | Profit: $4.69B | Margin: 57%**

Multi-year performance across product classes (Regular, Deluxe, Economy) and top brands. Geographic heatmap shows global sales distribution. Year-over-year trend analysis identifies seasonal patterns.

**Key Insight**: Brands like Fabrikam dominate with $1.9B revenue, highlighting premium segment strength.

---

### 2️⃣ Products Analysis
**Sales: $8.34B | Profit: $4.69B | Margin: 57%**

Customizable Top/Bottom N product rankings by profitability. Identifies quality issues through return tracking. **Scatter plot reveals critical insight**: Every 1% discount increase reduces profitability by ~$10M—quantifying the discount impact paradox.

**Key Feature**: Dynamic filters for Year, Category, and Analysis Type enable rapid hypothesis testing.

---

### 3️⃣ Categories Analysis
**Hierarchical Intelligence**

Five-level filtering drill-down: Continent → Country → Category → SubCategory → ClassName. Monthly profit trends ($100M–$133M range) reveal category seasonality. Enables cross-regional performance comparisons and bottleneck identification.

**Data Depth**: Millions of transactions aggregated across 5 analytical dimensions.

---

### 4️⃣ Promotions Analysis
**28 Campaigns | $126.7M Total Discount | $5.54B Promo Sales**

Promotions drive **66% of total sales volume**—a substantial channel. Campaign performance varies dramatically (North America Back-to-School: $1.29B vs European Spring: $310M). Redemption rate (65.71%) indicates healthy engagement. Monthly combo chart shows clear seasonal promotion strategy.

**Strategic Finding**: Redemption rate tied to campaign timing; holiday campaigns 2–4x more effective.

---

## 🔍 In-Depth Analysis Pages

### Marketing Engagement (3 flexible views)
- **YTD**: Year-to-date clicks vs. same period last year.
- **Time Range**: Pre-set windows (last 15/30/45 days) auto-calculate prior-year comparison
- **Custom**: User-selected periods for ad-hoc cohort analysis

---

### Target Achievement
Monthly sales (bars) vs. same month last year (line) vs. stated targets (KPI cards). 92.07% overall achievement rate. November variance (-3.3% vs LY) signals competitive pressure or seasonal headwind.

---

### Delivery Channel Analysis
**Multi-channel order tracking**: Compares order volume through delivery channel vs. total orders. Reveals channel distribution shifts and fulfillment pipeline health.

---

### Promotions Timeline
- **Active Promotions/Month**: 2–4 concurrent campaigns—strategic holiday clustering visible
- **Order Fulfillment**: Tracks delivered order count by date, identifying processing delays

---

### Sales by Country
Global bubble map highlights China (59.59% of Asia sales) and regional leaders with drill through option for each country.

---

### Order Fulfillment
Tracks delivered order count by date, user can chose any date and chart will show the delivered orders after that date by 7 days, 15 days, 30 days and 6 months.

---

### Countries share for each continent
Tracks the share of countries sales in each continent to know more about the active markets in each region.

---

## 🛠️ Technical Architecture

**Data Model**: snowflake schema with fact table (Sales) and dimensions (Products, Date, Geography, Promotion, Channel, Stores).

**Advanced DAX**: 70+ measures including YoY comparisons, rolling periods, discount impact calculations, and dynamic KPIs. Field parameters enable metric switching without report modification.

**Security**: User roles implemented for row-level filtering—sales teams see regional data only.

---

## 💡 Key Insights

**Sales Performance**
- Fabrikam, Contoso and Adventure Works Best Selling Brands with more than 50% of total sales
- North America is the best selling continent with 59.15% of total Sales.
- Sales trend declined year over year

**Promotional Effectiveness**
- Promotions account for $5.54B of $8.34B sales (66%)
- North America campaigns 4x more effective than European equivalents
- Promotion-free months see 30%+ sales decline—structural dependency

**Geographic Opportunity**
- Asia under-indexed (59.59% sales from China alone)
- Europe shows balanced multi-country distribution
- Emerging regions (SE Asia, Central Europe) under-penetrated

**CRITICAL ALERT: Sustained Sales Decline**
- 2013 profits show 4.50% decrease vs. 2012. 2013 profits show 15.85%  decrease vs 2011
- Total revenue dropped 18.7% over three years
- Strategy overhaul required to reverse trend

**Premium Products Underperform**
- Deluxe products show 35% higher return rate vs. economy lines
- Premium pricing should equal premium quality
- 62% of all returns originate from deluxe category
- Quality audit required for premium product lines

**✅ OUTSTANDING QUALITY PERFORMANCE**
- Return Rate: 1.61% across all product lines
- Industry Benchmark: Below 3% average
 - Customer Satisfaction: Exceptionally High

---

## 🎓 Skills Demonstrated

✅ **Advanced DAX** – 70+ measures, YoY logic, field parameters  
✅ **Star Schema Design** – Optimized for millions of rows  
✅ **Row-Level Security** – User role implementation  
✅ **Data Visualization** – Geographic mapping, hierarchical drill-down  
✅ **Collaborative Development** – Team-based complex project  
✅ **Business Intelligence** – Actionable insights from massive datasets  
✅ **Performance Optimization** – Aggregation tables, efficient relationships  

---

## 📸 Dashboards Overview

- `sales-analysis.jpg` – Revenue trends, brand performance, margins
- `products-analysis.jpg` – Profitability ranking, discount impact, returns
- `categories-analysis.jpg` – Hierarchical drill-down, category seasonality
- `promotions-analysis.jpg` – Campaign ROI, promotional channel impact
- `marketing-engagement-*.jpg` – YTD, time range, custom period analysis
- `target-achievement.jpg` – Monthly vs. LY with target variance
- `delivery-sales-vs-total-sales.jpg` – Channel composition and growth
- `sales-per-country-map.jpg` – Global geographic distribution
- `active-promotions-per-month.jpg` – Promotional calendar insights

---

## 🚀 Why This Matters

This project demonstrates **enterprise-grade analytics**: handling millions of rows, implementing security controls, and delivering actionable insights to drive channel strategy, promotional investment, and regional expansion decisions. The 70+ DAX measures and field parameters show mastery of complex calculations—not dashboard decoration, but mathematical business logic.

---

## 👥 Collaboration & Build Details

Built in partnership with **3 colleagues** (I was the teamleader). My contribution was the whole design of the project, the marketing engagement pages (from scratch), row level security and made the promotions anaysis dashboard. also helped other colleagues in their tasks.

**Repository organized for clarity**:
- `dashboards/` → 4 core business dashboards
- `in-depth-analysis/` → 9 specialized analysis pages

Intentionally separated core reporting from exploratory analysis—easier for better experience.

---

## 📧 Questions or Interested?

This project showcases what's possible with Power BI at scale. Happy to discuss architecture decisions, DAX approaches, or collaboration workflows.

  
## 📧 Contact & Connect
Feel free to reach out to discuss this project or potential collaborations!  

**LinkedIn**: [MyLinkedIn](https://www.linkedin.com/in/hossam-badawy)  

**Email**: hossam.mousa779@gmail.com  

---

**Last Updated**: November 2025  
**Data Scale**: Millions of rows  
**Skill Level**: Advanced Analysis
