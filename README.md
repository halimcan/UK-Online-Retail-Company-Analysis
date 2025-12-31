## E-Retail Customer & Revenue Analytics

Python · SQL · BigQuery · Power BI

## Project Overview

This project focuses on understanding customer value, revenue concentration, and churn risk in an e-retail business using transactional data.

The goal is not only to analyze historical performance, but to translate customer analytics into actionable business decisions for:

revenue growth

customer retention

marketing budget allocation

The analysis combines customer segmentation, CLV estimation, and business-oriented insights, delivered through interactive Power BI dashboards.

## Business Questions

This project answers the following key business questions:

Which customer segments drive the majority of revenue?

How concentrated is revenue across customers (VIP dependency)?

Which customers are at risk of churn, and how much revenue is at risk?

Where should the company focus retention, win-back, and cross-sell efforts?

## Key Insights
# Customer Value Distribution

Average CLV: £42,105

Median CLV: £28,712 → indicates a right-skewed distribution

A small group of VIP customers generates a disproportionate share of total revenue

 Insight: Revenue is highly dependent on a limited number of high-value customers.

# Revenue Concentration by Segment
Segment	% of Customers	% of Revenue
Premium	~10%	48.2%
High	~15%	19.4%
Medium	~25%	18.6%
Low	~50%	13.8%

# Insight: Losing a small number of Premium customers would cause a significant revenue shock.

# Churn Risk & Revenue at Risk

136 customers identified as high churn risk

Revenue at risk: ~$3.3K (6-month horizon)

 #Insight: Targeted intervention on a limited customer group can protect meaningful revenue.

# Business Recommendations

Based on the analysis, the following actions are recommended:

VIP Retention Program

Focus on 285 Premium customers

Personalized offers, priority support, loyalty incentives

Win-Back Strategy

Target 68 high-value but at-risk customers

Time-limited discounts or reactivation campaigns

Cross-Sell Opportunities

Upsell to 295 medium/high potential customers

Increase purchase frequency and basket size

These actions aim to maximize revenue impact with minimal marketing spend.

# Dashboards & Deliverables

Interactive Power BI dashboards were developed to support decision-making:

- **Sales Analysis:** Total and category-wise sales trends.
- **Returns Analysis:** Understanding return patterns and reasons.
- **Geographical Analysis:** Regional sales performance and export insights.
- **Time Analysis:** Monthly, weekly, and daily sales patterns.
- **RFM Analysis:** Segmentation based on Recency, Frequency, and Monetary metrics.
- **Export Analysis:** Export vs domestic sales comparison.


# Analytical Approach 

Data Preparation & EDA

Transaction cleaning, customer aggregation

Customer Segmentation

RFM-based segmentation

Customer Lifetime Value Estimation

Probabilistic CLV modeling

Feature-enhanced ML validation

Business Impact Analysis

Revenue concentration

Churn risk quantification

Action prioritization

Technical modeling details are intentionally kept in the background; the focus is on business impact and decisions.

# Tools & Technologies

Python (pandas, numpy, scikit-learn)

SQL / BigQuery

Power BI

Jupyter Notebooks

# Outcome

This project demonstrates how customer analytics can directly support revenue growth and risk mitigation, bridging the gap between data science and business decision-making.



