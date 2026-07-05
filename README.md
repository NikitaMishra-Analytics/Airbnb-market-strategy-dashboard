# 🏠 Airbnb Market Strategy Dashboard

An interactive dashboard built to help **Airbnb Market Strategy Managers** compare markets, spot pricing and demand patterns, and identify guest experience gaps across six global cities.

**🔗 Live Dashboard:** [https://tinyurl.com/45bndt2p](https://tinyurl.com/45bndt2p)

**Author:** Nikita Mishra

---

## 📌 Overview

This project analyzes Airbnb market performance across **Austin, Bangkok, Buenos Aires, Cape Town, Istanbul, and Melbourne**, combining Airbnb listings data with tourism arrival trends. The dashboard was designed around real business questions — comparing cities, spotting pricing/demand patterns, and identifying where guest experience gaps exist — so that market strategy decisions are grounded in data rather than intuition.

## 🎯 How the Dashboard Was Designed

| Audience Need | Business Question | Data Field |
|---|---|---|
| Compare cities | How does market supply vary by city? | Market Supply — Active listings |
| Compare cities | How do prices compare across cities? | Pricing — Average nightly rate |
| Spot pricing & demand patterns | Where is the highest guest activity? | Location Activity — Bookings by location |
| Spot pricing & demand patterns | How does tourist demand change over time? | Tourist Demand — Bookings over time |
| Identify guest experience gaps | Where are guest satisfaction gaps? | Guest Satisfaction — Review score (1–5) |

## 🔑 Key Findings

### Market Supply
- **Istanbul** has the largest Airbnb supply (~30,000 listings), followed closely by **Bangkok**.
- **Entire homes** dominate the listing mix across all six cities.
- **Austin** has the smallest supply (~10,000 listings) of the six markets studied.
- Hotel rooms and shared rooms remain a minor share everywhere — the market is driven by entire homes and private rooms.

### Tourism Demand (2021–2025)
- **Bangkok** shows the strongest rebound: from ~1.5M arrivals in 2021 to over 40M by 2025.
- **Austin** shows steady growth (22M → 31M+).
- **Istanbul** and **Melbourne** show consistent year-over-year recovery.
- **Cape Town** and **Buenos Aires** remain smaller tourism markets by volume.

### Supply vs. Demand (Market Saturation)
- **Buenos Aires** and **Cape Town** show signs of market saturation — high Airbnb listings relative to tourist volume.
- **Austin** and **Bangkok** show the strongest tourist demand relative to supply — suggesting room for growth.

### Pricing
- **Hotel rooms** and **entire homes** generally lead in the higher-price segments, though the top room type varies by city.
- **Private/shared rooms** are consistently more budget-oriented, though some cities show high-price outliers.
- After currency conversion to CAD: **Austin** is the premium market (hotel rooms ~CAD 297, entire homes ~CAD 255); **Melbourne** and **Cape Town** sit mid-range; **Bangkok, Istanbul, and Buenos Aires** are more budget-friendly.

### Location Concentration
- Listings cluster around central urban and tourism areas in every city.
- **Bangkok** and **Buenos Aires** show dense single urban cores; **Austin, Istanbul, and Melbourne** show broader multi-area spread; **Cape Town** shows a strong coastal/tourism-corridor pattern.
- Top neighborhoods: Austin (78704), Bangkok (Vadhana), Buenos Aires (Palermo), Cape Town (Ward 115), Istanbul (Beyoglu), Melbourne (Melbourne CBD).

### Guest Satisfaction
- Overall satisfaction is high across all cities (avg. ratings 4.57–4.84), led by **Austin (4.84)**.
- **Communication** is consistently one of the strongest categories.
- **Value** is the weakest category in Austin, Bangkok, Cape Town, and Melbourne; **cleanliness** is the weakest in Buenos Aires and Istanbul.
- **Value score correlates strongly with overall rating** in every city (r = 0.84–0.92) — the single strongest lever for lifting guest satisfaction.

## 💡 Strategic Takeaways

1. Airbnb supply, demand, and pricing patterns are **uneven across cities** — a single strategy will not fit all markets.
2. **Austin and Bangkok** show the best growth opportunity (high demand relative to supply).
3. **Buenos Aires and Cape Town** show possible market saturation.
4. **Improving perceived value** is the clearest, most consistent way to raise guest satisfaction scores across nearly every market.
5. Guest experience weaknesses are **city-specific** — improvement plans should target each city's particular weak category rather than a blanket fix.

## 🛠️ Dashboard Structure

- **Market Overview** — Listings by city and room type
- **Tourism Demand** — Arrivals trends (2021–2025) and supply-to-demand ratio
- **Pricing Analysis** — Price distribution by room type, and cross-city CAD comparison
- **Location Activity** — Neighborhood-level concentration maps
- **Guest Satisfaction** — Category-level ratings, sentiment, and value-to-rating correlation

## 📊 Data Sources

- Airbnb listings data (city-level, includes price, room type, location, availability, reviews)
- Tourism arrivals data (2021–2025, by city)
- Currency conversion (CAD) for cross-market price comparison

## 📎 Files in This Repository

- `Airbnb_Dashboard.pptx` — Full presentation deck with findings and takeaways
- `README.md` — This file

---

*This dashboard supports ongoing market monitoring and strategic decision-making for Airbnb market expansion, pricing, and guest experience improvement.*
