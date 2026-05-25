# About Tutu

## What is Tutu?

Tutu is a financial planning and retirement planning software that helps you track, analyze, and project your financial life — all in one place.

## Who is it for?

Tutu is useful for everyone on the financial journey — from the new graduate who just started their first job and wants to build good habits, to the person who is approaching retirement and would like to access their financial readiness or already retired and wants to stay on top of their financial health.

## What features does it have?

- **Overview** — A dashboard showing your total net worth with historical charts across all asset types and cashflow trends.
- **Stock** — Track your stock and investment portfolio with live price updates from Yahoo Finance and historical performance charts.
- **Real Estate** — Manage your property holdings, track values, rental income, and mortgage details.
- **Saving** — Monitor your savings and cash accounts over time.
- **Retirement** — Track your retirement accounts (401k, IRA, etc.) and watch them grow.
- **Retirement Planning** — A step-by-step configuration wizard that sets up your retirement plan, modeling withdrawals (fixed, percentage, or RMD), Social Security, inflation, spouse income, and planned life events.
- **Retirement Estimation** — A detailed year-by-year projection chart and table showing how your assets will grow and be drawn down through retirement.
- **Life Events** — Plan major financial life events (buying or selling a home, college costs, new baby, job loss, inheritance, wedding, medical expenses, and more) and see their impact on your retirement trajectory.
- **Income and Tax** — Project your year-by-year income from all sources alongside a federal income tax estimate, so you can plan withdrawals with tax efficiency in mind.

## Why does Tutu only have a desktop version?

This is a deliberate choice to protect your privacy. Tutu will NEVER upload any of your financial information to the cloud. Everything stays on your local computer — forever. The only internet connection Tutu ever makes is to Yahoo Finance to fetch stock prices when you request a snapshot update or ping Github for the latest version and download it if detected.

## Need Support or have feedback or feature request?

Email us at lihua.cao2007@gmail.com. This is only a hobby project so far, but we will try to respond as fast as we can.

## Release Notes

### v1.0.12 — 2026-05-24

**Dark mode polish**
- All panels (Retirement Planning, Life Events, Income and Tax) now fully respect dark mode — panel headers, borders, and section backgrounds are consistent with other panels.
- Life Events table no longer shows a white border around the scroll area in dark mode.
- Retirement Planning wizard: the "Do you have a spouse" checkbox and "Back" navigation button now correctly use the dark theme background instead of rendering white.
- Retirement Financial Estimation bar chart: tooltip now uses the correct light/dark background and border colors — previously showed a dark tooltip even in light mode.
- Chart backgrounds (Overview, Retirement Financial Estimation, Income and Tax Projection) are now consistent with the theme across both modes.
- Navigation panel version label is now readable in dark mode.

**About page and README updated**
- "What features does it have" now lists all panels: Overview, Stock, Real Estate, Saving, Retirement, Retirement Planning, Retirement Estimation, Life Events, and Income and Tax.
- "Who is it for" section updated to mention financial readiness assessment for those approaching retirement.

---

### v1.0.11 — 2026-05-24

**Income and Tax panel (new)**
- Added "Income and Tax" sub-menu under Retirement Planning in the sidebar.
- Bar chart showing taxable income components (salary, rental, interest/dividend, Social Security, 401k/IRA withdrawal, other) stacked per year, plus a non-taxable income bar.
- Overlay line for total income and a right-axis line for effective tax rate %.
- Detail table with years as columns, showing: all taxable income rows, Taxable Income Subtotal, Pre-Tax Contributions, Standard Deduction, Net Taxable Income, each federal tax bracket row (rate + range with income falling into that bracket), Estimated Tax, Effective Tax Rate, Non-Taxable Income, and Income After Tax.
- Clicking a chart bar scrolls the table to align that year column; clicking a table column header highlights the corresponding chart bar.

**Retirement projection improvements**
- Annual equity gain from mortgage principal payments is now added to the real estate asset value each year in the projection — previously only the starting equity and market appreciation were tracked.

---

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

### 1. Support More Life Events
- Add a "Gift to kid" life event

### 2. Improve Reminders
- Add reminders to update asset snapshots
- Add reminders on financial tips and actions to take

### 3. Improve Tax and Withdrawal Strategy
- Increase the standard deduction projection based on historical increases or the configured inflation rate
- Consider tax treatment in withdrawals (Roth vs. traditional retirement accounts, or capital gains tax)
- Add configuration to allow users to choose their preferred withdrawal priority across different asset types

### 4. Projection Improvements
- Add a what-if scenario feature to explore alternatives without changing existing planning
- Add a financial scan that surfaces tips and tax optimizations based on the current asset portfolio and income — e.g. best time for a Roth conversion, best time to realize capital gains from stocks, asset allocation adjustments based on age and retirement progress
