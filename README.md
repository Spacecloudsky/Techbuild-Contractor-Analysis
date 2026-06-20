# Techbuild Contractors Financial Performance Analysis (2024)

> **Good contracts. Bad collections.** Despite N416.5M in contract value, slow collections have pushed Techbuild into a cashflow-negative position — meaning the business is currently financing its own operations. This analysis identifies where the money is, why it isn't coming in, and what management should do about it.

![Techbuild Dashboard](images/techbuild-page1.png)
![Insights & Recommendations](images/techbuild-page2.png)

## Business Problem

A mid-sized Nigerian contracting firm with a strong project pipeline is experiencing negative actual profit (-N100.3M) despite N416.5M in total contract value. The gap between contracts won and cash received is threatening operational continuity.

## Dashboard Overview

A 2-page Power BI report covering financial performance, payment status across the client base, outstanding balance by client, revenue vs contract value trends, and a full client-level summary table with contract status and payment health.

## Key Insights

- Actual profit is **-N100.3M** against a projected profit of N82.7M — the entire gap is a collections problem, not a profitability one.
- **25% of clients have made zero payment** to date, representing direct zero-payment risk to the business.
- Government clients (Uwvie LGA and Warri Port Authority) make up **26% of total contract value** but are among the slowest payers, with N20M outstanding from Uwvie LGA alone.
- Completed contracts show clients **do pay in full** — the risk is concentrated in active and pending contracts where no upfront deposit policy exists.
- **69.95% collection rate** means nearly 30% of billed revenue has not been recovered.

## Recommendations

- Prioritize immediate follow-up on N183M in outstanding receivables to restore cashflow.
- Enforce upfront deposit requirements for all government clients before work commences.
- Pause new work for Apex Logistics, Oilserve, and Osubi Airport Authority until initial payments are secured.
- Introduce a collections milestone tied to project progress — payment gates before each project phase.

## Tools

Power BI · DAX · Excel (data preparation)

## Repo Structure

```
techbuild-contractors-analysis/
│
├── data/
│   └── techbuild_2024.xlsx
│
├── dashboard/
│   └── techbuild_contractors_report.pbix
│
├── images/
│   ├── techbuild-page1.png
│   └── techbuild-page2.png
│
└── README.md
```

---
*Part of my BI portfolio: [spacecloudsky.netlify.app](https://spacecloudsky.netlify.app)*
