# SW Chicagoland Real Estate Analytics Dashboard

## Overview
This project analyzes residential real estate market conditions across 7 southwest Chicagoland suburbs to identify pricing trends, property tax differences, and market competitiveness between Cook and Will County communities.

**Suburbs analyzed:** Orland Park · Tinley Park · Homer Glen · Palos Hills · Oak Forest · Mokena · Frankfort

---

## Dashboard Preview
![SW Chicagoland Real Estate Dashboard](dashboard.png)

---

## Key Findings
- Median home prices range from **$246K (Palos Hills)** to **$550K (Frankfort/Mokena)** — a $304K spread across suburbs just 20 miles apart
- Will County suburbs (Frankfort, Homer Glen, Mokena) carry significantly lower property tax rates (~1.8–2.0%) vs Cook County suburbs (~2.4–2.7%)
- Homer Glen showed the strongest YoY appreciation at **+6.7%** in 2025
- Cook County suburbs (Oak Forest, Palos Hills, Tinley Park) showed price softening in 2025–2026
- Average days on market increased across all suburbs compared to the 2022 peak, signaling a market shift toward more balanced conditions
- Frankfort offers the lowest tax rate (1.78%) despite being the highest priced suburb

---

## Metrics Analyzed
- Median sale price (Redfin MLS)
- Zillow Home Value Index (ZHVI)
- Property tax rate by county
- Days on market
- Year-over-year price change
- Monthly rent estimates (1BR, 2BR, 3BR)
- Rent-to-price ratio
- 5-year price trend (2021–2026)

---

## Tools Used
| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard design, data visualization |
| Power Query | Data transformation, unpivoting price trends |
| Microsoft Excel | Data modeling, 3-sheet workbook |
| SQL | Data querying and preparation |

---

## Data Sources
| Source | Metric | Date Range |
|---|---|---|
| Redfin MLS | Median sale price, days on market, YoY change | Q4 2025 – Q1 2026 |
| Zillow ZHVI | Home value index | Q1 2026 |
| Movoto | Cross-reference pricing data | 2025–2026 |
| Cook County Assessor | Property tax rate estimates | 2024–2025 |
| Will County Assessor | Property tax rate estimates | 2024–2025 |
| Zillow Rent Index / Apartments.com | Monthly rent estimates | 2025 |

---

## Files in This Repository
| File | Description |
|---|---|
| `SW_Chicagoland_RealEstate.xlsx` | Excel workbook with 4 sheets: Suburb Data, Price Trends, Rent Estimates, Data Sources |
| `dashboard.png` | Final Power BI dashboard screenshot |
| `SW_Chicagoland_RealEstate_Dashboard.pbix` | Power BI report file |

---

## About
Built by **Nour Tawil** · B.S. Data Analytics, Southern New Hampshire University  
Focused on SW Chicagoland real estate as a locally relevant, data-rich
topic for portfolio development.  
Connect with me on [LinkedIn](www.linkedin.com/in/nour-tawil01)
