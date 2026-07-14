# Honda Dealership — Sales & Channel Performance Diagnostics

Power BI analytics project built during my Data Analytics internship at Vision Honda India Limited, analyzing dealership sales performance, marketing channel ROI, and vehicle model portfolio strategy.

## Overview

Built a 3-page executive dashboard from a raw invoice-level sales export (1,407 records, FY2022–2025, 12 models, 22 lead sources) with no built-in pricing or cost data. Designed and documented an assumption-based pricing/CAC layer to enable revenue and ROI analysis, then modeled it as a proper star schema in Power BI with DAX-driven time intelligence.

## What's Inside

**Data Model:** Star schema — fact table related to model-pricing and channel-CAC dimension tables, plus a dedicated Date table (DAX `CALENDAR()`) supporting FY/Quarter/Month intelligence.

**Page 1 — Executive Overview:** KPIs, monthly sales trend, model mix, FY × Model heatmap matrix.

**Page 2 — Channel Effectiveness:** Revenue-per-CAC-rupee ranking by lead source, plus a spend-vs-revenue-vs-volume bubble chart identifying which acquisition channels are actually efficient.

**Page 3 — Model Portfolio (BCG Matrix):** Every model plotted by YoY growth vs. volume across the 4 BCG quadrants. Key finding: no model qualifies as a true "Star" — the portfolio is mature, dominated by high-volume/flat-growth Cash Cows.

<img width="1281" height="722" alt="Screenshot 2026-07-14 151404" src="https://github.com/user-attachments/assets/687bdc2f-8036-4135-b555-de8170d98432" /> <img width="1291" height="729" alt="Screenshot 2026-07-14 151422" src="https://github.com/user-attachments/assets/6a8f7bf2-dba8-47e7-a243-da484218000a" />


## Key Insight & Recommendation

No model combines high growth with high volume — the product portfolio is saturated, not expanding. Referral and owned-digital channels significantly outperform traditional advertising on revenue-per-rupee spent. Recommendation: defend share on existing Cash Cow models rather than over-investing in acquisition, and reallocate channel budget toward referral/digital-owned sources.

## Skills Demonstrated

Power BI · DAX (measures, time intelligence, filter context) · Power Query · Data modeling (star schema) · BCG Growth-Share framework · Channel ROI analysis · Strategic recommendation writing

## Note on Data

Pricing and CAC figures are illustrative assumptions, kept in separate editable reference tables. Sales volumes and lead sources reflect actual (anonymized) dealership records. Independent personal project — not an official Honda deliverable.

**Rohit Vinod** — Data Analytics Intern, Honda Cars India Limited
