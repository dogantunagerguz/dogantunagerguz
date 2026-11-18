# Dogan Tuna Gerguz

**Industrial Engineer (Wirtschaftsingenieurwesen) · Business Operations · BI & Data Analytics**

I manage service-business operations, identify business needs and data gaps, and develop analyses that guide daily decisions.

**At a glance:** **3 business lines** · **7 → 2 hours/week** reporting effort · **Microsoft PL-300**<br>
The time reduction is an author-reported result from the wider BI engagement. [Outcome and scope notes](https://github.com/dogantunagerguz/driving-school-targeting-and-finance/blob/main/docs/story.md#operational-delivery-notes).

**Berlin · Authorized to work in Germany · M.A. International Management**<br>
Open to junior, graduate and trainee roles in BI, data, operations and process improvement.

[How I work](docs/working-approach.md) · [Technical evidence](#technical-evidence) · [LinkedIn](https://linkedin.com/in/dogantunagerguz)

## Selected projects

| [Renewal outreach](#renewal-outreach) | [Driving-school targeting & finance](#driving-school-targeting--finance) | [Travel customer analysis](#travel-customer-analysis) |
|:---:|:---:|:---:|
| <a href="https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/blob/main/docs/dashboard.md"><img src="https://raw.githubusercontent.com/dogantunagerguz/psychotechnical-renewal-tracker/main/assets/dashboard.png" width="240" alt="Renewal outreach dashboard preview"></a> | <a href="https://github.com/dogantunagerguz/driving-school-targeting-and-finance/blob/main/docs/dashboard.md"><img src="https://raw.githubusercontent.com/dogantunagerguz/driving-school-targeting-and-finance/main/assets/dashboard.png" width="240" alt="Driving-school targeting dashboard preview"></a> | <a href="https://github.com/dogantunagerguz/travel-agency-customer-segmentation/blob/main/docs/dashboard.md"><img src="https://raw.githubusercontent.com/dogantunagerguz/travel-agency-customer-segmentation/main/assets/dashboard.png" width="240" alt="Travel customer analysis dashboard preview"></a> |
| Who should staff contact next? | Which licence upgrades fit, and what do costs show? | Who returns, and when do they book? |
| [Workflow](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/blob/main/docs/decision-workflow.md) · [Demo](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker#run-the-public-demo) | [Workflow](https://github.com/dogantunagerguz/driving-school-targeting-and-finance/blob/main/docs/decision-workflow.md) · [Demo](https://github.com/dogantunagerguz/driving-school-targeting-and-finance#run-the-public-demo) | [Workflow](https://github.com/dogantunagerguz/travel-agency-customer-segmentation/blob/main/docs/decision-workflow.md) · [Demo](https://github.com/dogantunagerguz/travel-agency-customer-segmentation#run-the-public-demo) |

The operational reports use private company data. Public repositories provide anonymised screenshots, synthetic-data Power BI demos and separate SQL companions.

### Renewal outreach

**My decisions:** Turn renewal-date rules into manageable priority groups and combine interested trainees and external contacts in a source-tagged pool.

**Daily use:** Staff review priorities, record call outcomes and arrange follow-up. The operational model updates on scheduled Power BI Service refresh; recorded outcomes then change the open list. The public Desktop demo refreshes manually.

[Project and code](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker) · [KPI definitions and proposed next steps](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/blob/main/docs/decision-workflow.md#metric-interpretation)

<details>
<summary>View the renewal dashboard</summary>

<a href="https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/blob/main/docs/dashboard.md"><img src="https://raw.githubusercontent.com/dogantunagerguz/psychotechnical-renewal-tracker/main/assets/dashboard.png" width="680" alt="Renewal report with urgency groups and a source-tagged contact pool"></a>

Original report preview with anonymised contact details. Public-demo totals differ; expressions of interest do not establish completed renewals.
</details>

### Driving-school targeting & finance

**My decisions:** Extend a commercial-licence brief to motorcycle and car segments, connect five source types, and add nine expense categories and nominal cost-per-trainee analysis.

**Daily use:** Staff choose a segment using available class capacity, drill through to contact details and review financial records. Excel preparation and report refresh remain manual.

[Project and code](https://github.com/dogantunagerguz/driving-school-targeting-and-finance) · [Reported outreach and metric scope](https://github.com/dogantunagerguz/driving-school-targeting-and-finance/blob/main/docs/story.md#numbers)

<details>
<summary>View the targeting and finance dashboard</summary>

<a href="https://github.com/dogantunagerguz/driving-school-targeting-and-finance/blob/main/docs/dashboard.md"><img src="https://raw.githubusercontent.com/dogantunagerguz/driving-school-targeting-and-finance/main/assets/dashboard.png" width="680" alt="Candidate decomposition tree from licence segment to cohort and age band"></a>

Targeting preview; the linked walkthrough also covers finance. Screenshot selections are separate from reported outreach counts.
</details>

### Travel customer analysis

**My decisions:** Request monthly exports to recover a booking-month proxy, standardise hotel names and correct table grain before joining sources.

**Daily use:** Lifecycle, booking timing and hotel-location views support sales conversations across two branches and approximately 4,500 customer records. Reports refresh manually. Customer identity is name-based, lifecycle windows use 2026, and recommendation conversion has not been measured.

[Project and code](https://github.com/dogantunagerguz/travel-agency-customer-segmentation) · [End-to-end BI pipeline](https://github.com/dogantunagerguz/travel-agency-customer-segmentation/blob/main/docs/end-to-end-bi-pipeline.md) · [Data gaps and modelling decisions](https://github.com/dogantunagerguz/travel-agency-customer-segmentation/blob/main/docs/story.md#what-i-built)

<details>
<summary>View the customer analysis dashboard</summary>

<a href="https://github.com/dogantunagerguz/travel-agency-customer-segmentation/blob/main/docs/dashboard.md"><img src="https://raw.githubusercontent.com/dogantunagerguz/travel-agency-customer-segmentation/main/assets/dashboard.png" width="680" alt="Travel report with booking lead time, customer lifecycle filters, seasonal sales and hotel demand"></a>

Earlier Power BI export; the current model uses the shorter Customers KPI caption. Public figures are anonymised or synthetic.
</details>

## Forecasting case study

### Promotion demand forecasting

**The task:** A retail-analytics take-home case — explain why a chain's promotion forecast missed, test four commercial beliefs, forecast demand for the next promotion week with an 80 % interval, and set order quantities per store.

**My decisions:** Separate sales from demand on days the shelf emptied; learn the promotion lift per store format and category instead of one number for all; backtest the method on twelve past promotions and calibrate from the result; size the order with a newsvendor rule.

**Result:** 19,848 units with an 80 % range of 18,100–21,900; reviewers re-ran the pipeline and got identical outputs. Their written feedback and my planned revisions are in the README.

[Project and code](https://github.com/dogantunagerguz/promotion-demand-forecast) · [Junior Gurobi extension](https://github.com/dogantunagerguz/promotion-demand-forecast/tree/main/optimization) · [Method and findings](https://github.com/dogantunagerguz/promotion-demand-forecast#the-method) · [What I'd do differently](https://github.com/dogantunagerguz/promotion-demand-forecast#what-id-do-differently)

## Public-data analysis

### City of Austin procurement (FY2023)

**The question:** Where does a city's goods spend go? How concentrated are suppliers, when are orders placed, and how much runs through master agreements? 10,699 purchase-order lines worth $326M, analysed in Python with pandas.

**Approach:** Measure spend by line amount, because half of the lines carry an amount but no quantity (45 % of spend); group suppliers by code, not name; test the expected year-end spike against order dates; flag a price comparison the data cannot support.

**Result:** The top 10 of 916 suppliers take 37.4 % of spend. There is no September spike: 23 % of order value lands in October, when annual blanket orders open. 93.2 % of spend runs through master agreements.

[Project and code](https://github.com/dogantunagerguz/austin-procurement-analysis) · [Junior DuckDB and REST extension](https://github.com/dogantunagerguz/austin-procurement-analysis/blob/main/docs/junior-data-stack.md) · [Notebook](https://github.com/dogantunagerguz/austin-procurement-analysis/blob/main/austin_procurement_fy2023.ipynb) · [Limitations](https://github.com/dogantunagerguz/austin-procurement-analysis#limitations)

<details>
<summary>View the monthly spend chart</summary>

<a href="https://github.com/dogantunagerguz/austin-procurement-analysis#2-timing"><img src="https://raw.githubusercontent.com/dogantunagerguz/austin-procurement-analysis/main/images/monthly_spend.png" width="680" alt="Monthly purchase order value, with October far above the monthly average and September the lowest month"></a>

Order dates, not payment dates; one fiscal year only.
</details>

## Technical evidence

Each SQL companion documents sources, table grain, transformation logic, KPI denominators, quality checks and reproducible results. SQL uses synthetic data and is separate from the operational Power BI workflow.

| Companion | Inspectable work | Code and validation |
|---|---|---|
| **Renewal** | Strict date and identity checks; missing-result handling; atomic snapshot replacement with replay and rollback regressions | [SQL](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/tree/main/sql) · [Results](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/blob/main/sql/RESULTS.md) · [Test evidence](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/blob/main/sql/TEST_EVIDENCE.md) |
| **Driving school** | Eligibility rules; finance pre-aggregation; ranking and source reconciliation | [SQL](https://github.com/dogantunagerguz/driving-school-targeting-and-finance/tree/main/sql) · [Results](https://github.com/dogantunagerguz/driving-school-targeting-and-finance/blob/main/sql/RESULTS.md) |
| **Travel** | Raw/staging layers; customer-hotel-date star schema; reservation-grain checks; lifecycle, LAG and DENSE_RANK | [Pipeline](https://github.com/dogantunagerguz/travel-agency-customer-segmentation/blob/main/docs/end-to-end-bi-pipeline.md) · [SQL](https://github.com/dogantunagerguz/travel-agency-customer-segmentation/tree/main/sql) · [Results](https://github.com/dogantunagerguz/travel-agency-customer-segmentation/blob/main/sql/RESULTS.md) |

**Automated Python/SQL checks:**<br>
Renewal [![Renewal tests](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/actions/workflows/ci.yml) ·
Driving school [![Driving-school tests](https://github.com/dogantunagerguz/driving-school-targeting-and-finance/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/dogantunagerguz/driving-school-targeting-and-finance/actions/workflows/ci.yml) ·
Travel [![Travel tests](https://github.com/dogantunagerguz/travel-agency-customer-segmentation/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/dogantunagerguz/travel-agency-customer-segmentation/actions/workflows/ci.yml)

These checks validate the public companions and demo sources. They do not run Power BI Desktop or independently verify reported business outcomes.

## Tools and credentials

**Tools:** Power BI · DAX · Power Query · SQL / SQLite · Python · DuckDB · REST APIs · Git/GitHub Actions · Gurobi · Excel

**Forecasting:** Stocked-day baseline; format × category lift; 12-promotion backtest; interval and order rule | [Code](https://github.com/dogantunagerguz/promotion-demand-forecast/blob/main/forecast_p19.py) · [Notebook](https://github.com/dogantunagerguz/promotion-demand-forecast/blob/main/claims_analysis.ipynb) · [Memo](https://github.com/dogantunagerguz/promotion-demand-forecast/blob/main/docs/memo.pdf) |

**Certificates:**
- Microsoft Certified: Power BI Data Analyst Associate
- [IBM / Coursera: Databases and SQL for Data Science with Python](https://coursera.org/verify/YBWV668PB596)
- M.A. International Management · B.Sc. Industrial Engineering

**Languages:** Turkish (native) · English (C1) · German (B2)
