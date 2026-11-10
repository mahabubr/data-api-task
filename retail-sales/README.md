1\. Task 1: Product Revenue Ranking – Find the top 5 products by net revenue, considering only products with at least 50 transactions, using `product_id`, `net_amount_bdt`, and `is_return`.

2\. Task 2: Rolling Revenue Optimization [Date/Time] – Find the highest-revenue 5-calendar-day window for each `city` between `2026-08-01` and `2026-10-31` using an optimized sliding-window algorithm.

3\. Task 3: Data Relationship Validation – Detect inconsistent mappings between `product_id`, `product_name`, and `category`, and identify every product ID associated with multiple categories.

4\. Task 4: Tag Association Ranking – Find the top 10 most strongly associated tag pairs using co-occurrence frequency and Jaccard similarity across the `tags` arrays.

5\. Task 5: Store Idle-Time Analysis [Date/Time] – Find the longest transaction-free interval for each `store_id` within a single day using `sale_date` and `sale_time`, then identify the store with the longest idle period.

6\. Task 6: Discount Performance Ranking – Identify the discount percentage range that generates the highest average net revenue per transaction, excluding returned transactions.

7\. Task 7: Optimized Two-Sum Search – Find two transactions from the same `city`, involving different `product_name` values, whose combined non-returned `net_amount_bdt` is closest to ৳15,000 without exceeding the target.

8\. Task 8: Product Return Anomaly Detection – Identify products with at least 30 transactions whose return rate exceeds their category's overall return rate by at least 7 percentage points.

9\. Task 9: Intraday Revenue Detection [Date/Time] – Divide `sale_time` into 30-minute intervals and identify the highest-revenue interval for each `sales_channel` during October 2026.

10\. Task 10: Longest Consecutive Sales Streak [Date/Time] – Find the `store_id` with the longest consecutive calendar-day streak of non-returned transactions, resolving equal streaks by selecting the earliest starting date.

11\. Task 11: Multi-Level Product Ranking – Rank products within each `category` by net quantity sold, using `quantity` and `is_return`, and return the top three products per category.

12\. Task 12: Transaction Amount Reconciliation – Recalculate every transaction's amount using `unit_price_bdt`, `quantity`, `discount_pct`, and `tax_pct`, then identify records with a difference exceeding ৳0.02 from `net_amount_bdt`.

13\. Task 13: Monthly Return-Rate Analysis [Date/Time] – Identify the month with the highest return rate for each `category` during 2026, considering only months with at least 30 transactions.

14\. Task 14: Statistical Price Outlier Detection – Apply the IQR method to `unit_price_bdt` within each `product_id` and identify transactions outside the 1.5 × IQR boundaries.

15\. Task 15: Revenue Concentration Analysis – Determine the minimum number of products required to generate 80% of positive net revenue within each `category` using cumulative revenue ranking.

16\. Task 16: Payment Method Dominance – Identify the most dominant `payment_method` in each `city` based on transaction percentage, resolving ties using total net revenue.

17\. Task 17: Weekday Revenue Anomaly [Date/Time] – Using transactions from January to September 2026, identify the weekday with the highest average daily net revenue and compare it against the overall average daily revenue.

18\. Task 18: Top-K Transaction Selection – Find the top 25 transactions by `net_amount_bdt` where `is_return` is false, `quantity` is at least 2, and `discount_pct` is between 5 and 20, using a heap-based approach.

19\. Task 19: Category Distribution Entropy – Calculate Shannon entropy for each `sales_channel` using its `category` distribution and identify the channel with the highest product-category diversity.

20\. Task 20: Monthly Sales Streak Detection [Date/Time] – Identify the longest sequence of consecutive months in which each `city` generated positive net revenue, using `sale_date` and `net_amount_bdt`.

