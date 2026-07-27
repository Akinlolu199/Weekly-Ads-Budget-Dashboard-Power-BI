# 📊 Ads Performance Dashboard — Power BI
An end-to-end marketing analytics project that transforms raw, multi-platform advertising data into a clean, interactive Power BI dashboard, enabling data-driven budget allocation, campaign evaluation, and ROI optimisation across TikTok, Instagram, Google, and Facebook.

---

## 🏆 Key Results

| Metric | Value |
|---|---|
| Total Ad Spend | £1.40M |
| Total Revenue Generated | £4.34M |
| Return on Investment (ROI) | 210.69% |
| Return on Ad Spend (ROAS) | 3.11 |
| Total Leads | 424K |
| Total Conversions | 220K |
| Cost Per Acquisition (CPA) | £3.92K |

> **£2.94M net revenue generated from £1.40M in ad spend across 4 platforms and 6 campaigns.**

---

## 🔧 What Was Built

### Data Transformation
- Cleaned and standardised raw ad-platform exports with inconsistent formatting, missing values, and mismatched column names
- Unified data from four platforms (TikTok, Instagram, Google, Facebook) into a single, coherent model
- Applied Power Query (M) transformations: type casting, null handling, column renaming, and date table creation

### Data Modelling
- Built a star schema with a central fact table and supporting dimension tables (Campaign, Platform, Date)
- Established relationships optimised for slicer-driven cross-filtering

### DAX Measures
Custom DAX measures created for:
- **ROI** — `(Total Revenue - Total Spend) / Total Spend * 100`
- **ROAS** — `Total Revenue / Total Spend`
- **CPA** — `Total Spend / Total Conversions`
- **Conversion Rate** — `Total Conversions / Total Leads * 100`
- **Month-over-Month Spend & Revenue trends**
- **Revenue Attribution by Platform and Campaign**


### Dashboard Design
- KPI summary cards for at-a-glance performance (Total Spend, Revenue, ROI, ROAS, Leads, Conversions, CPA)
- Line chart: monthly spend vs revenue trend across all 12 months
- Horizontal bar charts: spend and revenue broken down by platform
- Campaign performance table: per-campaign spend, revenue, and ROI
- ROI bar chart ranked by campaign name
- Slicers for dynamic filtering: Platform, Month, CampaignName, WeekStartDate

---

## 💡 Business Questions This Dashboard Answers

- Which advertising platforms deliver the highest ROI and revenue?
- How does monthly spend compare to monthly revenue across the year?
- Which campaigns are driving the strongest returns — and which need optimisation?
- Where are we overspending relative to performance?
- What is the cost per acquisition and how does it vary by platform?
- How do leads and conversions trend across months and platforms?
- Which platforms should receive increased or reduced budget allocation?
- How do different audience strategies (lookalike, remarketing, influencer push) compare in performance?

---

## 📈 Key Insights

- **TikTok and Instagram** lead in both total spend (£0.36M each) and total revenue (£1.20M and £1.14M respectively)
- **Awareness Blast** (TikTok, 227.11% ROI) and **Product Showcase** (Instagram, 225.52% ROI) were the strongest performing campaigns
- **Holiday Promo** (Facebook) delivered the lowest ROI at 149.68% — a candidate for budget reallocation
- Revenue peaks in **March, June, and December** align with strategic campaign pushes, suggesting seasonal planning opportunities
- **Display Remarketing** (Google) generated the highest spend-to-revenue ratio in absolute terms at £134K spend → £382K revenue

---

## 🛠 Tools & Technologies

| Tool | Usage |
|---|---|
| Power BI Desktop | Dashboard design and publishing |
| DAX | Custom KPI and trend measures |
| Power Query (M) | Data cleaning and transformation |
| CSV / Excel | Raw data source |
| Data modelling | Star schema with dimension/fact tables |

---

## 📄 Licence

This project is for portfolio and educational purposes. Data has been anonymised and does not represent any real organisation.

---

## 🙋 Author

**Akinlolu Oyetakin**  
Data and Business Intelligence Analyst  

---

*Built with Power BI · DAX · Power Query*
