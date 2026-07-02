# Task 2: Evaluating Client Profiles and Real Estate Investments

**Program:** Goldman Sachs – Risk Management Virtual Experience Program (Forage)
**Difficulty:** Easy | **Duration:** 20–30 minutes

## Overview

This task builds on the foundational risk concepts from Task 1 and applies them to real-world financial scenarios encountered by a risk analyst at Goldman Sachs. It is split into two parts:

1. **Individual Credit Risk Assessment** — evaluating the creditworthiness of four fictional client personas using a simplified risk calculator.
2. **A Quantitative Approach to Real Estate Risk Analysis** — assessing and mitigating risks associated with a real estate investment in the Florida apartment market.

---

## Part 1: Individual Credit Risk Assessment

### Objective
Assess the credit risk of four fictional personas by inputting their financial details into a risk calculator, which normalizes and weights key financial attributes to produce a risk category.

### Methodology
The risk calculator evaluates five weighted attributes for each persona:

| Attribute | Weight |
|---|---|
| Credit Score | 25% |
| Annual Income | 20% |
| Debt | 20% |
| Savings | 25% |
| Late Payments | 10% |

Each attribute is normalized to a 0–100 scale, then combined into a single **Weighted Score**, which determines the final **Risk Category**:
- **0–33:** High Risk
- **34–66:** Medium Risk
- **67–100:** Low Risk

### Persona Financial Profiles

| Attribute | Persona 1 | Persona 2 | Persona 3 | Persona 4 |
|---|---|---|---|---|
| Annual Income | $280,000 | $180,000 | $100,000 | $150,000 |
| Credit Score | 760 | 700 | 660 | 720 |
| Debt | $150,000 | $100,000 | $90,000 | $200,000 |
| Savings | $450,000 | $120,000 | $20,000 | $80,000 |
| Late Payments | 0 | 1 | 2 | 1 |

### Results

| Persona | Profile Summary | Weighted Score | Risk Category |
|---|---|---|---|
| **Persona 1** | Entrepreneur diversifying into sustainable investments | 72.08 | **Low Risk** |
| **Persona 2** | Mid-career professional planning a home purchase | 44.85 | **Medium Risk** |
| **Persona 3** | High-earning IT consultant consolidating debt | 34.03 | **Medium Risk** |
| **Persona 4** | Small business owner with seasonal income | 48.42 | **Medium Risk** |

### Key Observations
- **Persona 1** benefits from a strong credit score, substantial savings, high income, and a clean payment history — resulting in the lowest overall risk.
- **Persona 3** sits closest to the High Risk threshold, driven by the lowest income and savings combined with the highest number of late payments — a reminder of how multiple weaker attributes compound risk.
- **Persona 4** shows how a strong credit score and reasonable income can offset a high debt load, keeping the profile within Medium Risk rather than High Risk.

---

## Part 2: Credit Risk Scenario Analysis

Building on the calculator results, the following scenarios examined how specific financial events would affect each persona's credit risk profile.

| # | Scenario | Answer | Rationale |
|---|---|---|---|
| 1 | Persona 1 has access to an unused $10,000 personal credit card | **Decrease due to added financial flexibility** | Unused available credit is treated as a flexibility buffer rather than a liability in this context. |
| 2 | Persona 2 considers a new mortgage without paying off existing debts | **Increase risk due to higher debt levels** | A new mortgage adds to an already-existing debt burden, raising overall risk exposure. |
| 3 | Persona 3 successfully consolidates their debt | **Decrease due to easier debt management** | Consolidation simplifies repayment structure, reducing the likelihood of missed or late payments. |
| 4 | Persona 1 liquidates assets to fund a start-up | **Increase due to the reduction in liquid assets** | Reduced liquidity weakens the ability to cover short-term obligations, even if long-term income potential rises. |
| 5 | Persona 2 secures a 3-year fixed-salary employment agreement | **Decrease — contractual income support** | A guaranteed income stream over a defined period reduces uncertainty around future repayment capacity. |
| 6 | Persona 4 has a $50,000 business loan with 2 years of on-time repayments | **Decrease — consistent repayment history indicates financial responsibility** | A demonstrated track record of reliable repayment is a strong positive indicator of creditworthiness. |

