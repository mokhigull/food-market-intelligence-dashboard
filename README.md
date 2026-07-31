# Food Market Intelligence Dashboard

An interactive Power BI dashboard turning public FAO food market data into policy-relevant insights on food prices, production, trade dependency, and food security.

## About This Project

Built as part of the FAO eLearning Academy Global Youth Contest 2026, this project applies concepts from the FAO course "Strengthening Wholesale Markets in Low- and Middle-Income Countries" to a real, working data tool. The course outlines four levers for strengthening wholesale markets — infrastructure, market information systems, governance, and finance/capacity building. This dashboard focuses on making the *outcomes* those levers are meant to influence (price stability, trade dependency, food security) visible and comparable across countries, as a starting point for identifying where intervention matters most.

As an Economics with Data Science student from Uzbekistan with an interest in AI and data analytics, I wanted to explore how technology can make food system data more accessible for decision-making.

## Dashboard Pages & Course Connection

**Page 1 — Food Price Trends & Inflation**
![Page 1](docs/page1_food_prices.png)
Tracks food CPI (2015–2025) and current inflation ranking across 9 countries. Connects to the course's *market information systems* lever: countries with the most volatile price swings are where reliable price and demand signals matter most for helping farmers and traders adapt to shocks.

**Page 2 — Wheat Production & Trade**
![Page 2](docs/page2_wheat_trade.png)
Compares production and import dependency for a staple crop. Connects to the *infrastructure* lever: high import-dependent countries carry the most exposure to global supply shocks, and post-harvest infrastructure (storage, logistics) is the lever for absorbing that volatility rather than passing it to consumers.

**Page 3 — Food Security Outcomes**
![Page 3](docs/page3_food_security.png)
Tracks undernourishment, child stunting, and cereal import dependency together. Connects to the course's point that levers must work in combination — countries with both high import dependency and rising undernourishment need coordinated infrastructure, governance, and finance interventions, not a single fix in isolation.

## Countries Covered

Brazil, Egypt, India, Italy, Kenya, Nigeria, United States, Uzbekistan, Vietnam

Selected for regional and income diversity — spanning net food exporters and import-dependent economies across South America, North Africa, South Asia, Western Europe, East Africa, West Africa, North America, Central Asia, and Southeast Asia.

## Data Sources

- [FAOSTAT Consumer Price Indices](https://www.fao.org/faostat/en/#data/CP) — Food CPI and inflation, 2015–2025
  → `data/faostat_food_cpi_2015-2025.csv`
- [FAOSTAT Trade & Production (TCL)](https://www.fao.org/faostat/en/#data/TCL) — Wheat production and trade
  → `data/WheatProduction_Clean.csv`, `data/WheatTrade_Clean_Long.csv`
- [FAOSTAT Food Security (FS)](https://www.fao.org/faostat/en/#data/FS) — Undernourishment, stunting, cereal import dependency
  → `data/undernourishment_clean.csv`, `data/stunted_children_clean.csv`, `data/cereal_import_dependency_clean.csv`

## Tech Used

- Power BI Desktop
- Power Query (M language) for data cleaning
- FAOSTAT filtered CSV exports

## Repository Structure

├── FAO Food Market Insights.pbix
├── data/
│   ├── faostat_food_cpi_2015-2025.csv
│   ├── WheatProduction_Clean.csv
│   ├── WheatTrade_Clean_Long.csv
│   ├── undernourishment_clean.csv
│   ├── stunted_children_clean.csv
│   └── cereal_import_dependency_clean.csv
├── docs/
│   ├── page1_food_prices.png
│   ├── page2_wheat_trade.png
│   └── page3_food_security.png
└── README.md

## Project Status

- ✅ Page 1 — Food Price Trends & Inflation
- ✅ Page 2 — Wheat Production & Trade Dependency
- ✅ Page 3 — Food Security Outcomes

## What's Next

With access to market-level data (e.g., producer-to-consumer price spreads, or market information system coverage by country), a future version could analyze wholesale market mechanics more directly, rather than the national-level outcomes shown here.

## How to View

The `.pbix` file requires [Power BI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494) (free) to open and interact with. See the screenshots above for a preview of all three pages.

## Author

Built by Mohigul for the FAO eLearning Academy Global Youth Contest 2026.
