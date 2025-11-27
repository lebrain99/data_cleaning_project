
# Table of Content 
- [Project Overview](#Project-Overview)
- [Tools Used](#Tools-Used)
- [Data Cleaning Steps](#DATA-CLEANING-AND-PREPARATION)
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
 - Identified the highest item quantity sold using aggregate function SUM() and GROUP BY to determine which products drive the most customer demand.

- Ranked the most profitable items by applying window function DENSE_RANK() and CTEs to compare revenue across products and identify which items contribute most to income.

- Analyzed customer purchasing behavior by breaking down sales by day of the week using DATE_FORMAT() and grouping, helping uncover peak traffic periods.

- Performed payment method segmentation using grouping and conditional totals to understand how customers prefer to pay (Cash vs. Credit Card vs. Digital Wallet).
 

# Interactive dashboards
Tools used: 
- [**Tableau**](https://public.tableau.com/views/Book1_17628679842870/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- [**Power BI**](https://app.powerbi.com/view?r=eyJrIjoiZGJhYmZmYzQtMDM4OS00MmI0LWI1ZWYtMDM4OTE4YjBkNmI4IiwidCI6Ijk0MWJiZjVmLWYyYzAtNDg3NS1hMjRjLTY5MDc4NjVkMjUxYSIsImMiOjh9)

 # DATA ANALYSIS AND INSIGHT
 - Product Performance. Salad is the top revenue-generating product, showing that customers are willing to pay a premium for it. Its order volume sitting above the median confirms it's both popular and profitable. Coffee leads in total quantities sold, meaning it is the most frequently purchased everyday item. This indicates high demand but likely lower margins compared to premium items like salad. Cookies record the lowest spend and quantity, suggesting limited customer interest or possibly insufficient promotion or visibility.

- Sales Trends by Day. Thursday has the highest sales, making it the café’s strongest operational day. This could be linked to mid-week customer behavior, promotions, or workplace routines. Weekends (especially Sunday) show a noticeable drop in sales, signaling a potential opportunity to introduce weekend bundles, discounts, or promotions to boost traffic.

- Payment Method Usage. Payments are almost evenly distributed across Credit Card, Cash, and Digital Wallet. Digital Wallet leads slightly, indicating a growing preference for fast, contactless transactions. The café can capitalize on this by promoting mobile wallet loyalty rewards.

-  Monthly Sales Insights. Sales show consistent fluctuations across months, with noticeable dips in February and September.Peaks occur around June and October, possibly indicating seasonal trends or effective campaigns during those times. This pattern suggests the café could analyze seasonal demand and plan inventory and marketing pushes around expected highs and lows.

-  Quantities Sold Breakdown. Coffee, cake, and juice consistently contribute strong unit sales. Smoothies, tea, and cookies fall on the lower end. The café may need to revisit:
  -      Pricing strategy
  -       Placement on the menu
  -       Promotions or combos to strengthen demand.

- Total Orders & Revenue: With 9,959 total orders and $88.94K in revenue, the café shows stable customer activity and healthy sales volume. The gap between total orders and revenue highlights which products generate high volume vs. high value, helping guide future product priorities.

 # Recommendations

 
  
