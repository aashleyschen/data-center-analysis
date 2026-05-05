# data-center-analysis
CSDS234 Final Project


## Project: Data Centers & Local Quality of Life

The primary angle is **residential utility cost changes** before and after a major data center opens in a region, but the project can be strengthened by considering other measurable dimensions of resident impact:

| Metric | Why It Matters | Potential Data Source |
|---|---|---|
| Electric & gas utility rates | Core focus — large loads can shift rate structures | EIA.gov, state PUC filings |
| Municipal water costs | Data centers use millions of gallons/day for cooling | City utility billing records, EPA |
| Property values near sites | Industrial blight vs. tax-base boost | Zillow, county assessor records |
| Housing affordability | Tech workforce migration inflates local rents/home prices | Census, HUD, Zillow rent index |
| Property tax abatements | Many DCs negotiate decade-long tax breaks, shifting burden to residents | Local government meeting minutes, investigative reporting |
| Grid reliability (outages) | Large baseload consumers can strain local distribution | EIA-861, state PUC complaints |
| Air quality | Diesel backup generators test regularly and emit NOx/PM2.5 | EPA AQS, local air district data |
| Noise pollution | 24/7 HVAC and cooling tower noise near residential areas | Local zoning complaints, noise ordinance records |
| Traffic & road wear | Heavy construction and logistics traffic damages local roads | DOT traffic counts, local maintenance budgets |

---

## Case Study Regions

These four regions were selected because they are among the **highest-concentration data center markets in the US** ([JLL North America Data Center Report, 2025](https://www.jll.com/en-us/insights/market-dynamics/north-america-data-centers); [CommercialCafe, 2024](https://www.commercialcafe.com/blog/americas-data-center-boom/)) and each offers a distinct, well-documented case of residential utility impact — together they span four geographic/regulatory contexts:

- **Northern Virginia** is the [#1 data center market in the world](https://www.datacentermap.com/content/nova/), with 70% of global internet traffic routed through Loudoun County's "Data Center Alley" and nearly 5,000 MW of capacity — more than double Beijing, the next closest market ([E2 Optics](https://www.e2optics.com/northern-virginia-continues-to-be-the-1-data-center-market-in-the-world/); [Loudoun County official data center page](https://www.loudoun.gov/6188/Data-Centers-in-Loudoun-County)).
- **Phoenix / Maricopa Co.** reclaimed the #2 US spot in 2024 with ~2.4 GW deployed and a projected 12.8% CAGR to 2030 ([Mordor Intelligence](https://www.mordorintelligence.com/industry-reports/phoenix-data-center-market)), and is the clearest US case study for water scarcity impact — data center water use in Arizona is projected to reach 7 billion gallons/year by 2035 ([Circle of Blue](https://www.circleofblue.org/2025/supply/data-centers-a-small-but-growing-factor-in-arizonas-water-budget/)).
- **Columbus / Central Ohio** represents the most dramatic rise: [JLL reported Columbus jumped from 25th to the top 10](https://www.five9sdigital.com/knowledge/columbus-oh-among-nations-top-10-data-center-regions/) by adding 6.1 million sq ft. It is the clearest regulatory-response case — PUCO created a [data-center-specific tariff](https://www.aepohio.com/company/about/rates/data-center-tariff/) after documented cost-shifting to residents ([NBC4 Columbus](https://www.nbc4i.com/news/local-news/columbus/how-data-centers-contribute-to-spiking-electric-costs-in-central-ohio/)).
- **Portland / Hillsboro, OR** is the 7th largest US market ([Cushman & Wakefield H2 2025](https://www.cushmanwakefield.com/en/insights/americas-data-center-update)) and provides a West Coast contrast: Intel and Meta DCs concentrated in Hillsboro drove Portland-area residential rates up ~50% over 2022–2025, with documented evidence of utilities under-charging industrial customers vs. residents.

| Region | Utility | Key Angle | Best Data Source |
|---|---|---|---|
| Northern Virginia (Loudoun Co.) | Dominion Energy (SCC) | Clearest utility rate paper trail; SCC approved $565.7M rate increase in Jan 2026 adding ~$11/mo to residential bills; simultaneously, Loudoun Co. property tax rate dropped 40% since 2016 because data centers fund ~45% of county revenue | [Virginia SCC dockets](https://scc.virginia.gov/case-information) — search DEV Biennial Review 2023/2025 |
| Phoenix / Maricopa Co., AZ | APS + SRP | APS testified data centers caused 94% of all load growth 2023–2025; cumulative 23.6% residential rate increase since 2021; water use projected to surge 9x (385M → 3.7B gal/yr) in a region already facing a 4.86M acre-foot groundwater deficit | [Arizona ACC dockets](https://azcc.gov) — APS rate case filings |
| Columbus / Central Ohio | AEP Ohio (PUCO) | PUCO ordered a data-center-specific tariff in July 2025; $2.5B in state/local tax incentives claimed 2017–2024; AEP load grew from ~100 MW (2020) to 600 MW (2024); provides "regulator fights back" policy contrast | [PUCO DIS](https://dis.puc.state.oh.us) — AEP Ohio distribution rate cases |
| Hillsboro / Portland Metro, OR | Portland General Electric | Residential rates up ~50% over 2022–2025; data centers pay less than half per-kWh vs. residents; Oregon passed a cost-allocation law but utilities accused of skirting it as of Dec 2025 | [Oregon PUC eDockets](https://apps.puc.state.or.us/edockets) — PGE dockets UE 394, UE 435, UE 436 |

---

## Todo List

### Research & Data Collection
- [x] Define scope — pick 2–4 case study regions where major data centers operate (e.g., Northern Virginia, Phoenix AZ, Columbus OH)
- [x] Gather utility rate data (before/after data center arrival) from public utility commission records or EIA.gov — see `notebooks/01_data_collection.ipynb`
- [ ] Research water usage impact (data centers use significant cooling water, which affects municipal water costs)
- [ ] Find peer-reviewed sources or news investigations on utility cost shifts for local residents
- [ ] Collect data center energy consumption statistics (MW draw, % of local grid load)

### Analysis
- [ ] Compare pre/post utility rates in case study regions
- [ ] Identify correlations between data center density and residential rate increases
- [ ] Note counterarguments — tax revenue, grid investment, jobs — for a balanced report
- [ ] Summarize findings into 3–5 key claims supported by data

### Report Writing
- [ ] Outline report sections (intro, background, methodology, findings, discussion, conclusion)
- [ ] Draft each section
- [ ] Add citations, figures/charts, and data tables
- [ ] Proofread and finalize formatting

### Presentation
- [ ] Create slide deck (intro, problem, data, findings, conclusion — ~10 slides)
- [ ] Add visuals: graphs, maps, data callouts
- [ ] Practice and time the presentation

---
