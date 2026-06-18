# About Tutu &nbsp; ![GitHub Downloads](https://img.shields.io/github/downloads/lihuacao2007/tutu-releases/total?label=downloads&color=blue)

## What is Tutu?

Tutu is a financial planning and retirement planning software that helps you track, analyze, and project your financial life — all in one place.

**Download:** https://github.com/lihuacao2007/tutu-releases/releases

**Source Code:** https://github.com/lihuacao2007/tutu

## Who is it for?

Tutu is useful for everyone on the financial journey — from the new graduate who just started their first job and wants to build good habits, to the person who is approaching retirement and would like to access their financial readiness or already retired and wants to stay on top of their financial health.

## Do I need to enter any PII (Personal Identity Information) to use Tutu?

Zero — no name, no address, no phone, no email, no Social Security number, no account information. The only information that is remotely close to PII is birth year and birth month, which are used solely for retirement age and RMD calculations in the projection.

## What features does it have?

**Asset Management**
- **Overview** — A dashboard showing your total net worth with historical charts (1Y / 5Y / 10Y) across all asset types and cashflow trends. Includes an **Asset Summary Score Card** that automatically scores your Total Asset Value (Rule of 25), Asset Allocation (110-minus-age guideline), Retirement Pre-tax vs. After-tax balance (Roth ratio), Total Savings coverage (months of expenses), Unrealized Capital Gain, and Real Estate Appreciation.
- **Stock** — Track your stock portfolio with a live **↻ Refresh Prices** button that fetches the latest prices from Yahoo Finance. Unrealized Capital Gain is tracked automatically — it adjusts when prices are refreshed and scales proportionally when you sell shares.
- **Real Estate** — Manage your properties with full mortgage tracking (monthly payment auto-calculated from loan details), HOA fees, annual property tax rate, and rental income — all tracked independently so your equity, cashflow, and net costs are always clear. Only the Property Zip Code is stored (not the full address) to protect your privacy.
- **Saving** — Monitor your savings and cash accounts with historical balance charts over time.
- **Retirement** — Track pre-tax (Traditional 401k / IRA) and after-tax (Roth) retirement accounts separately, with historical growth charts.

**Retirement Planning**
- **Retirement Planning** — A step-by-step configuration wizard covering Retirement Timeline, Withdrawal Strategy (fixed amount, percentage, or RMD), Social Security, Spouse, independent return rates per asset class (retirement accounts, stocks, real estate), Order of Withdrawal (pre-tax first or after-tax first), and planned Life Events.
- **Retirement Estimation** — A detailed year-by-year projection chart and table showing how your portfolio grows and is drawn down through retirement. Enforces RMD rules (SECURE 2.0, starting age 73), applies Medicare Part B premiums with IRMAA surcharges, tracks capital gains from stock sales, and splits withdrawals into Pre-Tax and After-Tax rows. The chart marks your and your spouse's retirement ages with labeled dotted lines for easy reference.
- **Life Events** — Plan major one-time financial events (buying or selling a home, paying off a mortgage, college costs, new baby, job loss, inheritance, wedding, medical expenses, and more) and see their impact on your retirement trajectory.
- **Income and Tax** — Project year-by-year taxable income from all sources (salary, rental, Social Security, pre-tax withdrawals, capital gains, and other) alongside a federal income tax estimate with bracket-by-bracket detail, standard deduction, net taxable income, and effective tax rate. The chart marks your and your spouse's retirement ages with labeled dotted lines.
- **Expenses** — Plan year-by-year living expenses with inflation-adjusted projections across six categories (Housing, Healthcare, Food, Transport, Entertainment, Other). Override any individual cell, bulk-update a range, and explore spending patterns through an interactive multi-line chart with drag-to-edit support. The chart marks your and your spouse's retirement ages with labeled dotted lines.

**Retirement Analysis**
- **Retirement Questions** — Three in-depth retirement analyses, each running three progressive layers of simulation and persisting results across app restarts:
  - *Q1 — Do I have enough money to retire from today?* — Rule of 25 income gap check → full deterministic year-by-year projection → 2,000-run Monte Carlo survival probability.
  - *Q2 — When can I retire?* — Safe withdrawal rate year search → deterministic binary search → Monte Carlo confidence search (1,000 runs/year) targeting ≥85% survival probability.
  - *Q3 — What is my best Social Security claiming strategy?* — Lifetime benefit comparison at ages 62 / FRA / 70 → deterministic portfolio impact across all three strategies → 1,500-run Monte Carlo survival probability per strategy.
- **What-If Scenarios** — Explore alternative financial decisions without modifying your existing plan. Each scenario has its own embedded chart showing what-if vs. original Total Assets side by side. The page supports horizontal scrolling on narrow screens:
  - *Scenario 1 — Rate Assumptions*: adjust inflation rate, retirement account return, stock return, and real estate return.
  - *Scenario 2 — Future Tax Rate*: model a federal income tax rate increase (e.g. 50% increase multiplies every bracket rate by 1.5×) taking effect in a specified future year.
  - *Scenario 3 — Retire at Different Age*: enter an alternative retirement age and see how your portfolio trajectory changes, with dotted lines marking both the original and what-if retirement ages on the chart.
- **Retirement Tips** — Automated scan across 8 financial health categories: Roth Conversion Window, Capital Gain Harvesting, Social Security Timing, Sequence-of-Returns Risk Buffer, Pre-RMD Roth Conversion, Medicare IRMAA Cliff, Asset Allocation, and Emergency Fund. Each tip is rated Action Needed / Warning / Info with a detailed explanation. Scans run monthly in the background; tips can be dismissed and reviewed later.

