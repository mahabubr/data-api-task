1\. **Task 1: Summer Temperature Ranking** – Find the greenhouse with the highest average `temperature_c` between June 1 and August 31, 2026.

2\. **Task 2: Evening Light Intensity** – Find the `sensor_type` with the highest average `light_lux` between 16:00 and 20:00.

3\. **Task 3: Longest Warning Streak** – Find the longest consecutive-day sequence in which a greenhouse has at least one `Needs Review` reading each day.

4\. **Task 4: Monthly Water Consumption** – Find the month with the largest percentage increase in total `water_used_l` compared with the previous month.

5\. **Task 5: Weekend Water Usage** – Calculate the difference between average `water_used_l` on weekends and weekdays.

6\. **Task 6: Longest Reading Gap** – Find the greenhouse with the longest time gap between two consecutive readings.

7\. **Task 7: Nutrient Variation** – Find the `crop_type` with the greatest variation in `nutrient_ec_ms`.

8\. **Task 8: Soil pH Outliers** – Count the records where `soil_ph` falls outside the 1.5×IQR range.

9\. **Task 9: Low Battery Detection** – Find the `sensor_type` with the highest percentage of readings where `battery_pct` is below 20%.

10\. **Task 10: Most Common Alert Combination** – Find the most frequently repeated combination of values in the `alerts` array.

11\. **Task 11: Irrigation Efficiency** – Find the `irrigation_mode` with the highest average `soil_moisture_pct` per litre of `water_used_l`.

12\. **Task 12: Soil Acidity Comparison** – Find the `crop_type` with the highest percentage of readings where `soil_ph` is below 6.0.

13\. **Task 13: Calibration Reliability** – Find the `sensor_type` with the highest percentage of records where `is_calibrated` is false.

14\. **Task 14: Greenhouse Light Intensity** – Find the `greenhouse_id` with the highest median `light_lux`.

15\. **Task 15: Greenhouse Data Validation** – Find greenhouse IDs linked to more than one `greenhouse_name` or `crop_type`.

16\. **Task 16: Temperature and Humidity Relationship** – Find the `crop_type` with the strongest correlation between `temperature_c` and `humidity_pct`.

17\. **Task 17: Water Consumption Share** – Calculate the percentage of total `water_used_l` consumed by the three highest-consuming greenhouses.

18\. **Task 18: Alert Inconsistency** – Find the `sensor_type` with the highest percentage of `Normal` records containing alerts.

19\. **Task 19: Nutrient Range Analysis** – Find the `crop_type` with the widest range between the 25th and 75th percentiles of `nutrient_ec_ms`.

20\. **Task 20: Temperature Stability** – Find the `greenhouse_id` with the most consistent `temperature_c` readings based on the lowest coefficient of variation.