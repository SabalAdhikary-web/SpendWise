# SpendWise 

**Deconstructing the hidden costs of the service economy.**

## What the App Does

SpendWise is a financial transparency dashboard that turns raw purchases and receipts into clear spending insights.

Unlike standard banking apps that only show a total transaction amount, SpendWise deconstructs **Friction Costs** — tips, gratuity, taxes, service fees, and other extra charges — to show users exactly how much they are paying above the base price of their goods and services.

The app helps users catalog purchases, search through spending history, and view dashboard insights such as monthly spending, tip percentages, taxes, fees, recurring costs, frequent vendors, and spending trends.

## The Problem It Solves

Most consumers suffer from **Receipt Blindness**. We focus on the final total but lose track of the cumulative impact of tips, taxes, service fees, delivery fees, and other hidden costs.

SpendWise solves this information gap by providing a more detailed look at the data behind each receipt. Instead of only showing what the user spent, SpendWise shows how much of that spending came from the base purchase and how much came from extra costs.

This helps users better understand their discretionary spending and recognize patterns that are usually hidden inside everyday transactions.

## Why It Is Unique

SpendWise is unique because it focuses on **how much extra** users are paying, not just where they are spending.

While many finance apps focus on broad categories like food, shopping, or transportation, SpendWise specifically targets the “last-mile” costs of the modern service economy, such as:

- tips and gratuity
- taxes
- service fees
- delivery fees
- extra charges
- recurring small purchases

This makes SpendWise a specialized tool for users who want to understand the real cost behind their purchases.

## Target User

SpendWise is designed for students, young adults, and gig-economy consumers who want a simple way to audit their spending habits without the complexity of a full-scale accounting or budgeting app.

The target user is someone who wants to understand where their money is going, especially when small extra charges begin to add up over time.

## How to Use SpendWise

1. Start on the **Dashboard** screen.
2. Review the selected month at the top of the dashboard. In the example, the dashboard is showing **May 2026**.
3. Use the left and right arrows near the month to move between months.
4. Review the **Monthly Spending** card to see:
   - total amount spent,
   - budget progress,
   - number of purchases for the month.
5. Review the **Total Purchases vs. Extras** section to compare:
   - base purchase prices,
   - extra costs such as tips, taxes, and fees.
6. Use the summary cards to view specific insights, including:
   - gratuity spend,
   - taxes and fees,
   - spending trend,
   - recurring costs,
   - frequent vendor,
   - last uploaded receipt or purchase.
7. Tap the **plus (+)** button at the bottom of the app to add a new purchase or upload a receipt.
8. Use the **Search** tab to search through saved purchases.
9. On the Search screen, filter purchases by:
   - item, category, store, or amount,
   - channel, such as in-person or online,
   - payment method,
   - minimum and maximum amount range.
10. Review purchases from the list to see the purchase amount and extra costs.

## Example App Data and Output

The dashboard example shows spending data for **May 2026**.

```text
Monthly Spending: $450.36
Budget: $2,000
Budget Used: 23%
Number of Purchases: 10
```

The app also separates regular purchase costs from extra costs:

```text
Base Prices: $403.49
Friction Costs / Extras: $46.87
```

Example purchase shown in the search library:

```text
Purchase: Cold brew
Store: Blue Bottle
Category: Coffee
Payment Method: Debit
Date: May 12
Amount: $5.75
Extras: $0.75
```

Example dashboard insights:

```text
Gratuity Spend: 4% / $16.15
Taxes & Fees: 7% / $30.72
Spending Trend: +7732% vs last month
Recurring Costs: 1 repeated item
Frequent Vendor: Trader Joe's
Last Upload: $5.75, 1 day ago
```

## What This Example Shows

This example shows that SpendWise can catalog purchases, separate base costs from friction costs, track tips, taxes, and fees, identify frequent vendors, search purchases, and summarize monthly spending trends in a dashboard format.

## Data Used

SpendWise uses purchase data provided by the user. This may come from manual purchase entry or uploaded receipts.

The app may use data such as:

- purchase name
- store or vendor
- purchase category
- subtotal or base price
- tip or gratuity
- tax
- service fees
- total amount
- payment method
- purchase channel, such as in person or online
- purchase date
- receipt upload information

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

The app uses logic to organize purchases, calculate extra costs, measure gratuity percentage, total taxes and fees, identify frequent vendors, and summarize monthly spending trends.

## API and AI Information

SpendWise does not require a public banking or finance API for the basic dashboard. The main financial data comes from user entered purchases and uploaded receipts.

The app does use an AI powered receipt scanning feature for uploaded receipts. When a user uploads a receipt, the app processes the file and extracts structured purchase information such as vendor, item, base price, gratuity, taxes, fees, category, payment method, and date.

This AI feature is used to make receipt entry faster, but the user still needs to review the information. The purpose of the AI is not to give a generic response, but to help turn receipt data into organized purchase data for the dashboard.

If future versions are expanded, an API could be added for features such as automatic bank syncing, receipt scanning, or vendor data. For this version, the focus is on user provided purchase data and clear financial insights.

## Features

- Financial transparency dashboard
- Manual purchase entry
- Receipt upload option
- Purchase library and search
- Channel filters for in-person and online purchases
- Payment method filters
- Amount range filters
- Monthly spending summary
- Base purchase vs. extras comparison
- Tip/gratuity tracking
- Tax and fee tracking
- Recurring cost insight
- Frequent vendor insight
- Spending trend summary
- Clear visual dashboard

## Team Members

- Sabal Dhoj Adhikary
- Aaliyah Minnie

## Project Links

- Replit App: (https://spend-wise-sabaladhikary-aaliyahminnie.replit.app/)
- GitHub Repository: (https://github.com/SabalAdhikary-web/SpendWise)
