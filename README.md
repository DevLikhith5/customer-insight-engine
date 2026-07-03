# Customer Insight Engine

A complete analytics project that uncovers patterns, segments, and trends in retail customer shopping behavior. Combines SQL, Python, Power BI, and executive reporting in one workflow.

---

## Overview

This project takes raw customer purchase data and turns it into actionable insight across the full analytics stack:

- **SQL** for querying and aggregating transactional data
- **Python (pandas / matplotlib / seaborn)** for exploration and statistical analysis
- **Power BI** for an interactive business dashboard
- **PDF report + PPTX deck** for stakeholder-ready storytelling

The goal: identify who the customers are, what they buy, when they buy it, and how to grow revenue and retention.

---

## Tech Stack

| Layer        | Tool                        |
| ------------ | --------------------------- |
| Data         | CSV (412K records)          |
| Querying     | SQL                         |
| Analysis     | Python, Jupyter Notebook    |
| Visualization| Power BI                    |
| Reporting    | PDF + PowerPoint            |

---

## Project Structure

```
.
├── README.md
├── .gitignore
├── customer_shopping_behavior.csv              # raw dataset
├── customer_behavior_sql_queries.sql            # SQL analysis queries
├── Customer_Shopping_Behavior_Analysis.ipynb    # Python exploration
├── customer_behavior_dashboard.pbix             # Power BI dashboard
├── Customer Shopping Behavior Analysis.pdf      # written report
├── Customer-Shopping-Behavior-Analysis.pptx     # slide deck
└── Business Problem  Document.pdf               # problem statement
```

---

## Getting Started

### 1. Explore the data
Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter or VS Code to walk through the EDA and feature engineering steps.

### 2. Run the SQL queries
Load `customer_shopping_behavior.csv` into your database of choice (PostgreSQL, MySQL, SQLite), then run the queries in `customer_behavior_sql_queries.sql`.

### 3. Open the dashboard
Launch `customer_behavior_dashboard.pbix` in Power BI Desktop and connect it to the CSV (or your DB) to explore the visuals interactively.

### 4. Review the findings
- `Customer Shopping Behavior Analysis.pdf` — full written analysis
- `Customer-Shopping-Behavior-Analysis.pptx` — executive summary deck
- `Business Problem  Document.pdf` — original problem framing

---

## Key Analysis Areas

- Customer segmentation by demographics and spend
- Product category performance and seasonality
- Purchase frequency, recency, and basket size
- Discount sensitivity and promotional impact
- Subscription vs. one-time buyer behavior
- Customer satisfaction (review ratings) drivers

---

## License

This project is for analytical and educational purposes. Adapt freely.
