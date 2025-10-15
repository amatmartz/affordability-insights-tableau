# Purchasing Power & Housing Affordability Atlas (1995–Present)

Interactive Tableau project quantifying how **real wages, prices, and housing costs** evolve over time. Explore **price-to-income**, a **mortgage stress tester**, and city/region comparisons with parameterized scenarios.

[![Tableau Public](https://img.shields.io/badge/Tableau_Public-Live_Demo-blue)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

<p align="center">
  <img src="assets/preview.webp" alt="Project preview" width="720">
</p>

## What this demonstrates (Tableau skills)
- **Parameters:** baseline year, mortgage rate, loan term, down payment %
- **LOD expressions:** stable medians by region/city
- **Set Actions:** build custom comparison baskets
- **Table calcs:** MoM/YoY growth, indexed series (base = 100)
- **Custom tooltips:** affordability verdicts (e.g., “30% rule exceeded”)

## Dashboards
1. **Affordability Map** — Choropleth of **price-to-income** with city/country picker  
2. **Real Wages vs Prices** — Dual indexed series with baseline-year parameter  
3. **Mortgage Stress Tester** — Payment vs income with rate/term/down-payment sliders  
4. **City/Region Compare** — Cohort builder (set action), KPI tiles, ranks

**Story:** *The Squeeze* — How 2000–07, 2010–13, and 2020–23 regimes impacted first-time buyers

## Business/Policy implications (examples)
- Wage growth lag vs housing price booms → persistent affordability squeeze  
- Rate shocks can raise monthly burden even when prices stall  
- Local heterogeneity suggests targeted policy and comp strategies

## Repo
