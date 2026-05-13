# SpendWise 

**Deconstructing the hidden costs of the service economy.**

## What the App Does

SpendWise is a financial transparency dashboard that turns raw purchases and receipts into clear spending insights.

## The Problem It Solves

SpendWise helps users understand the hidden costs inside everyday purchases, such as tips, taxes, service fees, delivery fees, and other extra charges.

## Why It Is Unique

SpendWise is unique because it focuses on how much extra users are paying above the base price, not just where they are spending.

## Target User

SpendWise is designed for students, young adults, and gig-economy consumers who want a simple way to audit their spending habits without the complexity of a full-scale accounting or budgeting app.

## How to Use SpendWise

1. Start on the **Dashboard** screen.
2. Review the selected month at the top of the dashboard.
3. Use the month arrows to move between months.
4. Review the **Monthly Spending** card to see total spending, budget progress, and purchase count.
5. Review **Total Purchases vs. Extras** to compare base purchase prices against extra costs such as tips, taxes, and fees.
6. Use the summary cards to view insights such as gratuity spend, taxes and fees, spending trends, recurring costs, and frequent vendors.
7. Tap the **plus (+)** button to add a new purchase or upload a receipt.
8. Use the **Search** tab to search and filter saved purchases.

## Example App Data

Example dashboard data:

```text
Monthly Spending: $450.36
Base Prices: $403.49
Friction Costs / Extras: $46.87
```

This example shows that SpendWise separates regular purchase costs from extra costs like tips, taxes, and fees.

## Data Used

SpendWise uses purchase data provided by the user through manual entry or receipt uploads. This includes details such as vendor, price, tips, taxes, fees, payment method, date, and category.

## App Logic

SpendWise follows this basic data flow:

```text
User enters purchase or uploads receipt
        ↓
App reads purchase details
        ↓
App checks for missing or invalid information
        ↓
App catalogs the purchase
        ↓
App separates base costs from friction costs
        ↓
App calculates totals, tips, taxes, fees, and trends
        ↓
Dashboard displays spending insights
```

## API and AI Information

SpendWise does not require a public banking or finance API for the basic dashboard. The main financial data comes from user-entered purchases and uploaded receipts.

The app includes an AI-powered receipt scanning feature that helps extract structured purchase information from uploaded receipts.

## Features

- Financial transparency dashboard
- Manual purchase entry
- Receipt upload option
- Purchase library and search
- Monthly spending summary
- Base purchase vs. extras comparison
- Tip/gratuity tracking
- Tax and fee tracking
- Recurring cost insight
- Frequent vendor insight
- Spending trend summary

## Team Members

- Sabal Dhoj Adhikary
- Aaliyah Minnie

## Project Links

- [Replit App](https://spend-wise-sabaladhikary-aaliyahminnie.replit.app/)
- [GitHub Repository](https://github.com/SabalAdhikary-web/SpendWise)
- [Final Report](REPORT.md)
