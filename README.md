# 🔩 Steel Price History Analysis

**Tools:** Power BI, Excel, Claude AI (Anthropic)  
**Data Source:** SteelBenchmarker™ (Report #483)  
**Period:** October 2024 – May 2026 (Biweekly)  
**Year:** 2026

## Project Overview
A 4-page Power BI dashboard tracking biweekly steel prices across four global 
markets — USA, China, Western Europe, and World Export — covering three finished 
steel products and three scrap categories. Data was extracted from a published 
SteelBenchmarker report and structured into a clean CSV dataset using Claude AI 
for analysis and visualization.

## Dataset
`steel_price_history.csv` — 481 rows of biweekly price observations

| Column | Description |
|--------|-------------|
| Date | Biweekly observation date |
| Region | USA, China, Western Europe, World Export |
| Product | Hot-Rolled Band, Cold-Rolled Coil, Standard Plate, Steel Scrap variants |
| Currency | USD |
| Unit | Metric Tonne (finished steel) / Gross Ton (scrap) |
| Price | Price in USD |
| Dollar_Change | Change from prior observation |
| Pct_Change | Percentage change from prior observation |

## Dashboard Pages

**Page 1 — Current Price Snapshot (May 2026)**
- USA Cold-Rolled Coil: $1,400/MT
- USA Standard Plate: $1,370/MT
- USA Hot-Rolled Band: $1,169/MT
- USA vs. China spread: $735/MT — reflecting Section 232 tariff impact
- Hot-Rolled Band USA up 53% from October 2024 baseline

**Page 2 — USA Steel Price Trends (Oct 2024 – May 2026)**
- Price trend lines for all three finished steel products
- Section 232 tariff increase annotated on the timeline
- Cold-Rolled Coil consistently the highest-priced product

**Page 3 — Hot-Rolled Band: USA vs. Global Markets**
- Side-by-side comparison: USA ($1,169), Western Europe ($800), 
World Export ($515), China ($434)
- Visual representation of tariff-driven price gap between USA and global markets

**Page 4 — USA Steel Scrap Prices: The Leading Indicator**
- Tracks Busheling ($455/GT), Shredded ($430/GT), and Heavy Melting ($370/GT)
- Scrap prices typically lead finished steel prices by 4–6 weeks
- While USA finished steel nearly doubled Oct 2024–May 2026, scrap remained 
relatively stable — indicating higher mill margins rather than raw material cost increases

## Key Findings
- USA Hot-Rolled Band increased 53% between October 2024 and May 2026, 
driven largely by the Section 232 tariff increase to 50% in June 2025
- The USA vs. China price spread reached $735/MT — a direct measure of 
tariff impact on domestic steel consumers
- Scrap price stability during the same period confirms mill margin expansion 
rather than input cost inflation as the primary driver of finished steel price increases
- Cold-Rolled Coil reached $1,400/MT in May 2026, the highest of the 
three tracked products

## Skills Demonstrated
- AI-assisted data extraction from published industry reports
- Time series price tracking and trend visualization in Power BI
- Cross-market comparative analysis (USA, China, Western Europe, World Export)
- Annotated event-driven analysis (tariff impact on price timelines)
- Leading indicator identification (scrap as predictor of finished steel prices)

## Files in This Repository
- `steel_price_history.csv` — Structured biweekly price dataset (481 rows)
- `Steel_Price_History_Dashboard.pdf` — Full dashboard export
- `Steel_Price_History_Source.pdf` — Original SteelBenchmarker source report
