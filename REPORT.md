# MIS15 Vibe Coding Final Report

# SpendWise

**Deconstructing the hidden costs of the service economy.**

## Description

SpendWise is a financial transparency dashboard that helps users catalog purchases and understand their spending habits. Users can manually enter purchases or upload receipts, and the app provides insights such as total spending, tip percentage, taxes, fees, friction costs, recurring costs, frequent vendors, and monthly spending trends.

## The Pitch

We have all experienced **receipt blindness**. We know the final total we paid, but we often lose track of the extra costs that slowly add up, such as tips, taxes, service fees, delivery fees, and gratuity.

We built SpendWise to give students, young adults, and professionals more financial transparency. It is not just a regular spending tracker. It is a tool that highlights the hidden costs of modern spending that are usually buried inside receipts and transaction totals.

SpendWise helps users understand not only where their money is going, but also how much extra they are paying above the base price of goods and services.

## The Problem

In a service-heavy economy, the “base price” is often not the final price. Between taxes, tips, delivery fees, service charges, and other extra costs, consumers are often unaware of how much they are actually paying beyond the original price of an item.

SpendWise solves this information gap by breaking purchases into clearer parts. Instead of only showing the final transaction amount, the app separates the base price from **friction costs**, which include tips, gratuity, taxes, and fees.

This helps users make better financial decisions because they can see patterns that are normally hidden inside receipts.

## Target User

SpendWise is designed for students, young adults, and gig-economy consumers who want a simple way to audit their spending habits without the complexity of a full accounting or budgeting app.

Our target user is someone who wants to understand where their money is going, especially when small extra charges begin to add up over time.

## Why SpendWise Is Unique

SpendWise is unique because it focuses on **how much extra** users are paying, not just where they are spending.

Many finance apps focus on broad categories like food, shopping, bills, or transportation. SpendWise focuses specifically on the hidden “last-mile” costs of modern spending, such as:

- tips and gratuity
- taxes
- service fees
- delivery fees
- recurring small purchases
- extra charges above the base price

This makes SpendWise a specialized tool for users who want to understand the real cost behind their purchases.

## What the App Does

SpendWise allows users to manually log a purchase or upload a receipt.

When a purchase is added, the app organizes the data into categories such as:

- base price
- tip or gratuity
- taxes
- service fees
- total amount
- vendor
- category
- payment method
- purchase channel
- purchase date

The dashboard then turns this information into insights. Instead of only showing a total purchase amount, SpendWise shows how much of that total came from friction costs.

For example, the app can show how much a user spent on gratuity, taxes, and fees during a selected month. It can also show frequent vendors, recurring costs, and monthly spending trends.

## App Screenshots

### Dashboard View

Add a screenshot of the main SpendWise dashboard here.

```markdown
![SpendWise Dashboard](screenshots/dashboard.png)
```

The dashboard shows monthly spending, budget progress, purchase count, base prices versus extras, gratuity spend, taxes and fees, recurring costs, and frequent vendor insights.

### Search and Purchase Library

Add a screenshot of the Search screen here.

```markdown
![SpendWise Search Screen](screenshots/search.png)
```

The Search screen allows users to search saved purchases and filter by item, category, store, amount, channel, payment method, and amount range.

### Receipt Upload or Add Purchase Screen

Add a screenshot of the add purchase or receipt upload screen here.

```markdown
![SpendWise Add Purchase](screenshots/add-purchase.png)
```

This screen shows how users can add new purchase data to the app.

## Example App Data

Example dashboard data for May 2026:

```text
Monthly Spending: $450.36
Budget: $2,000
Budget Used: 23%
Number of Purchases: 10
```

Example cost breakdown:

```text
Base Prices: $403.49
Friction Costs / Extras: $46.87
```

Example saved purchase:

```text
Purchase: Cold brew
Store: Blue Bottle
Category: Coffee
Payment Method: Debit
Date: May 12
Amount: $5.75
Extras: $0.75
```

This example shows that SpendWise can catalog purchases, separate base costs from friction costs, track tips, taxes, and fees, identify frequent vendors, search purchases, and summarize monthly spending trends in a dashboard format.

## How We Built It