**Finance Literacy** — 19 financial and retirement concepts explained in plain language: 401(k) and 403(b), Backdoor Roth Conversion, Capital Gain, Compound Interest, Inflation, IRMAA (Medicare Income Surcharge), Medicare, Mortgage, Net Worth, Property Tax, Required Minimum Distribution (RMD), Retirement Plans and Contributions, Retirement Spending Smile, Roth IRA and Roth IRA Conversion, Sequence of Returns Risk, Social Security, Tax Brackets, Traditional IRA, and Withdrawal Rate (Safe Withdrawal Rate).

## Why does Tutu only have a desktop version?

This is a deliberate choice to protect your privacy. Tutu will NEVER upload any of your financial information to the cloud. Everything stays on your local computer — forever. The only internet connection Tutu ever makes is to Yahoo Finance to fetch stock prices when you request a snapshot update or ping Github for the latest version and download it if detected.

## Screenshots

### Asset Management

| Overview | Stock |
|----------|-------|
| ![Overview](screenshots/overview.png) | ![Stock](screenshots/stock.png) |

| Real Estate | Saving |
|-------------|--------|
| ![Real Estate](screenshots/real-estate.png) | ![Saving](screenshots/saving.png) |

| Retirement | |
|------------|--|
| ![Retirement](screenshots/retirement.png) | |

### Retirement Planning

| Retirement Planning | Retirement Estimation |
|---------------------|-----------------------|
| ![Retirement Planning](screenshots/retirement-planning.png) | ![Retirement Estimation](screenshots/retirement-estimation.png) |

| Life Events | Income and Tax |
|-------------|----------------|
| ![Life Events](screenshots/life-events.png) | ![Income and Tax](screenshots/income-tax.png) |

| Expenses | |
|----------|--|
| ![Expenses](screenshots/expenses.png) | |

### Retirement Analysis

| Retirement Questions | What-If Scenarios |
|----------------------|-------------------|
| ![Retirement Questions](screenshots/retirement-questions.png) | ![What-If Scenarios](screenshots/what-if.png) |

| Retirement Tips | |
|-----------------|--|
| ![Retirement Tips](screenshots/retirement-tips.png) | |

### Reference

| Finance Literacy | |
|------------------|--|
| ![Finance Literacy](screenshots/finance-literacy.png) | |

## I got an installation error on Mac, what should I do?

Tutu is currently not signed by an Apple developer certificate, so macOS Gatekeeper will block it from opening by default. Follow these steps to allow it:

**Option A — Right-click to open (easiest, one-time only)**

1. Open **Finder** and navigate to your **Applications** folder (or wherever you copied Tutu).
2. **Right-click** (or Control-click) the Tutu icon and choose **Open** from the menu.
3. A dialog will appear saying the app is from an unidentified developer. Click **Open** to proceed.
4. macOS remembers this choice — you can double-click Tutu normally from now on.

**Option B — System Settings (if Option A does not work)**

1. Try to open Tutu by double-clicking it. macOS will show a blocking dialog — click **Done** (do not click "Move to Trash").
2. Open **System Settings** → **Privacy & Security**.
3. Scroll down to the **Security** section. You will see a message like *"Tutu was blocked because it is not from an identified developer."*
4. Click **Open Anyway** next to that message.
5. Confirm by clicking **Open** in the dialog that appears.

**Option C — Terminal (if both options above fail)**

Open **Terminal** and run:

```bash
xattr -cr /Applications/Tutu.app
```

Then double-click Tutu to open it normally. This command removes the macOS quarantine flag that Gatekeeper uses to block unsigned apps.

> **Why does this happen?** Apple requires apps distributed outside the Mac App Store to be signed and notarized. This is a paid developer program ($99/year). Tutu is a free hobby project and has not gone through that process yet. The app itself is safe — you can inspect the full source code at the project repository.

## Need Support or have feedback or feature request?

Email us at tutu.retirement.planning@gmail.com. This is only a hobby project so far, but we will try to respond as fast as we can.

## Release Notes

### v1.1.3 — 2026-06-17

**Retirement Projection — Savings-first withdrawal (new)**
- The projection engine now draws from the **Saving Asset** before touching retirement accounts each year.
- When the saving balance exceeds the configured reserve floor (Saving Asset Balance setting in the Retirement Withdrawal wizard), the surplus is used to cover living expenses first — reducing taxable retirement withdrawals and lowering the annual tax bill.
- RMD (Required Minimum Distribution) floors are always honored regardless of savings availability.
- If savings surplus is insufficient, the remaining gap is covered by pre-tax or after-tax retirement accounts per the configured withdrawal order.

**Retirement Projection — Excess savings swept to Stock Asset (new)**
- At the end of each projection year, any saving balance above the configured reserve floor is automatically moved into the Stock Asset portfolio for better long-term returns.
- This ensures the saving account is never left with idle cash beyond what is needed for liquidity, while the reserve floor is always maintained.

**README — PII question added**
- Added a "Do I need to enter any PII?" section explaining that Tutu requires zero personal identity information — no name, address, phone, email, Social Security number, or account details. Only birth year and birth month are used for retirement age and RMD calculations.

---

### v1.1.2 — 2026-06-16

