
# Table of Content 
- [Project Overview](#Project-Overview)
- [Tools Used](#Tools-Used)
- [Data Cleaning Steps](steps)
- [Exploratory analysis](#Exploratory-analysis)



# Project Overview
This project demonstrates my data cleaning, transformation, and exploratory analysis process using Microsoft Excel.
The goal was to clean a messy dataset by handling missing values, removing duplicates, and preparing the data for meaningful analysis and visualization.


#         Tools Used
- Microsoft Excel

- SQL

- POWER BI

- TABLEAU

 #              DATA CLEANING AND PREPARATION
 - Tool used: Excel

- Cleaned and trimmed the entire dataset to remove unnecessary spaces that created duplicate entries.

- Converted the dataset into a table and removed all duplicate rows for consistency.

- Performed a quick scan to identify blank cells, incorrect values, and errors.

- Filled missing item names (including those labeled “UNKNOWN” or “ERROR”) using the relationship between item name and price.

- Each item had a specific price (e.g., Coffee = 1).

- I filtered rows where price = 1, reviewed errors, and used copy-and-replace to fill missing values accurately.

- When two items shared the same price, I used an Excel formula to randomly
   assign names to balance the data: =IF(D8=3, IF(ISEVEN(ROW()), "Juice", "Cake"), B8)

- Calculated missing Price values using: Total Spent / Quantity

- Calculated missing Quantity values using: Total Spent / Price per Unit

- Filled missing Price per Unit values using the IFS function to assign each price to its correct item.

- Calculated missing Total Spent values using: =Quantity * Price

- Filled missing Dates with the previous valid date, assuming they were purchased on the same day.

- Created Pivot Tables to summarize total sales by each item and identify the most common purchasing methods.

- Designed Visual Dashboards and charts to illustrate sales trends and insights clearly.


 # Exploratory analysis
 Tool used: MYSQL
 - I used SQl to find the highest item quantity sold
 - I ranked the most profitable incoming by using windows function and cte to see which items brings in the highest profit

# Interactive dashboards
Tools used: 
- [**Tableau**](https://public.tableau.com/views/Book1_17628679842870/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- [**Power BI**](https://app.powerbi.com/view?r=eyJrIjoiZGJhYmZmYzQtMDM4OS00MmI0LWI1ZWYtMDM4OTE4YjBkNmI4IiwidCI6Ijk0MWJiZjVmLWYyYzAtNDg3NS1hMjRjLTY5MDc4NjVkMjUxYSIsImMiOjh9)

 # DATA ANALYSIS AND INSIGHT

 # Recommendations

 
  
