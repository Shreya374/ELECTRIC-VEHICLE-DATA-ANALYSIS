# ⚡ Electric Vehicle Data Analysis

> An interactive Power BI project analyzing global EV sales trends, battery performance, and market share across regions and manufacturers.

---

## 📌 Overview

This project performs an end-to-end analysis of the global Electric Vehicle (EV) market using Power BI. It uncovers key insights across three major dimensions:

- **Sales Trends** — Year-over-year growth of BEV and PHEV segments globally
- **Battery & Range Analysis** — How battery costs and driving range have evolved over time
- **Market Share** — Breakdown by country, region, and top EV manufacturers

---

## 📊 Dashboard Highlights

| Section | Key Insight |
|---|---|
| Global EV Sales | 17.1M units sold in 2024, up 25% YoY |
| Market Share | China leads at 59%, followed by Europe (25%) |
| Adoption Rate | Norway tops at 92% EV penetration |
| Battery Cost | Dropped from $668/kWh (2013) to $115/kWh (2024) |
| Top Brand | BYD overtook Tesla in global EV sales volume |

---

## 🗂️ Project Structure

```
electric-vehicle-data-analysis/
│
├── data/
│   ├── ev_sales_global.csv        # Global EV sales data (2019–2024)
│   ├── battery_cost_trend.csv     # Battery pack cost by year
│   └── market_share_by_region.csv # Regional and manufacturer share
│
├── dashboards/
│   └── EV_Analysis.pbix           # Power BI dashboard file
│
├── visuals/
│   └── screenshots/               # Dashboard screenshots
│
└── README.md
```

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Data modeling, DAX measures, interactive dashboards
- **Microsoft Excel / CSV** — Raw data preprocessing
- **DAX** — Custom KPIs and calculated columns

---

## 📈 Key Analyses

### 1. EV Sales Trend (2019–2024)
Stacked bar chart showing BEV vs PHEV growth over six years, highlighting the acceleration post-2021.

### 2. Regional Market Share
Donut chart breaking down global EV sales share by region — China, Europe, USA, and Rest of World.

### 3. Country-Level Adoption Rate
Horizontal bar chart ranking countries by EV market share percentage, with Norway at 92%.

### 4. Battery Cost Decline
Line chart showing the dramatic 83% reduction in battery pack costs over the last decade.

### 5. Manufacturer Sales Share
Horizontal bar chart comparing top 10 EV brands by global sales share in 2024.

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/electric-vehicle-data-analysis.git
   ```
2. Open `dashboards/EV_Analysis.pbix` in **Power BI Desktop**.
3. If prompted, refresh the data source paths to point to the `/data` folder.
4. Explore the interactive report pages.

---

## 📁 Data Sources

- [IEA Global EV Outlook 2024](https://www.iea.org/reports/global-ev-outlook-2024)
- [BloombergNEF EV Market Data](https://about.bnef.com/)
- [EV Volumes](https://www.ev-volumes.com/)

> *Note: Some figures are estimates based on publicly available reports.*

---

## 🎯 Insights & Conclusions

- The global EV market is growing rapidly, driven largely by China's dominance and aggressive OEM investment.
- Battery cost reductions are the single biggest driver of EV affordability — costs have fallen 83% in a decade.
- Scandinavian countries demonstrate that near-full EV adoption is achievable with the right policy environment.
- BYD's rise signals a major shift in the competitive landscape, with Chinese brands now leading globally.

---

## 👩‍💻 Author

**Shreya**
B.Tech Computer Science Engineering | Data Science & Analytics
📍 Mumbai, India
🔗 [LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