**What-If Scenarios — Scenario 4: Social Security Benefit Cut (new)**
- A fourth what-if scenario is now available: **"What if Social Security benefits are cut by ___ %?"**
- Enter a cut percentage between 0 and 100 (defaults to 25, reflecting the projected 2033 trust fund shortfall). Both your and your spouse's monthly SS benefit are scaled by `(1 − cut%)` in the what-if projection while all other plan settings remain unchanged.
- Results are displayed in the same embedded simplified chart as other scenarios, with dual Total Assets lines (what-if vs. original) for direct comparison.

**Retirement Withdrawal wizard — Saving Asset Balance (new)**
- A new **"Saving Asset Balance"** dropdown has been added to the Retirement Withdrawal step of the wizard, with options: No buffer (default), 6 / 12 / 18 / 24 Months Living Expense.
- A visual separator line is now drawn above the "Order of Withdrawal" field to clearly separate per-person withdrawal strategy settings from shared settings.
- When a buffer is configured, the retirement projection engine maintains the target saving balance at the end of every year — in pre-retirement years by drawing from the stock portfolio; in retirement years by also drawing from retirement accounts (following the configured withdrawal order). If no other assets are available to fill the shortfall, the balance is left at whatever is available.

**Asset Summary Score Card — Saving score criteria updated**
- The **Total Savings** score thresholds have been updated to reflect a more meaningful liquidity buffer:
  - **Green**: ≥ 2 years of living expenses (previously ≥ 5 years)
  - **Yellow**: ≥ 1 year but < 2 years (previously ≥ 2 years)
  - **Red**: < 1 year of living expenses (previously < 2 years)

**README — Source Code link added**
- A **Source Code** link to the GitHub repository has been added below the Download link.

---

### v1.1.1 — 2026-06-15

**What-If Scenarios — Scenario 3: Retire at Different Age (new)**
- A third what-if scenario is now available: **"What if I retire at ___ years old?"**
- Enter an alternative retirement age (defaults to your currently configured age) and click **Go Analyze** to run a full retirement projection with the shifted retire year while keeping all other plan settings unchanged.
- Results are displayed in the same embedded simplified chart as Scenarios 1 and 2, with dual Total Assets lines (what-if vs. original) for direct comparison.
- Two vertical dotted lines are drawn on the chart — one for your original retirement age and one for the what-if retirement age — both labeled with "Age N" so the shift is immediately visible.

**Retirement Charts — retirement age markers (new)**
- The **Retirement Financial Estimation** chart, **Income and Tax** chart, and **Annual Expense Projection** chart all now display vertical dotted lines marking your retirement age and your spouse's retirement age (if configured).
- Each line is labeled with "Age N" directly on the chart.
- Two new legend entries appear on each chart: "My retirement age" (teal) and "Spouse retirement age" (pink).

**What-If Scenarios — horizontal scrolling on narrow screens (improvement)**
- The What-If Scenarios page now supports horizontal scrolling when the window is narrowed below 700 px, so scenario card content is never clipped or squished.

**Real Estate — Property Zip Code replaces Address (privacy improvement)**
- The "Address" field in the Add/Edit Property dialog is renamed to **"Property Zip Code"** to avoid storing a full street address on disk.
- Existing data is migrated automatically on the next app launch.
- The help tooltips for Purchase Price and Current Value still say "search your property address on Redfin or Zillow" because that is how you look up the values — only what is stored locally has changed.

**Real Estate — Help Tooltips in the Property Dialog (new)**
- Four **"?" help buttons** have been added to the Add/Edit Property dialog:
  - **Purchase Price** — explains how to find your original purchase price on Redfin or Zillow by searching the property address.
  - **Current Value** — explains how to find the current estimated value on Redfin or Zillow.
  - **Annual Property Tax Rate (%)** — suggests searching "[your county] property tax rate" on Google.
  - **Mortgage Info** separator — explains how to find mortgage details by logging into your loan servicer's website or mobile app.
- Hover over "?" to see the tooltip, or click it for a dialog popup.

**Stock — Unrealized Capital Gain auto-tracking (improvement)**
- The Unrealized Capital Gain field is now tracked automatically instead of being a purely manual entry.
- **Price refresh (↻ Refresh Prices)**: the gain adjusts by `shares × (new_price − old_price)`, preserving your cost basis across every price update.
- **Selling shares (reducing share count)**: the gain scales down proportionally — `new_gain = old_gain × (new_shares / old_shares)`.
- **Buying more shares (increasing share count)**: the existing gain stays unchanged; new shares are assumed purchased at the current market price with zero embedded gain.
- **Manual override**: typing directly in the Unrealized Capital Gain field always takes precedence — auto-adjustment is skipped when you edit the field.

---

### v1.1.0 — 2026-06-14

**What-If Scenarios — Scenario 2: Future Tax Rate (new)**
- A second what-if scenario is now available: **"What if federal income tax rates increase?"**
- Enter a tax rate increase percentage (e.g. 50 means every bracket rate is multiplied by 1.5×, so a 22% bracket becomes 33%) and the year the increase takes effect.
- Click **Go Analyze** to run a full retirement projection with the higher tax rates while keeping all other plan settings unchanged (rates, retire year, Social Security, life events, expenses).
- Results are displayed as the same simplified Retirement Financial Estimation chart as Scenario 1: stacked income/expense bars, Net Savings line, and dual Total Assets lines (what-if vs. original) for direct comparison.

**What-If Scenarios — each scenario has its own embedded chart (improvement)**
- Each scenario card now contains its own chart that appears inside the card when **Go Analyze** is clicked, instead of all scenarios sharing a single chart at the bottom of the page.
- Scenario 1's chart appears within Scenario 1's card; Scenario 2's chart appears within Scenario 2's card. Both charts can be visible at the same time for side-by-side comparison.

