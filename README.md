## urbancart-ecommerce-sql-analytics
A SQL case study on a 6-table e-commerce database (Jan 2024 to Dec 2025) covering unit economics, customer retention and RFM segmentation.
## Business Problem
UrbanCart's order volume was growing, but profit had stalled. I used SQL to find where the money was leaking: margins and returns, one-time buyers, and untargeted CRM discounting.
## Database
6 tables: `customers`, `products`, `campaigns`, `orders`, `order_items`, `returns` (1,373 orders, 2,223 line items, 600 customers).
## Skills Used
SQL (SQLite), multi-table JOINs, CASE WHEN, CTEs, window functions (LAG, ROW_NUMBER, DENSE_RANK, NTILE), cohort retention, market basket analysis, RFM segmentation.
## Key Findings
i) Gross merchandise value is Rs 88.08 lakh, but delivered net revenue is Rs 64.07 lakh. 19.1% of orders never complete.
ii) Fashion has the highest return rate (21.0%), and about 60% of its returns are size/fit issues.
iii) The 30%-off InfluencerFlash30 campaign has the lowest margin (24.0%) and the highest return rate (22.2%).
iv) Cash on Delivery fails 28.3% of the time, against 16.9% for UPI.
v) 71% of Influencer-acquired buyers order only once, against 18% for Referral.
vi) 62 "At-Risk High Value" customers hold Rs 11.90 lakh (18.6% of revenue).
## Recommendations
1. Cap flash discounts and move spend toward Referral and Organic channels.
2. Add a size and fit guide for Fashion, and push prepaid payment over COD.
3. Send a second-purchase nudge around day 45 and run a win-back campaign for at-risk customers.

