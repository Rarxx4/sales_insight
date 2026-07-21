# Sales Insights: AtliQ Hardware Power BI Project
### A Business Consultant's Guide


---

## Executive Summary

This project simulates a real data analytics consulting engagement: a mid-size hardware distributor is losing sales visibility as it scales, and a data team is brought in to diagnose the problem and deliver a decision-support dashboard. It's built as a training project, but its structure mirrors an actual client engagement end to end — problem framing, discovery, data work, delivery, feedback, and iteration — which is what makes it useful as a template for how a data/BI advisory engagement should run.

## Client Profile

**AtliQ Hardware** — a fictional computer hardware and peripherals manufacturer/distributor with multiple branches across India and an expansion push into Latin America.

## The Business Problem

The Sales Director can't get a clear read on performance. Symptoms:

- Sales are declining gradually and the cause isn't obvious from current reporting.
- The business still runs its analytics off Excel files — slow to consume, error-prone, and impossible to refresh in real time.
- Lack of timely insight contributed directly to a significant loss in the Latin America market.
- Multiple functions (sales, marketing, customer service) are making decisions without a shared, trusted view of the numbers.

This is a common trigger for a BI engagement: the business has data, but not *insight*. The ask isn't "build a dashboard" — it's "help me see what's happening in my business before it costs me more."

## Stakeholders

- **Sales Director** — primary sponsor, needs performance visibility and forecasting support.
- **Marketing Team** — needs regional/customer segmentation to target campaigns.
- **Customer Service Team** — needs order and account-level context.
- **Data & Analytics Team** — owns the pipeline and dashboard build.
- **IT** — owns infrastructure, access, and deployment (including mobile access).

## Objectives

1. Surface sales insights that weren't previously visible to the sales team.
2. Move from manual Excel reporting to an automated, self-service dashboard.
3. Reduce the time analysts spend gathering and reconciling data by hand.
4. Give every stakeholder group a shared, real-time source of truth for decisions.

## Engagement Methodology

The project follows a phased approach that maps closely to how a consulting/analytics engagement is typically scoped and delivered:

| Phase | What Happens | Consulting Equivalent |
|---|---|---|
| 1. Problem Statement | Define the business pain point, sponsor, and success criteria | Scoping / statement of work |
| 2. Data Discovery | Inventory available data sources and assess quality/gaps | Current-state assessment |
| 3. Data Analysis (SQL) | Query raw transactional data to validate early hypotheses | Diagnostic analysis |
| 4. Data Cleaning & ETL | Standardize, clean, and model the data for reporting | Data engineering / prep |
| 5. Build Dashboard/Report | Design and build the Power BI report against business questions | Solution build |
| 6. Stakeholder Feedback | Walk the dashboard through with sponsors, capture gaps | Client review / UAT |
| 7. Publish Report | Deploy to the Power BI service for broader access | Go-live / rollout |
| 8. Mobile Access | Enable access via the Power BI mobile app | Adoption / accessibility |
| 9. Version 2 (Iteration) | Rebuild based on stakeholder feedback | Continuous improvement cycle |

The point worth taking from this for consulting work generally: the dashboard isn't the deliverable, the decision-support process is. Feedback and a version 2 are built into the plan from the start rather than treated as scope creep.

## Data & Scope

The underlying dataset is a simulated sales transactions system covering:

- Sales transactions (order-level detail)
- Customers
- Markets/regions
- Products
- Dates (for time-intelligence)

This is a small, clean star-schema-style dataset by design — intentionally simple so the focus stays on the analysis and delivery process rather than data wrangling.

## Tools & Techniques Used

- **SQL** — exploratory querying of raw sales data
- **Power BI (Power Query)** — data cleaning and transformation
- **Power BI (data modeling)** — relationships between transactions, customers, products, markets, and dates
- **Power BI (DAX/reporting)** — building KPIs and visuals
- **Power BI Service** — publishing and sharing
- **Power BI Mobile** — field/on-the-go access

## Business Value Delivered

- A single, trusted view of sales performance replacing scattered Excel files.
- Faster time-to-insight for the sales and marketing teams.
- A repeatable framework: once built, the dashboard refreshes automatically instead of requiring manual reassembly each period.
- A structured feedback loop that turns a first-draft dashboard into one stakeholders actually adopt.

## Why This Matters for a Business Consultant

Even without writing a line of DAX or SQL, a consultant can use this project as a reference model for:

- **Framing a data/BI engagement** — how to translate a vague complaint ("sales are down and I can't tell why") into a scoped, staged project.
- **Stakeholder management** — identifying who needs what from the same dataset (Sales wants performance, Marketing wants segments, Service wants order context).
- **Change management** — the "feedback → v2" phase is a reminder that adoption, not just delivery, is the real success metric on analytics projects.
- **Vendor/team evaluation** — this is a useful checklist for assessing whether an internal team or outside vendor is following a sound BI delivery process.
- **Client conversations** — a plain-English walkthrough of what a "Power BI project" actually involves, useful when scoping similar work for your own clients.

