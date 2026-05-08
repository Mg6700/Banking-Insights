# Banking Insights — Financial Transaction Analysis

**Tools:** Power BI, DAX  
**Domain:** BFSI Analytics | Transaction Monitoring | Branch Performance  
**Portfolio:** [mg67.vercel.app](https://mg67.vercel.app/) | **GitHub:** [Mg6700](https://github.com/Mg6700)

---

## Project Overview

This project analyzes banking transaction data from 2013 to 2023 covering $492M in total balance and $3bn in total loan amounts. The dashboard tracks transaction patterns by medium, type, and account category, identifies top-performing branches and states, and surfaces transaction volume trends over a decade — providing insights relevant to retail banking operations and branch performance management.

---

## Key Metrics

| Metric | Value |
|---|---|
| Total Balance | $492M |
| Total Loan Amount | $3bn |
| Average Balance | $492K |
| Average Loan Amount | $5M |

---

## Dashboard Features

- **Year filter** (2013–2023) — decade-level temporal analysis
- **Month filter** (January–December) — seasonal transaction patterns
- **Transaction Medium** — Check / Cash / Debit Card / Credit Card breakdown
- **Transaction Type** — Purchase / Deposit / Transfer / Withdrawal split
- **Transactions by Account Type** — Savings / Checking / Fixed Deposit distribution
- **Transactions by Account Status** — Active / Pending / Closed breakdown
- **Transaction Trend** — line chart of transaction volume 2014–2022
- **Top 5 Branch States by Transaction Amount** — state-level performance
- **Top 5 Branches by Transaction Amount** — individual branch ranking

---

## Transaction Medium Breakdown

| Medium | Share |
|---|---|
| Cash | 26.03% |
| Credit Card | 25.83% |
| Debit Card | 24.98% |
| Check | 23.17% |

---

## Transaction Type Breakdown

| Type | Share |
|---|---|
| Deposit | 26.74% |
| Withdrawal | 24.81% |
| Transfer | 24.39% |
| Purchase | 24.06% |

---

## Account Type Distribution

| Account Type | Share |
|---|---|
| Checking | 36.04% |
| Fixed Deposit | 33.45% |
| Savings | 30.51% |

---

## Account Status Distribution

| Status | Share |
|---|---|
| Closed | 36.33% |
| Pending | 33.87% |
| Active | 29.8% |

---

## Top States by Transaction Amount

| State | Amount |
|---|---|
| North Carolina | $18M |
| Louisiana | $16M |
| New York | $13M |
| Iowa | $12M |
| Virginia | $12M |

---

## Top Branches by Transaction Amount

| Branch | Amount |
|---|---|
| IA00033 | $8.8M |
| NC00010 | $7.7M |
| IL00035 | $7.3M |
| AZ00046 | $7.0M |
| VA00048 | $6.8M |

---

## Key Findings

**1. All four transaction mediums are nearly equally distributed (~25% each)**
The near-perfect balance across Cash, Credit Card, Debit Card, and Check suggests a mature, diversified customer base with no single payment method dominating — unlike typical digital-first banks where card payments lead heavily.

**2. Transaction volume peaked at 27M in 2014 and 2019, declining to 18M by 2022**
The transaction trend shows two peaks separated by a mid-period dip, with a sharp decline in 2022 — possibly reflecting branch consolidation, digital migration, or post-pandemic behavioral shifts.

**3. 36.33% of accounts are Closed — the largest account status segment**
More accounts are closed than active (29.8%), which is a concerning retention signal suggesting high customer churn relative to new account acquisition.

**4. Checking accounts lead (36.04%) over Fixed Deposits (33.45%) and Savings (30.51%)**
The relatively high Fixed Deposit share suggests a customer base with savings-oriented behavior — potentially older demographic or high-interest rate environment driving term deposit preference.

**5. North Carolina leads all states with $18M in transactions**
Despite New York typically dominating banking metrics nationally, NC leads here — suggesting this dataset covers a regional bank with concentrated Southeastern US operations.

**6. All transaction types are nearly equally split (~25% each)**
Equal distribution across Deposit, Withdrawal, Transfer, and Purchase indicates healthy account activity diversity — customers are using accounts for all banking functions rather than single-purpose use.

---

## Technical Highlights

- Decade-long time series with year and month dual-filter capability
- Four simultaneous donut charts for medium, type, account type, and status analysis
- Branch-level and state-level performance ranking
- DAX measures for average balance, average loan, and transaction share %
- Transaction trend line spanning 2014–2022

---

## Data Source

Banking Transaction Dataset — Kaggle.

---

*Created by Mayur Goyal | [Portfolio](https://mg67.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mg67)*
