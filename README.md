# 💳 Credit Card Analytics Dashboard

An interactive Power BI dashboard analyzing credit card transaction and customer data — covering revenue, spending behavior, and customer demographics to surface actionable business insights.

## 📊 Dashboard Preview

### Transaction Report
![Credit Card Transaction Report](assets/dashboard-screenshots/transaction-report.png)
*Revenue, transaction volume, and interest breakdown by card category, expenditure type, education level, customer job, and quarter*

### Customer Report
![Credit Card Customer Report](assets/dashboard-screenshots/customer-report.png)
*Customer-level insights across age group, income, marital status, dependents, education, and top-performing states*

## 🔍 Key Insights

- **Total Revenue:** 55M | **Total Interest Earned:** 7.84M | **Total Transactions:** 656K | **Customer Income:** 576M
- **Blue** card holders drive the majority of revenue (46M), followed by **Silver** (6M), while **Platinum** and **Gold** contribute the least despite being premium tiers
- **Swipe** transactions account for the largest share of spend (35M), well ahead of Chip (17M) and Online (3M)
- **Bills, Entertainment, and Fuel** are the top spending categories among cardholders
- Revenue is concentrated in the **40–60 age group**, with the **Graduate** education segment contributing the most (22M)
- **Businessman** and **White-collar** customer segments generate the highest revenue among job categories
- **Texas, New York, and California** are the top revenue-generating states
- Revenue trends by week show noticeable seasonal fluctuation across 2023

## 🛠️ Tools & Tech Stack

- **Power BI** — dashboard design, DAX measures, and data visualization
- **Data Source:** Credit card transaction and customer dataset (CSV/SQL)
- **Filters/Slicers:** Card category, quarter, gender, income level, transaction type, week

## 📁 Repository Structure

```
credit-card-analytics-dashboard/
├── assets/
│   └── dashboard-screenshots/
│       ├── transaction-report.png
│       └── customer-report.png
├── data/
│   └── (dataset used for the dashboard)
├── credit-card-dashboard.pbix
└── README.md
```

## 🚀 How to View

1. Clone this repository
2. Open `credit-card-dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Explore the interactive filters (card category, quarter, gender, income group, etc.) to drill into specific segments

## 📌 About

This project was built to practice data analytics and business intelligence skills — transforming raw transaction data into an interactive dashboard that highlights revenue drivers, customer segments, and spending patterns for a fictional credit card portfolio.