**Asset Management Overview — Asset Summary and Score Card (new)**
- A new **Asset Summary and Score Card** section appears below the Total Portfolio and Asset Value chart on the Overview page.
- Six rows are scored automatically from your current asset data:
  - **Total Asset Value** — scored GREEN / YELLOW / RED against the Rule of 25 (25× projected annual retirement income gap), or GREEN with a note when Social Security covers projected expenses.
  - **Asset Allocation** — scored against the 110-minus-age stock allocation guideline, flagging significant over- or under-allocation.
  - **Retirement Pre-tax vs. After-tax** — scored on Roth ratio: GREEN ≥ 30% after-tax, YELLOW 10–30%, RED < 10%.
  - **Total Savings** — scored as months of projected monthly expenses covered: GREEN ≥ 12 mo, YELLOW 6–12 mo, RED < 6 mo.
  - **Unrealized Capital Gain** — informational only; shows total unrealized gain with a note to realize gains during low-income years to minimize tax.
  - **Real Estate Appreciation** — informational only; shows total appreciation (current value − purchase price) with the same tax planning note.
- Each row uses a three-column layout: label | value + color badge | scoring logic and legend.

---

### v1.0.28 — 2026-06-13

**What-If Scenarios — Scenario 1: Rate Assumptions (new)**
- Navigating to **What-If Scenarios** now shows a fully functional first scenario instead of a placeholder.
- Enter alternative rate assumptions — expected inflation rate, retirement account annual return, stock asset annual return, and real estate annual return — and click **Go Analyze** to run a projection with those rates while keeping everything else in your plan unchanged (retire year, Social Security, life events, expenses).
- Results are shown as a simplified **Retirement Financial Estimation chart**: stacked income/expense bars and dual-axis lines, with hover tooltips showing Income Subtotal, Expense Subtotal, Net Saving, and Total Assets for any year. The chart does not include life event markers, a right-click event editor, or the projection details table.
- The chart renders **two Total Assets lines** on the same right axis for direct comparison: a solid orange line for the what-if projection and a dashed blue line for your original plan, so the impact of the rate change is immediately visible.

---

### v1.0.27 — 2026-06-11

**Retirement Tips — two new Expense tips (new)**
- **Healthcare Expense Check** — compares your configured monthly healthcare expense against 2025 national retiree benchmarks (~$500/mo per person for Medicare-age retirees, ~$800/mo for pre-Medicare), scaled for single vs. couple coverage. Flags under-budgeting as Action Needed or Warning, and flags extreme over-budgeting as an Info note.
- **Spending Smile Pattern** — checks whether your retirement expense plan reflects the Blanchett (2014) "spending smile": higher spending in the go-go years (retirement to +10 yrs), tapering in slow-go (+10 to +20 yrs), and lower spending in no-go years (age 80+). Suggests adding ~15% in go-go years and ~10% in no-go years via life events if the pattern is absent.

**Retirement Questions — answers shown immediately on panel open (fix)**
- Previously, navigating to Retirement Questions right after app startup showed a blank panel for ~½ second while the database loaded in the background. Persisted answers are now rendered synchronously from disk as soon as the panel opens, so the panel is never blank.

**Windows installer — release tag derived from pom.xml (fix)**
- The GitHub Actions "Build Windows Installer" workflow previously uploaded the .exe to a hardcoded release tag (`v1.0.15`). It now reads the version from `pom.xml` at build time and uses the correct tag automatically.

**What-If Scenarios — hidden from navigation (chore)**
- The What-If Scenarios menu item is temporarily hidden until the feature is implemented.

---

### v1.0.26 — 2026-06-10

**Retirement Tips — full implementation (new)**
- The Retirement Tips panel now runs a real data-driven scan across 8 personalized tip categories:
  - **Roth Conversion Window** — identifies low-income years between retirement and SS/RMD start where pre-tax funds can be converted at the 12% bracket rate.
  - **Capital Gain Harvesting** — flags projected years where ordinary taxable income falls below the 0% long-term capital gains threshold, enabling tax-free gain realization.
  - **Social Security Timing** — compares your configured SS start age against the longevity-adjusted breakeven for delaying to 70, and flags if delaying would yield more lifetime income.
  - **Sequence-of-Returns Risk Buffer** — checks whether projected cash savings at your retire year cover a 24-month expense buffer to protect against early-retirement market downturns.
  - **Pre-RMD Roth Conversion** — detects a multi-year gap before age-73 RMDs begin and flags large pre-tax balances that could be reduced through Roth conversions.
  - **Medicare IRMAA Cliff** — scans retirement-year projected MAGI against 2025 Part B surcharge thresholds and warns when income is within $10K of a cliff.
  - **Asset Allocation Check** — compares your current stock percentage against the 110-minus-age guideline and flags over- or under-allocation.
  - **Emergency Fund** — checks whether liquid savings cover 3 / 6 / 12 months of projected monthly expenses.
- Each tip is rated **Action Needed**, **Warning**, **Info**, or **No Issues**, and displayed with a headline finding and detailed explanation.
- Tips are sorted by severity (Action → Warning → Info). "No issues" and dismissed tips appear in collapsible sections.
- A **Scan Now** button triggers an immediate re-scan. The scan also runs automatically in the background on app startup if the last scan is more than 30 days old.
- One scan result set is kept per calendar month; re-scanning in the same month overwrites the previous result. Results from prior months are preserved in the database.
- Each tip card has a **Dismiss** button; dismissed tips move to a collapsed section and can be reviewed without cluttering the main view.

