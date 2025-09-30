STRFTIME('%Y', "Order Date"): Pulls out the year from each order date.

STRFTIME('%m', "Order Date"): Pulls out the month from each order date.

SUM(Sales): Adds up all sales values to calculate monthly revenue.

COUNT(DISTINCT "Order ID"): Counts unique order IDs to measure order volume.

GROUP BY year, month: Groups the dataset by year and month so calculations happen at the monthly level.

ORDER BY year, month: Ensures the final output is displayed in chronological order.
