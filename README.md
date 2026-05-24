#Nandini G A
Dashboard
# 🛒 Retail Store Analytics Dashboard

An interactive, single-file analytics dashboard built from the **Walmart Retail Dataset** (45 stores, 8,190 weekly records, Feb 2010 – Jul 2013). It visualises store performance KPIs, macroeconomic trends, markdown campaign coverage, and seasonal patterns — all without a backend or build step.

---

## 📸 Preview

> *(Add a screenshot here — drag your dashboard image into this section on GitHub)*

---

## 📊 What's Inside

| Section | Description |
|---|---|
| **KPI Row** | Revenue, transactions, avg basket size, and active stores at a glance |
| **Store-type breakdown** | Performance split across Type A, B, and C stores |
| **CPI vs Unemployment** | Dual-axis quarterly trend (2010–2013) showing macro recovery |
| **Markdown campaign coverage** | Bar chart of MD1–MD5 deployment across 8,190 store-weeks |
| **Fuel price by store type** | Avg $/gallon and year-over-year unemployment trend |
| **Seasonal patterns** | Temperature & fuel price cycles (bi-monthly sample) |

Each chart comes with a **📌 Finding** panel that interprets the data in plain language.

---

## 🧰 Tech Stack

- **Vanilla HTML/CSS/JS** — zero frameworks, zero dependencies to install
- **[Chart.js 4.4.1](https://www.chartjs.org/)** — line and bar charts via CDN
- **[DM Sans + DM Serif Display](https://fonts.google.com/)** — Google Fonts
- **CSS custom properties** — full light/dark mode support via `prefers-color-scheme`

---

## 🗂️ Dataset

| File | Records | Coverage |
|---|---|---|
| `features.csv` | 8,190 rows | Store-week level: CPI, fuel price, temperature, markdowns, unemployment |
| `stores.csv` | 45 rows | Store type (A/B/C) and size |

**Time range:** February 2010 – July 2013  
**Source:** [Walmart Store Sales Forecasting — Kaggle](https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting)

---

## 🚀 Getting Started

No install needed. Just open the file:

````bash
# Clone the repo
git clone https://github.com/your-username/your-repo-name.git

# Open the dashboard
open retail_dashboard.html
````

Or simply double-click `retail_dashboard.html` in your file explorer.

---

## 💡 Key Findings

- **Type A stores** generate the highest revenue but show greater volatility tied to seasonal and economic shifts.
- **CPI rose 6%** (167.9 → 178.0) while unemployment fell 1.9 pp over the analysis window — consistent with a post-recession consumer recovery.
- **MD1 and MD5** are the most deployed markdown campaigns (~49% of store-weeks each), suggesting they are core recurring promotional tools.
- **Fuel prices surged 43%** from $2.69 to $3.85/gallon (2010–2012) before stabilising — a significant cost pressure on both operations and consumer budgets.
- Temperature follows a **predictable seasonal cycle** (36°F winter → 76°F summer), making it a reliable control variable for sales modelling.

---

## 📁 Project Structure

````
├── retail_dashboard.html   # Self-contained dashboard (HTML + CSS + JS)
├── data/
│   ├── features.csv        # Weekly store-level features
│   └── stores.csv          # Store metadata
└── README.md
````

---

## 🙌 Acknowledgements

Dataset sourced from the **Walmart Store Sales Forecasting** competition on Kaggle. Built as a data exploration and visualisation exercise.

---

*Built with Chart.js & vanilla HTML/CSS*