---

### v1.0.25 — 2026-06-10

**Retirement Questions — "What is my best Social Security withdrawal strategy?" (new Q3)**
- Clicking **Run Analysis** runs a three-layer Social Security strategy analysis and reveals each result progressively.
- **Analysis 1 — Lifetime Benefit Comparison**: Computes your monthly benefit at age 62, your Full Retirement Age (FRA), and age 70 using IRS reduction/credit rules (5/9% + 5/12% per month early; 8%/yr delayed past FRA). Shows total lifetime SS income to your longevity age for each strategy, calculates breakeven ages between strategies, and recommends the best strategy based on your configured longevity age. Includes a survivor-benefit note if you are the higher earner with a spouse.
- **Analysis 2 — Deterministic Portfolio Impact**: Runs three full projection-engine scenarios — one per SS strategy — holding everything else constant. Compares ending portfolio balances at your longevity age and identifies the strategy that leaves the most wealth.
- **Analysis 3 — Monte Carlo Survival by Strategy (1,500 runs/strategy)**: Runs Monte Carlo simulations for each SS strategy with Gaussian-perturbed annual returns, and reports survival probability for each. Identifies which claiming age gives your portfolio the best odds of surviving to your longevity age.
- Results persist across app restarts, same as Q1 and Q2.

**Retirement Questions UI**
- Added a contact note below the section subtitle: "Please reach out to tutu.retirement.planning@gmail.com if you have other questions you wish to have personalized answers to."

**Cross-restart persistence for all Retirement Questions analysis results**
- Q1, Q2, and Q3 analysis results now survive app quit and reopen. The last result is shown automatically on next launch; clicking **Run Analysis** re-runs and overwrites it.

---

### v1.0.24 — 2026-06-07

**Retirement Questions — "Do I have enough money to retire from today?" (new)**
- Clicking **Run Analysis** now runs a three-layer simulation and reveals each result progressively.
- **Analysis 1 — Income Gap & Rule of 25**: Checks whether your current liquid assets (savings + stocks + retirement accounts) meet the Rule of 25 target (income gap × 25). Only Social Security income already flowing today is counted; future SS is excluded with a "bridge period" note showing how many years until it begins.
- **Analysis 2 — Deterministic Year-by-Year Projection**: Runs the full projection engine with retire year set to today, modeling account growth, RMD rules, IRMAA premiums, life events, and expense inflation. Reports whether the portfolio survives to your longevity age, and if not, the year and age it runs out.
- **Analysis 3 — Monte Carlo Simulation (2,000 runs)**: Runs 2,000 simulations with Gaussian-perturbed annual returns (blended retirement/stock mean, 10% std dev) and reports the survival probability as a percentage with a readiness rating (Strong / Moderate / Risky).
- Each layer shows a **Details** line (numbers and conclusion) and a **Methodology** line (approach and assumptions).
- Simulation results persist across panel refreshes. A "Simulation run on [Date]" note appears at the bottom.

**Retirement Questions — "When can I retire?" (new)**
- Clicking **Run Analysis** runs a three-layer retirement date search, revealing each result progressively.
- **Analysis 1 — SWR Target Check**: Scans your projected wealth year by year (using your configured retire year) to find the earliest year where projected liquid assets × 4% covers the inflation-adjusted income gap — accounting for which year SS becomes available.
- **Analysis 2 — Deterministic Binary Search**: Binary-searches retire years from today to your longevity age (~6 iterations). Each candidate runs the full projection engine; the earliest year where the portfolio never goes negative is returned.
- **Analysis 3 — Monte Carlo Confidence Search (1,000 runs/year)**: Binary-searches retire years using a two-phase Monte Carlo model — deterministic growth + contributions during working years, then Gaussian-perturbed returns during retirement. Returns the earliest retire year with ≥85% survival probability.
- Same persistent results and date note as Q1.

**Retirement Questions UI polish**
- Question titles now show a **Q1** / **Q2** prefix for quick reference.
- The **Run Analysis** button sits on the same line as the question title.
- Each analysis layer formats its answer in three parts: status badge + analysis title, **Details**, and **Methodology**.

---

### v1.0.23 — 2026-06-06

**Medicare Premium as a separate expense line (new)**
- Medicare Part B premium now appears as its own **Medicare Premium** row in the Retirement Estimation — Projection Details table under Expenses, below "Housing Cost (Tax, HOA)".
- Premium is inflation-adjusted year over year using the configured inflation rate.
- IRMAA surcharges are applied automatically: the projected MAGI for each year is compared against the 2025 IRS income brackets (inflation-scaled), and the correct premium tier is used — so high earners pay the appropriate surcharge rather than the base rate.
- Both the primary user's and spouse's Medicare eligibility are tracked independently starting at age 65.

**Order of withdrawal configuration (new)**
- A new "Order of withdrawal" setting has been added to the Retirement Withdrawal step of the wizard, with two choices: **Pre-tax first (default)** and **After-tax first**.
- Pre-tax first: draws from Traditional 401k/IRA accounts first; when depleted, the remainder comes from Roth. RMDs are always enforced regardless of this setting.
- After-tax first: draws RMD from pre-tax accounts (mandatory), then covers the remaining desired withdrawal from Roth, falling back to pre-tax only if Roth is insufficient.
- The choice flows through both the Retirement Estimation projection and the Income and Tax panel.

