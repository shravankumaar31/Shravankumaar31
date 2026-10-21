# Hi, I'm Shravan 👋

**GTM Engineer** · I build the automation and data systems behind B2B SaaS revenue teams: signal capture, enrichment, scoring, routing, CRM integrity, and AI agents that take manual work off reps' plates.

📍 Bay Area &nbsp;·&nbsp; 🌐 [Portfolio](https://shravangtm.lovable.app/) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/shravan-kumaar/) &nbsp;·&nbsp; ✉️ shravankumaar96@gmail.com

---

## 🛠 What I build

- **Lead enrichment and routing at scale:** 50,000+ leads a month enriched with Clay and ZoomInfo, scored against the ICP with Claude, and routed into Salesforce through n8n, sourcing **$8M in pipeline**
- **Territory and quota automation:** assignment rules that keep 500+ accounts balanced across 45 reps as accounts change
- **Sales ops workflow automation:** 30+ workflows across HubSpot and Salesforce plus a custom CPQ integration, eliminating **20 hours of manual work a week** and cutting quote generation from **2 hours to 15 minutes**
- **Customer health scoring:** product usage and CRM signals combined into a health score that flagged 70+ at-risk accounts and helped reduce churn from **34% to 22%**
- **AI on top of the CRM:** a webhook-based Gong to Salesforce integration with Claude summarization, putting call summaries on **93% of account records** for 45 reps
- **CRM data integrity:** duplicate and matching rules that cut duplicates by **95%**, a 15,000-contact migration into HubSpot, and validation rules that raised field completeness from **65% to 91%**
- **Self-service revenue reporting:** a Salesforce dashboard that replaced 12 manual weekly reports, with Zapier alerts on routing and health-score changes

---

## 🚀 Featured projects

### [Signal-to-Pipeline](https://github.com/shravankumaar31/signal-to-pipeline)
**Clay · n8n · Salesforce · Apify · Claude (API + MCP) · JavaScript · Python**

A GTM engine that turns buying signals into scored, routed, rep-ready pipeline.
- Scrapes job posts from Greenhouse, Lever, Ashby and Workable with Apify, and tracks 6 signal types with weights and decay
- Scores accounts 0–100 in Clay, tiers them A / B / C, and ranks contacts through a waterfall with email verification
- Upserts Accounts, Signals and Contacts to Salesforce through n8n on external ID: **0 load errors, idempotent re-runs**
- Routes Tier A/B accounts to an AE and BDR by territory, capacity, tenure and out-of-office status (`mapping.js` and `routing.js`, covered by Node tests)
- Claude writes "why now" rationales, email drafts and rep Tasks; every draft is validated and **never auto-sent**
- 49 logged design decisions, 5 reports and a dashboard

### [GPU Cloud Deal Desk](https://github.com/shravankumaar31/gpu-deal-desk)
**HubSpot · Python**

A working quote-to-cash deal desk for a GPU cloud company, built in HubSpot and enforced in Python.
- Quote engine prices deals from a versioned price book and returns BLOCKED, PENDING APPROVAL or APPROVED, generating an order form PDF on approval
- Retuned the approval matrix to cut deals routed to the CEO from **36% to 16%**
- "3-Day Rule" contract tracker with a daily digest, escalation ladder and controlled pauses
- 9-rule hygiene audit raised the portal clean rate from **90.6% to 92.3%** and flagged **$2.3M** in won deals not ready to invoice
- 25 judgment calls documented in a decisions log

### [B2B SaaS GTM Analytics Pipeline](https://github.com/shravankumaar31/B2B-SaaS-GTM-analytics)
**Salesforce · PostgreSQL · SQL · Tableau · Python**

End-to-end GTM analytics from raw CRM data to executive dashboards.
- Loaded 85 Accounts and 7,375 Opportunities into Salesforce and fixed a broken Stage-to-Forecast-Category mapping
- PostgreSQL semantic layer: 5 raw tables, 9 validation checks, 4 analytics views
- 4-page Tableau suite (17 worksheets): pipeline health, a 30-rep productivity scorecard, weighted forecast vs. actuals, and retention (**89.4% GRR, 93.3% NRR**)

### [Aerospace Supply Chain Risk AI](https://github.com/shravankumaar31/Aerospace-supply-chain-risk-ai)
**Python · SQLite · Claude API · Streamlit · Plotly · pytest · GitHub Actions**

A scheduled data pipeline that scores U.S. aerospace supply chain risk and uses Claude to write procurement briefs.
- Ingests 10,000 federal contract awards plus Census trade and BLS employment data from public APIs
- Scores supplier concentration (HHI), geographic and workforce risk across 50 states and 4 NAICS sectors
- Claude drafts a one-page procurement risk brief for any high-risk segment, exportable to PDF
- Runs weekly on GitHub Actions, with 8 passing pytest tests

---

## 📊 Data engineering and forecasting

- **[Snowflake 10-K Financial Pipeline](https://github.com/shravankumaar31/snowflake-10k-pipeline):** SEC EDGAR ingestion on AWS (S3, Glue, Athena, Lambda, EventBridge, SQS dead-letter queue), provisioned with Terraform, with ARIMA revenue forecasting, DCF valuation and Tableau dashboards
- **[B2B Sales Forecasting Ensemble](https://github.com/shravankumaar31/b2b-sales-forecasting-ensemble):** quarterly sales forecasts for 75 B2B customers; an Optuna-tuned LightGBM model (300 trials) beat XGBoost, CatBoost and stacked ensembles with a Kaggle MAE of 537.85
- **[BART Ridership Analysis](https://github.com/shravankumaar31/bart-ridership-analysis):** ridership trends, pandemic recovery, station revenue rankings and 2030 forecasting

---

## 🧰 Stack

| Area | Tools |
|---|---|
| Enrichment & signals | Clay, ZoomInfo, Apify, Apollo.io, waterfall enrichment, intent and buying signals |
| CRM | Salesforce (Flows, validation rules, Data Loader, `sf` CLI), HubSpot (workflows, quotes), Gong |
| Automation & AI | n8n, Zapier, Claude (API + MCP), webhooks, REST APIs, AI agents |
| Code & data | JavaScript (Node), Python, SQL, PostgreSQL, SQLite |
| Cloud & DevOps | AWS (S3, Lambda, Glue, Athena, EventBridge), Terraform, GitHub Actions |
| Analytics & ML | Tableau, Power BI, Looker, Streamlit, LightGBM, XGBoost |

---

## 📈 Impact Highlights

| Result | Impact |
|---|---|
| Pipeline sourced from automated enrichment and routing | **$8M** |
| Leads enriched, scored and routed per month | **50,000+** |
| Manual sales ops work eliminated per week | **20 hours** |
| Quote generation time | **2 hours → 15 minutes** |
| Customer churn | **34% → 22%** |
| Duplicate CRM records | **−95%** |
| CRM field completeness | **65% → 91%** |
| Account records with AI call summaries | **93%** |
| Alexa NLP model accuracy (Amazon) | **89% → 92%** |
| Annotator ramp-up time (Amazon) | **−50%** |

---

## 🎓 Education

- **M.S. Business Analytics**, California State University East Bay (2023–2025)
- **B.Tech Computer Science**, SRM Institute of Technology (2015–2019)

## 📜 Certifications

HubSpot Revenue Operations · HubSpot Sales Hub & Reporting · Atlassian Jira Fundamentals (Agile)

---

## 🎯 Where I'm Headed

I'm looking for a **GTM Engineer** or **technical RevOps** role at a B2B SaaS or AI company, where I can own the GTM stack end to end: building the agents, integrations and data flows that let sales teams spend their time selling and let leadership trust the numbers.

Open to Bay Area roles, in office or hybrid, and remote. Let's connect on [LinkedIn](https://www.linkedin.com/in/shravan-kumaar/).
