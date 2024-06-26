# Sales Product Performance Dashboard

## Project Overview

The Sales Product Performance Dashboard aims to provide comprehensive insights into the sales performance of products across various dimensions such as time, geography, and customer demographics. Utilizing data from six separate tables, the dashboard will offer a holistic view of sales metrics and trends.

### Dashboard 1 - Main Metrics Dashboard
1. **KPI Comparison to Previous Year**:
	- Cost of Goods(COGS), Revenue, Quantity, Profit, Profit Margin, and Transaction compared to the previous year.

2. **Yearly Performance Metrics(Above Average Years)**:
	- Total Revenue, Profit, and Transaction for years exceeding the average performance.

3. **Monthly Profit Trends**

4. **Profit by Week Type**

5. **Quarterly Profit Analysis**

6. **Profit by Weekday**
<img width="1377" alt="Dashboard-1" src="https://github.com/fangoaish/Excel__SONATINEN-Sales-Product-Performance-Dashboard/assets/51399519/0ac81010-0fa7-46ce-b894-788ae83fba7a">


### Dashboard 2 - Product Performance Dashboard
1. **Top 5 Profitable Products**

2. **Profit Share of the Top 5 Products v.s. Others**

3. **Total Products, Sold Products, Unsold Products**

4. **Overview of Total Profit Share by Product Pricing Strategy**

5. **Avg. Customer Age and #Customers**

6. **Profit by Age Groups**

7. **Total Profit by Countries**

<img width="1337" alt="Dashboard 2" src="https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/361e17f8-52e9-47c4-9e58-52ffc31c2b94">


## Project Steps
1. Data Gathering
2. Data Preparation Using Power Query, Advanced Formulas and Functions
3. Exploratory Data Analysis
4. Data Visualizations and Dashboard Build using **Pivot Tables**, **Pivot Charts**, **Timeline**, **Slicers** and **Macro**

## Data Sources
The data source is a fictitious product sales dataset.
  - SONATINEN.csv

The data contains six separate tables:
- FactInternetSales, DimProduct, DimSalesTerritory, DimDate, DimCustomer and DimGeography
  - The **FactInternetSales** table is the _fact table_
  - The **DimProduct**, **DimSalesTerritory**, **DimDate**, **DimCustomer** and **DimGeography** tables are the _dimension tables_.

## Data Preparation:
![Power Pivot](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/a453fd90-eeb5-49b0-9d3e-3915f9480795)
- Utilize **Power Query** to clean and prepare data.
- Utilize **Power Pivot** for understanding relationships between tables.
- Utilize the **IFs function** for dynamic graphics coordination.
- Use **VLOOKUP** for year-over-year (YoY) performance comparison.
- Manage errors with the **IFERROR function**.
- Highlight top performers using the **LARGE function**.
- Use **INDEX MATCH** to find the top months and corresponding age groups.
  

## Exploratory Data Analysis

### Dashboard 1 - Main Metrics Dashboard:
1. ### Yearly Performance Analysis
	- **Revenue and Profit by Year**
		- _**2015-2018**_ saw a steady increase in revenue and profit, peaking in _**2017**_ with over _**$102**_ million in revenue and a profit of _**$42.55**_ million.
		- Profit margins remained relatively stable (_**~41%**_), indicating consistent operational efficiency.
	- **Above Average Years (Revenue > $76.77M Average)**
		- _**2017**_ and _**2018**_ both exceeded the average, contributing _**66.5%**_ of the total revenue and _**67.1%**_ to overall profit during the observed period.

2. ### Monthly and Quarterly Trends
	- **Top Performing Months**
		- _**May**_, _**June**_, and _**December**_ were top performers, contributing significantly to the annual profit with peaks during the mid and end of the year, likely reflecting seasonal sales increases.
	- **Quarterly Analysis**
		- _**Q2**_ was the highest performing quarter, suggesting a strategic opportunity for targeted marketing and sales initiatives during this period.

3. ### Weekday and Weekend Performance
	- **Profit by Week Type**
		- _**Weekdays**_ significantly outperformed weekends, making up _**71.8%**_ of total profit.
		- Top weekdays for profit were _**Wednesda**y_, _**Tuesda**y_, and _**Thursday**_.

### Recommendations
- **Optimize Inventory and Pricing Strategies**: Given the high number of unsold products, review inventory levels and pricing strategies to improve turnover rates and reduce holding costs.
- **Enhance Seasonal and Quarterly Campaigns**: Capitalize on high-performing months and quarters by aligning marketing campaigns, promotions, and stock availability to boost sales during these peak times.
- **Focus on Weekday Sales**: Since weekdays are more profitable, consider enhancing weekday promotions and potentially offering special deals to boost weekend sales.






### Dashboard 2 - Product Performance Dashboard:
1. ### Product Performance:
	- The _**top 5 product**s_ significantly contribute to the company's profitability, making up nearly a quarter of the total profits. This underscores the importance of these products to the company's portfolio.
	- _Premium pricing strategies_ are highly effective, accounting for over 90% of total profits, which suggests that customers value and are willing to pay for perceived quality.

2. ### Customer Demographics:
	- Profit distribution across age groups shows that middle-aged customers (_**41-50 years**_) are the most profitable, suggesting that this demographic finds significant value in the products and should be a key target in marketing strategies.
	- Gender distribution in profitability is balanced, indicating effective market penetration across male and female segments.

3. ### Geographic Insights:
	- The _**United States**_ and _**Australia**_ are the top-performing countries in terms of profitability, pointing to strong market positions and customer bases in these regions.
	- There is a potential for growth in underperforming countries such as _**Canada**_ and _**France**_, where strategies could be realigned to enhance market penetration and profitability.


### Recommendations
- **Enhance Focus on Top Products**: Increase marketing efforts and inventory for the top 5 products to capitalize on their strong profit contribution.
- **Evaluate and Expand Premium Offerings**: Given the success of premium pricing strategies, consider expanding these offerings or enhancing features of existing products to justify premium pricing and increase profitability.
- **Target Core Demographic Groups:** Further develop products and marketing strategies tailored to the 41-50 age group while exploring opportunities to increase engagement with the 18-30 and 61+ age groups.
- **Balance Gender Targeting:** Continue to refine marketing strategies to equally appeal to both genders, leveraging the near-equal profit contribution from female and male customers.
- **Geographic Expansion:** Focus on expanding presence in high-profit countries like the United States and Australia, while also identifying and overcoming barriers in lower-performing regions like Canada.


## Conclusion
By streamlining data preparation, exploration, and visualization processes, the dashboard empowers organizations to identify trends, track performance metrics, and optimize strategies for success. 