**IRMAA surcharge in Finance Literacy (new)**
- Added "IRMAA (Medicare Income Surcharge)" term to the Finance Literacy tab, covering the look-back period, 2025 Part B brackets, IRMAA cliff effect, and the Part D surcharge.

**Housing Cost row renamed**
- "Housing Cost" row in the Projection Details expense table renamed to **"Housing Cost (Tax, HOA)"** to clarify that it aggregates property taxes and HOA fees.

**Retirement Planning wizard UI improvements**
- Field labels enlarged from 12 pt to 14 pt and hint/note text from 11 pt to 13 pt for better readability.
- Text fields and dropdowns are now constrained to a maximum width of 400 px — they no longer stretch across the full card width.
- A visual **"Spouse" section divider** is inserted between user fields and spouse-conditional fields in each wizard step, making the two sections clearly distinct. The divider hides automatically when no spouse is configured.

---

### v1.0.22 — 2026-06-05

**Account page (new)**
- Added an "Account" entry to the left navigation menu, above "About". The Account page uses a tabbed layout consistent with the About page.
- **Notification tab** — an in-app mailbox showing all notifications generated by Tutu:
  - Summary bar at the top displays the number of unread and total notifications.
  - Each row shows the notification subject and date side-by-side. Click a row to expand the full message; click again to collapse.
  - Expanding a notification marks it as read, changes its subject from bold to normal weight, and decrements the unread counter immediately.
- **Settings tab** — the existing Settings page is now accessible from Account → Settings. The standalone "Settings" title heading has been removed since the tab label already indicates context.

**About page — Finance Literacy tab (new)**
- "Finance Literacy" has been removed from the left navigation menu. It is now a second tab inside the About page, sitting alongside "About Tutu", so both reference pages are in one place.
- The "About Tutu" title heading and "⚙ Settings" button have been removed from the About page; the tab label replaces the heading and Settings is now reached via Account.
- Page margins are now consistent between the "About Tutu" and "Finance Literacy" tabs (28 px top, 32 px sides).
- Clicking "About" in the left menu always resets the scroll position to the top.
- The "Retirement Finance Literacy" title and subtitle have been removed from the Finance Literacy content; the tab label is sufficient.

**Menu bar notifications badge (new)**
- The Tutu icon in the macOS menu bar (system tray on Windows/Linux) now shows a red dot badge when there are unread notifications.
- The badge is refreshed every 30 seconds. The tooltip updates to show the unread count (e.g. "Tutu  (3 unread)").
- A new **Notifications** item appears in the menu bar popup (between "Open Tutu" and "Quit Tutu"). Clicking it opens the app and navigates directly to Account → Notification.

**Monthly reminder creates in-app notification**
- When the OS-level monthly asset snapshot reminder fires, it now also inserts a notification into the in-app Notification panel, so reminders are visible inside Tutu even if the desktop notification was missed.

---

### v1.0.21 — 2026-06-05

**macOS Menu Bar icon (new)**
- Tutu now installs a persistent icon in the macOS top-right menu bar. The icon stays there for the lifetime of the session and provides a popup menu with two actions: **Open Tutu** (brings the window to front) and **Quit Tutu** (fully exits the app and removes both icons).
- Closing the main window (clicking ×) now hides the window instead of quitting — the app keeps running in the menu bar so you can reopen it instantly without re-launching.
- Clicking the Dock icon when no window is visible reopens the window.
- Dock → Quit hides the window and removes the Dock indicator but keeps the menu bar icon alive. The only way to fully exit is via "Quit Tutu" in the menu bar popup.
- On non-macOS platforms (Windows, Linux) the same icon appears in the system tray with identical behaviour.

**Fix: duplicate Dock icon on every launch from Applications**
- Fixed a bug where Tutu added a new Dock entry on every launch because the existing-entry check compared against the bare path `/Applications/Tutu.app` while macOS stores Dock entries as `file:///Applications/Tutu.app/` (with `file://` scheme, trailing slash, and `_CFURLStringType 15`). The format mismatch caused the check to always fail.
- The fix checks all four plausible URL variants and adds new entries using the correct `file://` format.

**Fix: expense overrides now propagate with inflation**
- Previously, when you customized an expense value for a year, all subsequent years silently fell back to the original config base rather than compounding from your override. Now, the most recent override is used as the new base, and all subsequent years without their own explicit override compound from it using the configured inflation rate.
- This fix applies to both the Retirement Estimation projection and the Expenses panel display.

**Fix: bulk expense dialog now applies inflation growth across the range**
- When double-clicking a cell in the Future Expenses table and using "Bulk update through year", the entered amount is now treated as the value for the selected year and each subsequent year in the range receives that amount compounded by the configured inflation rate. Previously the same flat amount was stored for every year in the range.

**About page — updated TODOs**
- Reorganized and updated the planned features list under three headings: General, Retirement Planning, and Retirement Analysis.

---

### v1.0.20 — 2026-06-03

**Required Minimum Distribution (RMD) enforcement (new)**
- Pre-tax retirement accounts (Traditional 401k, Traditional IRA, SEP IRA, etc.) now enforce the IRS Required Minimum Distribution rule starting at age 73, per the SECURE 2.0 Act.
- The RMD is calculated using the IRS Uniform Lifetime Table: each year's minimum withdrawal = pre-tax account balance ÷ IRS distribution period for that age.
- The RMD floor is enforced regardless of which withdrawal strategy is configured (Fixed, Percentage, or RMD) and regardless of the configured withdrawal start year — if you turn 73, the minimum is always taken.
- After-tax (Roth) accounts are never subject to RMD, consistent with IRS rules.

