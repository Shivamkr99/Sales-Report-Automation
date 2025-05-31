📊 Excel Sales Data Analyzer using UiPath
This project automates the process of analyzing sales data from an Excel workbook with unknown sheet names and count using UiPath. It dynamically reads all available sheets, cleans the data, and performs basic analytics.

✅ Features:
Detects and reads all sheets in the Excel file dynamically.

Filters out empty rows from each sheet to ensure clean data processing.

Calculates total sales per month from the cleaned data.

Computes the average sales across all months.

Classifies each month's sales as "Above Average" or "Below Average" based on the calculated average.

Writes the result in a new column named "Above/Below Average".

📌 Example:
If the monthly sales are:
1000, 1200, 800, 600
Average = (1000 + 1200 + 800 + 600) / 4 = 900

Then the result would be:

1000 → Above Avg

1200 → Above Avg

800 → Below Avg

600 → Below Avg

