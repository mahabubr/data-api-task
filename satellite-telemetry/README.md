1\. Task 1: Peak Observation Hour Analysis – Using `observed_date` and `observed_time`, identify the hour with the highest number of telemetry observations for each `orbit_type` during January–March 2025.

2\. Task 2: Monthly Anomaly Rate Calculation – Calculate the monthly anomaly percentage for each `satellite_id` between `2025-01-01` and `2025-12-31`, and identify the satellite with the highest average monthly anomaly rate.

3\. Task 3: Longest Observation Gap Detection – Sort observations by `observed_date` and `observed_time` for each `satellite_id` and find the longest time gap between consecutive observations.

4\. Task 4: Rolling Seven-Day Battery Analysis – Calculate the seven-day rolling average of `battery_pct` for each `satellite_id` during April–June 2026 and identify the lowest rolling-average period.

5\. Task 5: Weekday Anomaly Pattern Analysis – Using `observed_date`, calculate the anomaly percentage for each day of the week and identify the weekday with the highest anomaly rate for every `orbit_type`.

6\. Task 6: Duplicate Timestamp Detection – Between `2026-01-01` and `2026-06-30`, identify duplicate observation timestamps for the same `satellite_id` using `observed_date` and `observed_time`.

7\. Task 7: Orbital Velocity Outlier Detection – Calculate theoretical orbital velocity from `altitude_km` using Earth's gravitational parameter (398600.4418 km³/s²) and radius (6371 km), then identify records where the difference from `velocity_km_s` exceeds 0.02 km/s.

8\. Task 8: Thermal Outlier Detection Using IQR – Apply the Interquartile Range method to `temperature_c` separately for each `orbit_type` and identify all statistical temperature outliers.

9\. Task 9: Operator Market Concentration Analysis – Calculate the Herfindahl-Hirschman Index (HHI) using each `operator`'s share of total telemetry observations.

10\. Task 10: Payload Inverted Index Construction – Build an inverted index mapping each individual value in `payloads` to its corresponding unique `satellite_id` values.

11\. Task 11: Common Active-System Identification – Use set intersection on `active_systems` to identify the systems shared by every satellite observation within each `orbit_type`.

12\. Task 12: Anomaly Data Integrity Detection – Identify records where `anomaly` and `anomaly_type` contradict each other, such as `anomaly=true` with `anomaly_type=none`.

13\. Task 13: Multi-Criteria Satellite Ranking – Rank satellites using a composite performance score based on average `battery_pct`, `signal_dbm` and `solar_output_kw`, normalized to comparable scales.

14\. Task 14: Payload Similarity Analysis – Calculate Jaccard similarity between the `payloads` sets of every pair of unique satellites and identify pairs with similarity above 0.50.

15\. Task 15: Active-System Pair Frequency – Calculate the frequency of every unique pair of co-occurring systems in `active_systems` and identify the five most frequent pairs.

16\. Task 16: Satellite Battery Percentile Ranking – Calculate the 90th-percentile `battery_pct` for each `satellite_id` and rank all satellites according to their percentile values.

17\. Task 17: Eclipse Power Anomaly Detection – Identify records where `eclipse=true` but `solar_output_kw` is greater than zero, using the power-generation relationship as a consistency constraint.

18\. Task 18: Payload Co-Occurrence Graph Analysis – Construct a graph where each payload in `payloads` represents a node and shared satellite usage creates weighted edges; identify the payload with the highest weighted degree.

19\. Task 19: Operating-Mode Distribution Entropy – Calculate Shannon entropy for the `operating_mode` distribution of each `satellite_id` and rank satellites by operational diversity.

20\. Task 20: Pareto Frontier Identification – Identify non-dominated records by maximizing `battery_pct` and `signal_dbm` while minimizing the absolute temperature deviation from 22°C, using `telemetry_id` to identify each record.