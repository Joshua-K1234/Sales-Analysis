# Sales-Analysis

<img src="https://github.com/Joshua-K1234/Sales-Analysis/blob/main/Visuals/Dashboard.JPG" alt="Sales Dashboard" width="800"/>

<img src="https://github.com/Joshua-K1234/Sales-Analysis/blob/main/Visuals/Dashboard%20Quantity.JPG" alt="Sales Dashboard" width="800"/>

### Project Goal
Build a Power BI sales overview dashboard to track KPIs across the Central, West, South, and East regions, visualize year-over-year performance changes, and show how sales, quantity and profit vary proportionally across states.

### 1. Data Exploration
- Broke the analysis into regional performance
- Identified key metrics for analysis, including:
    - Total Sales, Total Profit, Total Quantity Sold, and Year-over-Year Change
    - Current Year VS Previous Year

### 2. Data Preparation

- **In Power Query**
  - Checked data types and checked through data, no work was needed to be done.
- **In Power BI**
  -  Created measures for each of the KPI's
  -  Created Dynamic Slicers using DAX allowing for filtering of the three main types of data, sales, quantity and profit.
    - Used dax to generate adaptive titles
    - Used dax to format numbers with prefixes and suffixes for clarity such as $ prefix for currency and K suffix for thousands.

### 3. Analytics Use Cases  

- **Regional Analysis** – Identify which regions performed well each year and which ones performed worse.
- **Detailed Analysis** – Used the table to analyse YoY changes for each metric, including totals to have an overview of the year.

### Epilogue
This project was fun to complete. I got to use features from the latest update of power BI to create KPI cards with the new categories feature and see how far I could go with it. I got to use a lot of advanced dax to create measures such as YoY change, and overcame obstacles such as figuring out how to make the whole dashboard dynamic.
Improvements:
- In hindsight I could also color the bar charts for each month the same color as the region.
