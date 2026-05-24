# About Tutu

## What is Tutu?

Tutu is a financial planning and retirement planning software that helps you track, analyze, and project your financial life — all in one place.

## Who is it for?

Tutu is useful for everyone on the financial journey — from the new graduate who just started their first job and wants to build good habits, to the person who is approaching retirement or already retired and wants to stay on top of their financial health.

## What features does it have?

- **Overview** — A dashboard showing your total net worth with historical charts across all asset types and cashflow trends.
- **Stock** — Track your stock and investment portfolio with live price updates from Yahoo Finance and historical performance charts.
- **Real Estate** — Manage your property holdings, track values, rental income, and mortgage details.
- **Saving** — Monitor your savings and cash accounts over time.
- **Retirement** — Track your retirement accounts (401k, IRA, etc.) and watch them grow.
- **Retirement Planning** — A step-by-step planning wizard that projects your retirement trajectory, models withdrawals (fixed, percentage, or RMD), accounts for Social Security, inflation, spouse income, and life events such as home purchases or sales.

## Why does Tutu only have a desktop version?

This is a deliberate choice to protect your privacy. Tutu will NEVER upload any of your financial information to the cloud. Everything stays on your local computer — forever. The only internet connection Tutu ever makes is to Yahoo Finance to fetch stock prices when you request a snapshot update.

## Need Support or have feedback or feature request?

Email us at lihua.cao2007@gmail.com. This is only a hobby project so far, but we will try to respond as fast as we can.

## Release Notes

### v1.0.10 — 2026-05-23

**Real Estate property improvements**
- Separated "Monthly Rental" (gross rent) from mortgage payments to eliminate ambiguity — rental income and mortgage costs are now tracked independently.
- Added **HOA** field (amount + frequency: Monthly / Quarterly / Yearly) to the property add/edit dialog.
- Added **Annual Property Tax Rate (%)** field to the property add/edit dialog.
- Added **Monthly Mortgage Payment** as a read-only auto-computed field in the Mortgage Info section of the property dialog.

**Projection Details table improvements**
- New **Mortgage Payment** expense row showing all active DB property mortgage payments.
- New **Housing Cost** expense row aggregating HOA fees and property taxes across all properties, inflation-adjusted year over year.
- **Monthly Rental** column renamed and semantics clarified — always shows gross rental income (zero for non-rental properties).

**Life event improvements**
- **Pay Off Mortgage** life event: pick a property from your DB, auto-calculates current loan balance, deducts from savings (overflows to stock), and removes future mortgage payments from the projection.
- **Sell a House (rental)**: correctly routes appreciation to taxable income and equity recovery to stock.
- Rental property sale appreciation now appears in the **Other Income** row of Projection Details.

**Privacy & reliability**
- Removed third-party property valuation API — property values are now updated manually to eliminate internet dependency and protect financial privacy.

---

### v1.0.9 — 2026-05-22

## TODOs

### 1. Support more life events
- 1.1 Double-check that equity from each mortgage payment is correctly added to the real estate asset
- 1.2 Add a "Gift to kid" life event

### 2. Improve reminders and tips
- 2.1 Add reminders to update asset snapshots, or surface new tips when relevant
- 2.2 Add various financial tips based on current asset portfolio or income — such as best time for Roth conversion, exercising capital gains from stocks, asset rebalancing, etc.
- 2.3 Add corresponding tax optimization suggestions

### 3. Improve tax-related predictions
- 3.1 Add a tax obligation chart
- 3.2 Consider tax treatment in withdrawals (Roth vs. traditional retirement accounts, or capital gains tax)
- 3.3 Add configuration to allow users to choose their preferred withdrawal priority across different asset types
- 3.4 Customize future expenses for different year ranges
