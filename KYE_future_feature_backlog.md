# KnowYourExpenses — Feature Backlog

---

## 1. Month-on-Month Trend Analysis
**Status:** Waiting on data (build after ~6 months of records)

- Per-category spending across last 6 months
- Visual bar or line chart per category
- % change indicators (vs last month and vs 6-month average)
- Goal: surface trends like fuel creeping up, bills rising, etc.
- Categories: Food, Transport/Fuel, Bills, Shopping, Health, Entertainment, Travel, Other

---

## 2. Portfolio / Net Worth Tracker
**Status:** Ready to build

- New tab inside the same app (same HTML file, localStorage)
- **Asset classes:**
  - Crypto (BTC, ETH, USDT, etc.) — live USD price, converted to PKR
  - Gold — in **Tolas** (Pakistani standard), live PKR rate
  - Mutual Funds — manual NAV / value entry
  - Property — manual PKR value
  - Cash (PKR) — manual entry
- **How it works:**
  - First-time entry: add asset with quantity (e.g. 0.5 BTC, 10 Tolas)
  - Further additions work like expense entries
  - Live prices fetched on tab open for Crypto and Gold
  - Total net worth displayed at top in PKR
  - Each category shown as card with current value + % of total portfolio
