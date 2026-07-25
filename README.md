# Food Market Intelligence Dashboard

An interactive Power BI dashboard turning public FAO food market data into policy-relevant insights on food prices, production, trade dependency, and food security.

## About This Project

Built as part of the FAO eLearning Academy Global Youth Contest 2026, this project applies concepts from the FAO course "Strengthening Wholesale Markets in Low- and Middle-Income Countries" — particularly the importance of market information systems — to a real, working data tool. As a computer science student from Uzbekistan with an interest in AI and data analytics, I wanted to explore how technology can make food system data more accessible and useful for decision-making.

## Dashboard Preview

![Food Price Trend Dashboard](docs/Page%201%20-%20Food%20Prices%20and%20Inflation%2C%20screenshot.jpg)

*Food price trends (2015–2025) and current inflation ranking across 9 countries.*

## Questions This Dashboard Answers

- Which countries have rising food prices, and how fast?
- Which countries currently have the highest food price inflation?
- Which countries produce the most staple crops, and which depend heavily on imports? *(Page 2, in progress)*
- Which countries are improving or worsening on food security? *(Page 3, in progress)*

## Countries Covered

Brazil, Egypt, India, Italy, Kenya, Nigeria, United States, Uzbekistan, Vietnam

Selected for regional diversity — spanning South America, North Africa, South Asia, Western Europe, East Africa, West Africa, North America, Central Asia, and Southeast Asia — while keeping the dataset focused enough to build clear, readable visuals.

## Data Sources

- [FAOSTAT Consumer Price Indices](https://www.fao.org/faostat/en/#data/CP) — Food CPI and food price inflation, monthly, 2015–2025

*(Production, Trade Matrix, and Food Security indicator sources will be added as Pages 2 and 3 are built.)*

## Tech Used

- Power BI Desktop
- Power Query (M language) for data cleaning
- FAOSTAT filtered CSV exports

## Repository Structure

├── FAO Food Market Insights.pbix

├── data/
│ 
   └── faostat_food_cpi_2015-2025.csv

├── docs/
│ 
   └── Page 1 - Food Prices and Inflation, screenshot.jpg

└── README.md


## Project Status

- ✅ Page 1 — Food Price Trends & Inflation (complete)
- 🔲 Page 2 — Production & Trade Dependency (in progress)
- 🔲 Page 3 — Food Security & Resilience (in progress)

## How to View

The `.pbix` file requires [Power BI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494) (free) to open and interact with. If you don't have it installed, see the screenshot above for a preview of Page 1.

## Author

Built by Mohigul for the FAO eLearning Academy Global Youth Contest 2026.

## Author

Built by Mohigul for the FAO eLearning Academy Global Youth Contest 2026.
