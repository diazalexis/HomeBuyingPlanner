# Home Buying Planner

A focused, browser-based planner for modeling the financial path to buying a home. It brings purchase price inputs, mortgage assumptions, cash-to-close, monthly budget impact, and a customizable cash runway into one static page.

## Live Page

[Open the Home Buying Planner](https://diazalexis.github.io/HomeBuyingPlanner/)

## What It Does

- Calculates total purchase price from base price, homesite premium, structural options, and design budget.
- Models down payment, loan amount, monthly principal and interest, PMI, property taxes, insurance, HOA, and estimated PITIA.
- Tracks builder or lender incentives, including buydown allocation, closing-cost credit, and unused incentive amount.
- Estimates contract deposit, design deposit, cash to close, and remaining cash buffer.
- Includes a monthly household budget section for net income, fixed expenses, flexible expenses, and available savings.
- Builds a monthly cash runway from a selected starting month through closing.
- Lets runway rows be adjusted directly with editable event labels, housing costs, and ending balances.
- Exports and imports planner state as JSON, including runway overrides and generated rows.

## Why It Exists

Buying a home involves many numbers that change over time: incentives, rates, deposits, design selections, closing costs, savings, and timing. This planner is designed to keep those assumptions visible and easy to update without needing a spreadsheet.

The cash runway is especially useful when the timing of payments changes. For example, if a design deposit moves to a later month, the row-level housing cost can be adjusted while the main purchase model remains intact.

## How To Use It

1. Open the live page.
2. Enter the purchase, loan, incentive, cash, and monthly cost assumptions.
3. Review the calculated payment, cash-to-close, deposits, and buffer.
4. Choose the runway starting month and months to closing.
5. Edit runway events, housing costs, or ending balances as real timing replaces estimates.
6. Export JSON whenever you want to save a snapshot.
7. Import a saved JSON file to restore a previous plan.

## Project Structure

This is intentionally simple:

```text
index.html
README.md
```

No build step, package install, or server is required for local use. Open `index.html` directly in a browser.

## Notes

This planner is for personal planning and scenario modeling. It is not financial, legal, tax, or lending advice. Replace estimates with lender-provided numbers as they become available.
