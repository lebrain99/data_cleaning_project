# data_cleaning_project  (Excel)

This project demonstrates my data cleaning, transformation, and exploratory analysis process using Microsoft Excel.
The goal was to clean a messy dataset by handling missing values, removing duplicates, and preparing the data for meaningful analysis and visualization.

STEPS

Cleaned and trimmed the entire dataset to remove unnecessary spaces that created duplicate entries.

Converted the dataset into a table and removed all duplicate rows for consistency.

Performed a quick scan to identify blank cells, incorrect values, and errors.

Filled missing item names (including those labeled “UNKNOWN” or “ERROR”) using the relationship between item name and price.

Each item had a specific price (e.g., Coffee = 1).

I filtered rows where price = 1, reviewed errors, and used copy-and-replace to fill missing values accurately.

When two items shared the same price, I used an Excel formula to randomly assign names to balance the data:

=IF(D8=3, IF(ISEVEN(ROW()), "Juice", "Cake"), B8)


Calculated missing Price values using:

=Total Spent / Quantity


Calculated missing Quantity values using:

=Total Spent / Price per Unit


Filled missing Price per Unit values using the IFS function to assign each price to its correct item.

Calculated missing Total Spent values using:

=Quantity * Price


Filled missing Dates with the previous valid date, assuming they were purchased on the same day.

Created Pivot Tables to summarize total sales by each item and identify the most common purchasing methods.

Designed Visual Dashboards and charts to illustrate sales trends and insights clearly.

** Tools Used
Microsoft Excel

Data Cleaning

Formula Application

Pivot Tables

Charts and Dashboards

          Key Insights

Cleaned and standardized all item and price data.

Corrected missing values and resolved all duplicates.

Created interactive visuals showing total sales and purchasing trends.