We built SpendWise in Replit using vibe coding tools. We started with a high-level idea and used AI to generate the first version of the app. After that, we tested the app, reviewed the interface, and used more specific prompts to refine it.

The project followed the vibe coding lifecycle:

1. **Ideation**: We created the idea for a finance dashboard focused on hidden costs.
2. **Generation**: We used AI tools to generate the first working version.
3. **Iterative Refinement**: We tested the app and improved the dashboard, receipt upload, and search features.
4. **Testing and Validation**: We checked the app’s outputs, filters, and receipt data flow.
5. **Deployment**: We prepared the app in Replit and documented it with a README and report.

The first version gave us a starting point, but the real work was refining the app so that it told a clearer financial story.

## Initial Prompt

Our initial prompt was similar to this:

```text
Create an app called SpendWise.

SpendWise should be a financial transparency dashboard that lets users manually enter purchases or upload receipts. The app should catalog purchase information and show insights about spending, including total spending, tips, gratuity percentage, taxes, fees, monthly spending trends, recurring costs, and frequent vendors.

The app should have a clean dashboard interface and make it easy for users to understand how much they are paying above the base price of their purchases.
```

## Vibe Coding Refinements

| Prompt / Refinement | Why We Sent It | Result |
|---|---|---|
| “Build a finance dashboard called SpendWise that tracks purchases, tips, taxes, fees, and monthly spending trends.” | We needed a first working version of the app based on our main idea. | The AI generated the foundation of the dashboard and purchase tracking system. |
| “Separate base purchase prices from tips, taxes, and fees.” | The first version focused too much on total spending. Our app needed to expose hidden costs. | SpendWise became more focused on friction costs instead of only transaction totals. |
| “Add a dashboard card for Total Purchases vs. Extras.” | We wanted users to quickly compare normal purchase costs against extra costs. | The dashboard became more visual and easier to understand. |
| “Add receipt upload so users can scan a receipt instead of typing everything manually.” | Manual entry is useful, but receipt upload makes the app faster and more realistic. | The app gained a smarter input method for purchase data. |
| “Make the app extract receipt details like vendor, item, base price, gratuity, taxes, and fees.” | We needed receipt uploads to produce organized data, not just a generic AI response. | The receipt feature became connected to the dashboard’s financial logic. |
| “Add search and filters for saved purchases.” | Users need to review past purchases by item, store, amount, channel, or payment method. | The app became more useful as a purchase library, not just a dashboard. |
| “Show recurring costs and frequent vendors.” | We wanted the dashboard to reveal spending habits over time. | SpendWise started giving more meaningful long-term insights. |
| “Improve the README so another person can understand the app.” | The professor wanted documentation inside the app. | The README became a technical cover page for the project. |

## Data Used

SpendWise uses purchase data provided by the user through manual entry or receipt uploads.

The app may use data such as:

| Data | Source | Purpose |
|---|---|---|
| Vendor/store | User input or receipt upload | Identifies where the purchase happened |
| Item or purchase name | User input or receipt upload | Describes what was purchased |
| Base price | User input or receipt upload | Shows the original cost before extras |
| Tip/gratuity | User input or receipt upload | Calculates gratuity spend |
| Taxes and fees | User input or receipt upload | Tracks extra costs |
| Total amount | Entered or calculated | Shows the full purchase cost |
| Category | User input or app logic | Organizes purchases |
| Channel | User input or receipt data | Shows in-person or online purchase type |
| Payment method | User input or receipt data | Helps filter transactions |
| Date | User input or receipt data | Used for monthly spending trends |

## App Logic and Data Flow

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

The app logic separates each purchase into two major parts:

1. **Base Price**: the original cost of the item or service.
2. **Friction Costs**: extra costs such as tips, gratuity, taxes, and service fees.

This lets the dashboard calculate insights such as total spending, tip percentage, taxes and fees, recurring costs, frequent vendors, and monthly trends.

## Code and Technical Explanation

This section explains the main parts of the app’s code and how they support the user experience.

| App Section / File | What It Does | Why It Matters |
|---|---|---|
| Dashboard interface | Displays monthly spending, budget progress, purchase insights, and visual cards | Helps users quickly understand their spending |
| Purchase data route | Stores or retrieves purchase information | Allows the app to catalog purchases |
| Receipt upload route | Processes uploaded receipt files | Makes it easier for users to add purchase data |
| Search screen | Lets users search and filter saved purchases | Helps users review their spending history |
| Calculation logic | Separates base price from tips, taxes, and fees | Creates the main financial insights of the app |

