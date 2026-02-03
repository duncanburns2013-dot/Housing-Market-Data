# 🏠 New Hampshire Housing Market Dashboard

Interactive dashboard tracking residential real estate trends across 5 New Hampshire markets.

## 🚀 [Launch Live Dashboard](https://duncanburns2013-dot.github.io/Housing-Market-Data/nh-housing-market-dashboard.html)

---

## 📊 Key Market Statistics (2021–2026 Aggregate)

| Market | Avg Sale Price | Median Sale | Homes Sold | Avg DOM | SP/LP Ratio | Sell-Through |
|--------|---------------|-------------|------------|---------|-------------|--------------|
| **NH Statewide** | $530,781 | $438,000 | 102,567 | 29 days | 100.24% | 85.56% |
| **Portsmouth** | $994,254 | $765,359 | 790 | 24 days | 99.38% | 80.20% |
| **Salem** | $612,200 | $555,000 | 1,361 | 17 days | 101.62% | 90.67% |
| **Derry** | $518,587 | $491,000 | 1,371 | 16 days | 102.69% | 90.44% |
| **Windham** | $860,186 | $760,000 | 957 | 23 days | 101.37% | 89.61% |

---

## 🔥 Market Highlights

### Hottest Market: Derry
- **102.69% SP/LP ratio** — buyers paying 2.7% above asking
- **16 days on market** — fastest in NH
- **90.44% sell-through** — 9 in 10 listings sell

### Premium Market: Windham
- **$860,186 average sale price** — highest among I-93 corridor towns
- **101.37% SP/LP ratio** — still a seller's market
- **$760K median** — effectively matching Portsmouth's seacoast premium

### ❌ Affordability Gap: Portsmouth
- Income needed for median home ($765K): **$197,400**
- NH Median Household Income: **$111,800**
- **Shortfall: $85,600 (43% short)**

### 🚗 I-93 Corridor (Southern NH)
Salem, Derry, and Windham — the three I-93 corridor towns most accessible to Boston commuters — show the strongest seller's market indicators across all of NH. All three have SP/LP ratios above 101% and sell-through rates near 90%.

---

## 📂 Dashboard Tabs

| Tab | What's Inside |
|-----|---------------|
| **Overview** | Market comparison table, key stats at a glance |
| **Prices** | Average and median sale prices, bedroom price breakdowns |
| **Price Distribution** | Histograms showing where buyers land in each market |
| **Market Health** | DOM, SP/LP ratio, sell-through rate, active listings |
| **Affordability** | Income needed calculations, monthly payment breakdowns |
| **Southern NH** | Salem / Derry / Windham I-93 corridor deep dive |

---

## 📁 Files

| File | Description |
|------|-------------|
| `nh-housing-market-dashboard.html` | Interactive NH dashboard (single HTML file) |
| `nh_chart1_median_price.png` | Median sale price comparison |
| `nh_chart2_avg_price.png` | Average sale price by market |
| `nh_chart3_dom.png` | Days on market ranking |
| `nh_chart4_splp.png` | Sale/list price ratios |
| `nh_chart5_affordability.png` | Income needed vs NH median |
| `nh_chart6_bedrooms.png` | Price by bedroom count |
| `nh_chart7_summary.png` | 4-panel summary dashboard |
| `nh_chart8_southern.png` | Salem vs Derry comparison |

---

## 🏗️ Technical Notes

- Built with Chart.js 4.4.1
- Inter font (Google Fonts)
- Single self-contained HTML file — no build tools needed
- Responsive design — works on desktop and mobile
- PNG charts: 150 DPI, light theme

## Data Source

PrimeMLS · Paragon MLS Reports · Single-family homes · January 2021 – February 2026

## Affordability Assumptions

- 6.75% mortgage rate, 30-year fixed
- 20% down payment
- 2.09% NH property tax rate
- $2,400/year insurance
- 30% debt-to-income ratio
- NH median household income: $111,800 (2024 FRED data)

Last updated: **February 3, 2026**

---

*Data provided for informational purposes only. Verify all figures with PrimeMLS for transactions.*
