# Basics & Fashion — Overstock Analysis

**Case Study 01 · Retail Analytics**
Live at: `shefreenkaur.github.io/basics-and-fashion/basics-and-fashion.html`

---

## What this is

A self-initiated retail analytics case study framed as an area-level data analyst identifying an overstock problem across multiple stores during the September to November pre-holiday window, across two consecutive years (2024 and 2025).

## Files

| File | Description |
|------|-------------|
| `basics-and-fashion.html` | Main case study page — hero, charts, findings |
| `behind-the-analysis.html` | Working file — data model, SQL pipeline, analytical decisions |

## Stack

- **BigQuery + SQL** — three-table data model, six queries, final `overstock_analysis` table
- **Chart.js** — sell-through rate, volume comparison, net stock movement
- **HTML / CSS / JS** — no frameworks, no dependencies beyond Chart.js and Google Fonts

## Key finding

Womenswear Fashion averaged 29% sell-through across all six data points (Sep, Oct, Nov in both years), against a 70% healthy threshold. The same pattern repeating in consecutive years without correction points to a structural buying and forecasting problem, not a seasonal anomaly.

## To deploy

Drop both HTML files into a subfolder of your GitHub Pages repository and push. No build step required.

```
shefreenkaur.github.io/
  basics-and-fashion/
    basics-and-fashion.html
    behind-the-analysis.html
    README.md
```