### Example Logic Explanation

The most important calculation in SpendWise is separating the base purchase amount from the extra costs.

```text
Friction Costs = Tips + Taxes + Fees
Total Purchase = Base Price + Friction Costs
```

This matters because most banking apps only show the final total. SpendWise breaks the total into smaller parts so users can see how much they paid above the base price.

### Optional Code Screenshot

Add a screenshot of the code section that calculates totals, tips, taxes, or fees.

```markdown
![SpendWise Code Example](screenshots/code-example.png)
```

In the presentation, this code can be explained as the part of the app that turns raw purchase data into dashboard insights.

## API and AI Information

SpendWise does not require a public banking or finance API for the basic dashboard. The main financial data comes from user-entered purchases and uploaded receipts.

The app includes an AI-powered receipt scanning feature. When a user uploads a receipt, the app can process the file and extract structured purchase information such as vendor, item, base price, gratuity, taxes, fees, category, payment method, and date.

This AI feature is used to make receipt entry faster. The purpose of the AI is not to give a generic response, but to help turn receipt data into organized purchase data for the dashboard.

## Testing and Validation

We tested SpendWise with different types of inputs and user actions.

| Test Case | Input or Action | Expected Result | Result |
|---|---|---|---|
| View dashboard | Open dashboard screen | Monthly spending and insight cards display | Passed |
| Add manual purchase | Enter purchase details | Purchase appears in spending data | Passed |
| Receipt upload | Upload a receipt | App extracts or catalogs receipt information | Passed / Partially passed |
| Search purchase | Search for a store or item | Matching purchases appear | Passed |
| Filter by channel | Select online or in-person | Purchase list filters correctly | Passed |
| Filter by payment method | Select payment method | Purchase list updates | Passed |
| Amount range filter | Set minimum and maximum amount | Purchases within range display | Passed |
| Missing or invalid data | Leave required fields blank or enter bad data | App should prevent or correct bad data | Passed / Needs refinement |

Testing helped us understand that the dashboard needed clear labels, the receipt upload needed review/confirmation, and the search tools needed to be easy to use.

## Team Responsibilities

Our group worked together, but we divided responsibilities.

**Sabal Dhoj Adhikary** focused on:

- app idea and problem statement
- dashboard concept
- prompt refinement
- testing app flow
- presentation preparation

**Aaliyah Minnie** focused on:

- app building in Replit
- README documentation
- testing features
- report writing
- checking the final demo

Both members helped review the final app and made sure we understood how SpendWise works from start to finish.

## Lessons Learned

Both of our team members learned valuable lessons while creating SpendWise.

One major lesson was the importance of the phrase **“less is more.”** During the design process, we realized that some features could confuse or overwhelm users. Instead of trying to include everything, we simplified the app and focused on the features that best supported our main idea: helping users understand hidden costs.

We also learned that communication and planning are important. Throughout the project, we discussed what we wanted to add, what we wanted to remove, and what we wanted the dashboard to show before making changes. Getting some parts done early helped reduce stress later in the project.

Another lesson was that AI can create a first version quickly, but it still needs human direction. Specific prompts worked better than vague prompts. For example, asking the AI to “separate base prices from tips, taxes, and fees” was more useful than simply asking it to “make the dashboard better.”

Finally, the app itself helped us think more carefully about spending. Even small purchases can become expensive when tips, taxes, and fees are added. SpendWise reminded us that financial awareness is not only about large expenses, but also about the small charges that add up over time.

## Future Improvements

In the future, SpendWise could be improved by adding:

- stronger validation for unusual or unrealistic purchase values
- more detailed charts for monthly comparisons
- better receipt scanning accuracy
- user accounts for saving personal spending history
- export options for monthly reports
- optional bank or card syncing
- clearer budget goal tracking

## Project Links

- [Replit App](https://spend-wise-sabaladhikary-aaliyahminnie.replit.app/)
- [GitHub Repository](https://github.com/SabalAdhikary-web/SpendWise)
- [README](README.md)