**Pre-tax vs. After-tax retirement withdrawal split (new)**
- The "401k Withdrawal" row in the Retirement Estimation — Projection Details table is now split into two separate rows: **Pre-Tax Withdrawal** and **After-Tax Withdrawal**, making it clear which withdrawals are taxable and which are not.
- The same split appears in the Income and Tax Projection table: **Pre-Tax Withdrawal** (taxable) and **After-Tax (Roth) Withdrawal** (non-taxable).
- Years with no withdrawal of a given type show "—" to keep the table clean.

**Roth withdrawal tax treatment (new)**
- After-tax (Roth) withdrawals are now correctly excluded from federal taxable income in both the Retirement Estimation and Income and Tax projection panels.
- This affects the Estimated Tax row and the effective tax rate — years when the projection draws from Roth accounts will show lower tax liability.

**Withdrawal order — pre-tax first, Roth when depleted**
- The projection now draws from pre-tax retirement accounts first. When a pre-tax balance reaches zero (for Fixed withdrawal strategies), the remaining configured withdrawal amount automatically falls to the after-tax (Roth) account.
- Emergency drawdown order (when annual savings go negative) is: stock portfolio → Roth accounts → pre-tax Traditional accounts, preserving tax-free Roth assets for as long as possible.

---

### v1.0.19 — 2026-06-02

**Capital gain tracking in retirement projection (new)**
- The retirement estimation now maintains a capital gain bucket throughout the projection. It starts from the total unrealized capital gains entered across all stock holdings and grows each year by the stock portfolio's annual appreciation (`stock value × expected return rate`).
- When the projection needs to sell stock to cover a savings deficit, it calculates the realized capital gain proportionally: `(stock sold ÷ total stock value) × capital gain bucket`. The bucket shrinks by that same amount.
- Realized capital gains appear as a new **Capital Gain** row in the Projection Details income table and are automatically included in the gross income used to compute the Estimated Tax row. Years with no stock sale show "—".
- To take advantage of this, enter the accumulated unrealized gain for each stock holding in the Stock panel's "Unrealized Capital Gain" column.

**macOS Desktop and Dock shortcuts (new)**
- On first launch after install or upgrade, Tutu automatically creates a Finder alias named "Tutu" on the macOS Desktop so users can open the app with a single click.
- Tutu also pins itself to the macOS Dock on first launch if it is not already there.
- Both actions are skipped on subsequent launches and in the development environment.

**Support email updated**
- Support and feedback address changed to tutu.retirement.planning@gmail.com across the app and README.

---

### v1.0.18 — 2026-06-01

**Asset management charts — centred data and hover tooltips (all panels)**
- When fewer than 12 months of data exist, the chart now centres the data in the middle of the 12-month axis with equal empty space on both sides, instead of left-aligning it.
- Hover over any position on a chart to see a dotted vertical crosshair and a tooltip showing the month, per-series values (e.g. Stock, Real Estate, Saving, Retirement for the overview), and Total. Empty padding slots show "—".
- Applies to: Overview (Asset Management), Stock, Real Estate, Saving, and Retirement panels.

**Navigation**
- Added a visual separator line above the Asset Management section in the left menu for clearer section grouping.

**App icon improvements**
- macOS Dock icon is now set programmatically via the Taskbar API so it displays correctly when running from the command line or a development environment.
- Window title bar and taskbar icon now supplies four sizes (16, 32, 48, 256 px) for crisp rendering at all DPI settings.

**Windows installer**
- The Windows desktop shortcut now shows the Tutu icon instead of a generic Java icon.

**Build fix — DMG size regression**
- Fixed a bug where each successive macOS DMG grew by ~15 MB per release due to accumulated fat JARs in the jpackage staging directory. This release is back to ~62 MB (vs 120 MB for v1.0.17).

---

### v1.0.17 — 2026-05-31

**Stock panel redesign**
- Replaced the inline-edit input row with a dialog-based add/edit pattern consistent with Real Estate, Saving, and Retirement panels. Double-click any existing holding to edit it, or double-click the hint row / click "+ Add Stock" to add a new one.
- Added "Unrealized Capital Gain" column to stock holdings — records the accumulated unrealized gain carried into a position for future capital gains tax calculations.
- Added "↻ Refresh Prices" button next to the Holdings title. Fetches the latest previous-close price for all held symbols in parallel from Yahoo Finance, updates each holding's snapshot value, and automatically records the current month's snapshot via the existing DB trigger.
- Fixed stock chart x-axis: months are now shown on the x-axis for all data ranges. Previously, datasets with fewer than 4 months and none falling on Jan/Apr/Jul/Oct showed no x-axis labels at all.

**Monthly snapshot reminder service**
- Tutu now registers an OS-level scheduled task on every launch (production only) that fires at 9 AM on the 1st, 5th, 10th, and 20th of each month.
- On macOS: a launchd plist is written to ~/Library/LaunchAgents/com.tutu.reminder.plist and loaded automatically.
- On Windows: four Task Scheduler entries are created via schtasks.
- When triggered, a lightweight agent (com.tutu.ReminderAgent) opens the local database, checks whether the current month has any asset snapshot, and fires a native desktop notification if not. The reminder fires even when Tutu is not open.
- Reminders stop automatically once a snapshot is recorded for that month.

