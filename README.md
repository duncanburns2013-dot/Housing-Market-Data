# Greater Newburyport Housing Market Dashboard

Interactive dashboard tracking residential real estate trends across 12 MLS markets in Massachusetts, with focus on the Greater Newburyport region.

## Markets Covered

**Greater Newburyport (6 towns)**
- Newburyport
- West Newbury
- Newbury
- Rowley
- Salisbury
- Amesbury

**Regional Benchmarks**
- Massachusetts (statewide)
- Essex County
- Middlesex County
- Norfolk County
- Boston
- Cambridge

## Data Points Tracked

| Metric | Description |
|--------|-------------|
| Average Sale Price | Mean sold price for single family homes |
| Price per Sq Ft | $/sqft based on living area |
| Days on Market | Average DOM from list to accepted offer |
| Sales Volume | 12-month rolling transaction count |
| Months Supply | Active inventory ÷ monthly absorption rate |

## Time Period

**2021–2026** (6 years of historical data)

## Data Source

MLS Property Information Network (MLS PIN)

## Files Included

| File | Description |
|------|-------------|
| `housing-market-dashboard.html` | Interactive dashboard (single HTML file) |
| `wn_chart1_sales.png` | West Newbury River Meadow comps |
| `wn_chart2_listvssold.png` | List vs sale price comparison |
| `wn_chart3_dom.png` | Days on market by property |
| `wn_chart4_stats.png` | West Newbury market statistics |
| `wn_chart5_distribution.png` | Price distribution (106 sales) |
| `wn_chart6_table.png` | Comparable sales table with dates |
| `wn_chart7_timeline.png` | Sales timeline 2019–2024 |
| `gnbpt_chart1_prices.png` | Greater Newburyport avg prices |
| `gnbpt_chart2_sqft.png` | Price per sq ft by town |
| `gnbpt_chart3_dom.png` | Days on market by town |
| `gnbpt_chart4_change.png` | Price change since 2022 |
| `gnbpt_chart5_volume.png` | Sales volume by town |
| `gnbpt_chart6_summary.png` | 4-panel summary dashboard |

## Dashboard Features

- **Interactive timeline slider** — scrub through 2021–2026
- **7 tabbed views** — Price, $/SqFt, DOM, Volume, Inventory, Affordability, Greater Newburyport
- **Responsive design** — works on desktop and mobile
- **No dependencies** — single HTML file with embedded Chart.js

## Key Market Insights (2026)

### Massachusetts
- Median Sale: $818,000 (+23% since 2021)
- DOM: 56 days (+87% since 2021)
- Volume: 38,590 units (-26% since 2021)
- Inventory: 1.09 months supply

### Greater Newburyport
| Town | Avg Price | $/SqFt | DOM |
|------|-----------|--------|-----|
| Newburyport | $1,140,000 | $633 | 32 |
| West Newbury | $1,100,000 | $329 | 45 |
| Newbury | $801,000 | $462 | 71 |
| Salisbury | $695,000 | $407 | 38 |
| Rowley | $690,000 | $366 | 28 |
| Amesbury | $687,000 | $339 | 57 |

### West Newbury Detail (106 sales $1M+)
- Median Sale: $1,200,000
- Median $/SqFt: $316
- Median DOM: 39 days
- Median Sq Ft: 3,998

## Usage

1. Open `housing-market-dashboard.html` in any modern browser
2. Use the year slider to view historical data
3. Click tabs to switch between metrics
4. Hover over charts for detailed values

## Technical Notes

- Built with Chart.js 4.4.1
- Inter font (Google Fonts)
- Color palette: Blue (#2563eb), Red (#dc2626), Green (#16a34a), Yellow (#ca8a04)
- PNG charts: 150 DPI, dark theme (#0f172a background)

## Updates

Last updated: February 2026

---

*Data provided for informational purposes only. Verify all figures with MLS PIN for transactions.*
