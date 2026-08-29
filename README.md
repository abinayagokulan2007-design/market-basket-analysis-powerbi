#  Market Basket Analysis in a Supermarket 

##  Project Overview

This project performs Market Basket Analysis on supermarket transaction-level data to discover associations between products. The analysis helps identify frequently purchased product combinations and supports the development of cross-selling strategies, product bundles, and promotional offers.

The project is developed using Power BI and provides an interactive dashboard for analyzing customer purchasing patterns and product relationships.

---

##  Project Objectives

- Analyze supermarket transaction data.
- Identify the most frequently purchased products.
- Discover associations between products.
- Calculate important association rule metrics such as Support, Confidence, and Lift.
- Identify potential cross-selling opportunities.
- Provide data-driven recommendations for product bundling and promotional strategies.

---

##  Business Problem

Supermarkets contain thousands of products, making it difficult to identify which products customers frequently purchase together.

This project uses Market Basket Analysis to discover hidden relationships between products and help businesses:

- Improve cross-selling strategies.
- Create effective product bundles.
- Design targeted promotional offers.
- Improve product placement decisions.

---

##  Dashboard Features

The Power BI dashboard includes:

-  Total Transactions
-  Unique Customers
-  Unique Products
-  Average Basket Size
-  Total Items Purchased
-  Top 10 Most Purchased Products
-  Product Association Rules
-  Top 5 Product Purchase Share
-  Association Strength: Confidence vs Lift
-  Top Cross-Sell Associations by Purchase Frequency
-  Product Association Explorer

##  Market Basket Analysis Metrics

### Support

Support measures how frequently a product combination occurs in all transactions.

**Formula:**

Support = Transactions containing Product A and Product B / Total Transactions

### Confidence

Confidence measures how often Product B is purchased when Product A is purchased.

**Formula:**

Confidence(A → B) = Transactions containing A and B / Transactions containing A


### Lift

Lift measures the strength of the relationship between two products.

**Formula:**

Lift(A → B) = Confidence(A → B) / Support(Product B)

### Interpretation of Lift

- **Lift > 1** → Positive association between products.
- **Lift = 1** → No significant association.
- **Lift < 1** → Negative association.

##  Key Dashboard Visualizations

### Top 10 Most Purchased Products

Identifies the products with the highest purchase frequency.

###  Product Purchase Share

Shows the distribution of purchases among the top products.

###  Product Association Rules

Displays relationships between products using:

- Support
- Confidence
- Lift
- Pair Frequency

###  Confidence vs Lift Analysis

Helps identify strong product associations and potential cross-selling opportunities.

###  Cross-Sell Associations

Highlights frequently occurring product combinations that can be used for cross-selling strategies.

###  Product Association Explorer

Allows users to explore relationships between Product A and Product B interactively.

---

##  Business Insights

The analysis helps identify:

- Frequently purchased products.
- Strong product relationships.
- Potential cross-selling opportunities.
- Product combinations suitable for promotional bundles.
- Customer purchasing patterns.

---

##  Business Recommendations

Based on the Market Basket Analysis, supermarkets can:

- Create product bundles using frequently associated products.
- Recommend related products to customers.
- Place associated products strategically within the supermarket.
- Offer targeted discounts on complementary products.
- Use strong association rules for cross-selling campaigns.

---

##  Tools and Technologies Used

- **Power BI** – Dashboard development and visualization.
- **Power Query** – Data transformation and preprocessing.
- **DAX** – Calculated measures and business metrics.
- **Market Basket Analysis** – Association rule analysis.

---
## Author ##

**Abinaya G**

---

##  Project Structure

market-basket-analysis-powerbi/
├── Market Basket Analysis Dashboard.pbix
├── Groceries_raw.csv
├── Dashboard.png
└── README.md
