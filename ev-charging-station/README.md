1\. Task 1: Top Revenue Stations – Find the top 10 `station_id` by total `total_cost_usd`, including session count and average revenue.

2\. Task 2: Monthly Revenue Growth – Calculate monthly revenue for 2026 using `session_date` and rank months by growth percentage.

3\. Task 3: Connector Performance – Group by `connector` and calculate total `energy_kwh`, average `duration_min`, and revenue.

4\. Task 4: Membership Comparison – Compare `Plus`, `Standard`, and `Guest` by average `unit_price_usd` and total spending.

5\. Task 5: Overnight Charging Analysis – Find sessions between `2026-01-01` and `2026-06-30` where `end_date` differs from `session_date`. Rank cities by count.

6\. Task 6: Billing Accuracy Check – Identify `session_id` values where calculated cost (`energy_kwh × unit_price_usd`) differs from `total_cost_usd` by more than $0.01 after rounding.

7\. Task 7: High-Energy Charging – Filter `energy_kwh >= 50` and `charger_kw >= 100`. Rank cities by total energy delivered.

8\. Task 8: Evening Demand – For June–August 2026, find sessions starting between `17:00` and `21:00`. Rank stations by session count.

9\. Task 9: Fleet Vehicle Revenue – Filter `vehicle_class = Fleet Delivery Van`. Calculate revenue and average cost by `payment_method`.

10\. Task 10: Charging Efficiency – Calculate average charging power (`energy_kwh × 60 / duration_min`) and find the top 10 sessions.

11\. Task 11: Weekend Revenue Comparison – Compare weekend and weekday revenue by `city` during July–September 2026.

12\. Task 12: Session Flag Analysis – Count each value in `session_flags` and identify the 5 most frequent flag combinations.

13\. Task 13: Premium Pricing Analysis – Filter `unit_price_usd > 0.50`. Rank cities by average transaction value and session count.

14\. Task 14: High-Value Transactions – Filter `total_cost_usd > 40`. Calculate each `payment_method`'s percentage of these transactions.

15\. Task 15: Late-Night Charging – Between October 2025 and March 2026, find sessions starting from `22:00` to `05:59`. Rank cities by average duration.

16\. Task 16: Payment Revenue Share – Group by `payment_method` and `membership`. Calculate revenue share and average transaction value.

17\. Task 17: Station Vehicle Diversity – Find stations serving at least 3 different `vehicle_class` values. Rank by total revenue.

18\. Task 18: Fast Charging Comparison – Compare `charger_kw >= 100` versus lower capacities by average duration, energy, and revenue.

19\. Task 19: Weekly Revenue Trends – Calculate weekly revenue by `city` from August–October 2026 and find the largest week-over-week increase.

20\. Task 20: Off-Peak Opportunities – Filter `peak_hour = false`, `energy_kwh >= 40`, and `membership = Plus`. Rank stations by revenue.

21\. Task 21: Charging Cost Distribution – Categorise `total_cost_usd` into under $10, $10–$25, $25–$40, and above $40. Calculate session percentage by category.

22\. Task 22: Quarterly Energy Growth – Group `session_date` by quarter for 2025 and 2026. Calculate energy consumption and quarter-over-quarter growth.

23\. Task 23: Vehicle Charging Preferences – Find the most common `connector` for each `vehicle_class` and calculate its percentage of sessions.

24\. Task 24: Station Revenue Efficiency – Calculate total revenue divided by total `duration_min` for each station. Rank the top 10 stations with at least 40 sessions.

25\. Task 25: Peak-Hour Monthly Trends – For January–June 2026, calculate monthly `peak_hour = true` session percentages by `city`. Rank cities by their highest monthly percentage.

26\. Task 26: Membership Discount Validation – Find `Plus` and `Fleet` sessions missing `member_discount` in `session_flags`. Group discrepancies by `city`.

27\. Task 27: Payment Method Diversity – Find stations accepting at least 4 distinct `payment_method` values. Rank by transaction count and total revenue.

28\. Task 28: Daily Charging Demand – For September 2026, calculate daily session counts and total `energy_kwh`. Find the 5 highest-demand days.

29\. Task 29: Revenue Concentration – Calculate each `station_id`'s percentage of its city's total revenue. Find the top 3 stations in each city.

30\. Task 30: Multi-Condition Ranking – Filter `charger_kw >= 150`, `energy_kwh >= 45`, and `peak_hour = true`. Rank the top 10 stations by average `total_cost_usd`.