**Settings page (new)**
- A dedicated Settings page is now accessible via the "⚙ Settings" button on the top-right of the About page.
- Currently hosts one setting: "Monthly Asset Update Reminder" — a pill toggle to enable or disable the reminder service.
- The Reminders toggle has been removed from the navigation panel and consolidated here.

---

### v1.0.16 — 2026-05-30

**Customize Some Planning Configuration (new wizard step)**
- Added a dedicated "Customize Some Planning Configuration" step in the Retirement Planning wizard, positioned between Retirement Withdrawal and Future Expenses.
- Moved "Expected inflation rate (%)" here from the Retirement Timeline step.
- Moved "Expected annual return (%)" here from the Retirement Withdrawal step and renamed it "Expected retirement annual return (%)" for clarity.
- Added "Expected Stock Asset annual return (%)" (default 7.0%) — controls how the stock portfolio grows year over year in all projections.
- Added "Expected Real Estate annual return (%)" (default 4.0%) — controls how real estate value appreciates year over year; previously this was hardcoded to half the inflation rate.

**Projection calculation improvements**
- Retirement accounts (401k/IRA), stock assets, and real estate now each use their own independently configurable annual return rate instead of sharing a single rate.

**README and About page**
- Added a Screenshots section to the README showing all Asset Management and Retirement Planning panels.
- Added a detailed macOS Gatekeeper workaround guide ("I got an installation error on Mac") with three options: right-click open, System Settings, and Terminal xattr command.
- Removed the completed "Support More Life Events" TODO item from both the README and the About page.

---

### v1.0.15 — 2026-05-28

**Annual Expense Projection chart (major enhancement)**
- Replaced the single total-expenses line with a multi-line chart: one colored line per spending category (Housing, Healthcare, Food, Transport, Entertainment, Other) plus a Total line.
- Drag any category data point up or down to instantly adjust the expense value for that year; releasing the mouse commits the change to the table and database.
- Hover tooltip shows the category name, annual value, monthly value (annual ÷ 12), year, and your age at that year.
- Dual Y-axis: category lines scale against the left axis; the Total line has its own right axis rendered in blue.
- Vertical dotted crosshair highlights the hovered year column.

**Finance Literacy new terms**
- Added "Retirement Spending Smile" — David Blanchett's research on how retiree spending follows a U-shaped curve across go-go, slow-go, and no-go phases.
- Added "Backdoor Roth Conversion" — a strategy for high earners to fund a Roth IRA by contributing to a Traditional IRA and converting it.

**Income and Tax projection improvement**
- Standard deduction is now projected at a conservative 2.3 %/yr growth rate (half the 30-year historical CAGR) to account for the outsized 2017 Tax Cuts and Jobs Act jump that inflated the long-run figure.

**About and README updates**
- Feature list updated to include Expenses, the Retirement Analysis suite (Retirement Questions, What-If, Retirement Tips), and Finance Literacy.
- TODO list updated: renamed "Projection Improvements" to "Retirement Analysis", added capital gain tax item, added "basic personalized Q&A" item.

---

### v1.0.13 — 2026-05-25

**Future Expenses panel (new)**
- Added "Expenses" sub-menu under Retirement Planning in the sidebar.
- Year-by-year table showing inflation-adjusted annual expenses for Housing, Healthcare, Food, Transport, Entertainment, and Other.
- Two read-only rows at the top of the table display your age (and spouse's age if configured) for each projected year — making it easy to spot which year to customize.
- Double-click any expense cell to open an edit dialog with annual and monthly amount fields that auto-sync with each other (edit one, the other updates instantly).
- "Bulk update through year" dropdown in the edit dialog labels each year with ages (e.g. "2035 — Me 52, Spouse 50") so you know exactly what life stage you are customizing for.
- Overridden cells are highlighted in blue; "Reset to Defaults" button clears all overrides.
- Expense overrides feed directly into the Living Expenses row in Retirement Financial Estimation.
- A note below the table reminds users to use Life Events for one-time costs (tuition, mortgage payoff, etc.) rather than this panel.

**Retirement Finance Literacy panel (new)**
- Added "Finance Literacy" nav item above About in the sidebar.
- 16 financial and retirement concepts explained in plain language, in alphabetical order: 401(k)/403(b), Capital Gain, Compound Interest, Inflation, Medicare, Mortgage, Net Worth, Property Tax, RMD, Retirement Plans & Contributions, Roth IRA & Roth IRA Conversion, Sequence of Returns Risk, Social Security, Tax Brackets, Traditional IRA, and Withdrawal Rate.

**Dark Mode toggle redesigned**
- Replaced the small icon-only toggle with a full-width row showing a pill-style switch and a "Dark Mode" label — making its purpose immediately clear.

**Light mode bug fixes**
- Cancel button in the "Add / Edit Retirement Plan" dialog no longer shows a dark background in light mode.
- Mouse-over of type-selection, Cancel, and Back buttons in the "Add Life Event" dialog now uses the correct theme-aware hover color in both light and dark modes.

**Projection Details table**
- Renamed "Monthly Rental" row to "Rental" — the value has always been the annual figure.

**Windows installer (new)**
- Starting with this release, a Windows installer (`Tutu-1.0.13-Windows.exe`) is provided alongside the macOS disk image (`Tutu-1.0.13-macOS.dmg`).
- Binary filenames now include the OS to avoid ambiguity.

---

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

### 1. Retirement Analysis
- Add a what-if scenario feature to explore alternatives without changing existing planning