### Key Takeaway
This exercise reinforced that credit risk is dynamic — it is influenced not only by static financial figures (income, debt, savings) but by **behavioral factors** (repayment history), **structural changes** (debt consolidation, new liabilities), and **future income certainty** (employment stability). A complete risk assessment requires evaluating both the current financial snapshot and the trajectory of a client's financial decisions.

---

## Part 3: A Quantitative Approach to Real Estate Risk Analysis

### Scenario
As a risk associate at Goldman Sachs, the task involved assessing a client's apartment complex investment in the Florida real estate market — a market characterized by strong rental demand, but also exposed to variable tax policy, hurricane risk, seasonal demand swings, and new competitive developments.

### Methodology
For each identified risk, an estimated probability was assigned based on the given market context. The workbook automatically converted this probability into a **Risk Level** (Low / Medium / High) using the following thresholds:
- **< 0.40:** Low Risk
- **0.40 – 0.64:** Medium Risk
- **≥ 0.65:** High Risk

A mitigation strategy was then selected for each risk, and the workbook generated a corresponding outcome justification.

### Risk Assessment & Mitigation Summary

| Risk | Estimated Probability | Risk Level | Selected Mitigation Strategy | Outcome Justification |
|---|---|---|---|---|
| Increase in property taxes | 50% | **Medium Risk** | Explore legal avenues for tax reduction | Investing in legal advice could provide significant tax savings and is worth the effort at this risk level. |
| $250k+ in needed major repairs | 75% | **High Risk** | Plan for a one-time rent increase | Provides immediate funding for urgent repairs, directly addressing the high risk. |
| 10% drop in occupancy rate | 45% | **Medium Risk** | Introduce competitive pricing | Can quickly attract new tenants and retain existing ones, directly addressing the occupancy challenge. |
| Market downturn affecting property values and rental income | 25% | **Low Risk** | Adjust rent to market conditions | Keeps the property competitive and attractive to tenants, a cautious approach aligned with the lower immediacy of risk. |
| New development competition | 55% | **Medium Risk** | Introduce loyalty programs for existing tenants | Crucial for retaining tenants during a period of growing competition. |

### Rationale for Probability Estimates
- **Property tax increase (50%):** The market briefing described "variable" tax rates — genuine uncertainty warranted a mid-range estimate.
- **Major repairs (75%):** Hurricane exposure was explicitly flagged as a "serious consideration" for property integrity, justifying a high probability.
- **Occupancy drop (45%):** Seasonal demand swings were noted, but strong underlying demand (population growth, tourism) kept this from reaching High Risk.
- **Market downturn (25%):** The overall market was described as "thriving," making a downturn the least likely risk in the near term.
- **New development competition (55%):** The briefing explicitly named this as an active, emerging threat to long-term occupancy.

### Key Takeaway
This exercise demonstrated how quantitative probability estimates — grounded in qualitative market intelligence — can be systematically converted into actionable risk categories and mitigation strategies. It highlighted a core principle of risk management at Goldman Sachs: **the right mitigation strategy is not fixed, but must scale in intensity with the assessed level of risk.** A low-risk scenario calls for a low-cost, low-effort response, while a high-risk scenario justifies more significant, immediate investment.

---

## Overall Program Reflection

Across both tasks, this simulation provided hands-on exposure to the core building blocks of risk management as practiced in Goldman Sachs' Global Banking and Markets (GBM) and Asset and Wealth Management (AWM) divisions:

- **Risk identification and categorization** using the Market, Credit, Liquidity, Operational, and Model risk framework.
- **Quantitative credit risk assessment** through weighted, multi-factor scoring models.
- **Scenario-based risk analysis**, evaluating how financial decisions dynamically shift a client's risk profile.
- **Quantitative real estate risk analysis**, converting market intelligence into probability estimates, risk categories, and scaled mitigation strategies.

This program reinforced that effective risk management is not a one-time assessment but an ongoing, data-driven process — balancing quantitative models with contextual business judgment to support sound, strategic financial decision-making.
