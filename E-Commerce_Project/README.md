# Project Background

Beets, established in 2025, is a global e-commerce footwear retailer that sells sophisticated kinds of formal \& casual footwears to customers across multiple markets.
The store has valuable data on its sales, products, customer purchasing behavior and payment patterns, much of which have been underutilized. This Project rigorously analyzes this data in order to support better decision making and sustain Beet's overall commercial success and growth.



Insights and recommendations are provided on the following key areas:

\\Sales Trend Analysis:\*\*Evaluation of overall sales both by country and category, focusing on Revenue, Profit, Volume of orders and Average Order Value (AOV)

\\Brand \& Product level Performance:\*\*An analysis of Beet's products, brands \& categories, including their impact on sales

\\Regional Performance:\*\*An Evaluation of revenue, orders and sales performance across various countries

\\Customer Behavior and Purchasing Pattern:\*\*Analysis of customer product preference and payment behaviour to understand their contribution to sales

The DAX Formulas used to calculate and aggregate new measures for this analysis can be found \[here](https://docs.google.com/document/d/1ar1-KqKwVl\_Z9YIilHPeV29UvgUJwl3iw9Y3FPKfOKg/edit?usp=sharing).

A view of the dashboard used to report and explore the dataset is seen here !\[Visualization specific to category 2](./E-Commerce\_Project/dashboard.png)



# Data Structure \& Initial Checks

The data structure consists of two tables: Sales and Products, The Sales table contains 500 records.

!\[Visualization specific to category 2](./E-Commerce\_Project/Project\_ERD.png)

Before beginning the analysis, thorough cleaning was executed using power query to remove inconsistencies and handle nulls, hence improving data quality and integrity.



# Executive Summary

### Overview of Findings

After a spike in early June, Beets experienced a significant month-over-month decline in July with Key Performance Indicators showing month over month decrease: revenue by 30.1%, average order value by 10.5%. This decline points to changes in both sales volume and the value of customer purchases. While analysis of product, category, regional and payment performance revealed shifts in purchasing patterns across the business, the following sections will explore key factors and identify areas of improvement in order to strengthen product and category performance whilst understanding customer purchasing behavior for sustainable revenue growth.



Below is the overview section of the dashboard in action.

!\[Visualization specific to category 3](./E-Commerce\_Project/dashboard\_gif.gif)]



# Insights Deep Dive

### Sales Trend:

* Revenue peaked in June at approximately $70.8K recording the strongest monthly performance in the period analyzed. The spike was associated with unusually high sales of summer footwear across casual, formal and open categories.
* February sales declined 7.2% month over month, accompanied by a 14.3% decrease in units sold. Further investigations uncovered that this reduction in volume again was concentrated in the formal and casual categories.
* Average Order Value dropped sharply in March by 18.8%. This decline may be attributed to low selling products like Timberland having increased orders to the month prior. Subsequent months like May also experienced a decrease in AOV with July declining 10.5% relative to June. The corresponding decline in AOV and revenue suggests that the post-June slowdown reflected significant changes in both sales volume and customer purchases.
* August saw a dip in total sales (18.4%) making it the month with the lowest sales recorded.

!\[Visualization specific to category 4](./E-Commerce\_Project/Sales\_trend.png)



### Product \& Category Performance:

* &#x20;Monkstraps recorded the highest sales volume, with 575 units sold, followed by Oxford (561 units) and Boots (540 units). These products were the strongest volume    drivers during the period analyzed.
* In Q1, Q2 \& Q3, Canvas generated the highest profit at $63.4K, followed by Oxford ($58.9K) and Brogues ($58.5K). This signals that the products selling the most units are not necessarily the products generating the most profit.
* Formal footwear was the strongest-performing category, generating approximately $180K in revenue and $82K in profit from 2,000 units sold. Casual footwear followed with $83K in revenue, 935 units sold, and $38K in profit.
* Monkstraps and Boots combined high sales volume with comparatively lower revenue, generating $51.1K and $41.1K respectively from 575 and 540 units sold. This highlights the importance of looking beyond sales when evaluating product performance.

!\[Visualization specific to category 5](./E-Commerce\_Project/Products.png)



### Customer Behavior \& Preference:

* In Q1 \& Q2 combined, Clarks generated the highest revenue  ($110k, 1234 units sold) selling across formal and casual categories but in Q3, Zara generated the most sales ($25k, 280 units) selling majorly across the same categories as well.
* Green footwears recorded the highest purchase volume overall (964 units sold and $86K in revenue) but interestingly had low orders in January and no orders at all in both July \& August. Further observations found that they sold poorly across the utility categories. This shift in demand signals customer purchasing patterns during summer periods.
* Cash payments accounted for 1,049 units sold, showing that customers still use cash for a significant volume of purchases despite Card and Bank Transfer generating more revenue.
* Card payments generated the highest revenue at approximately $99.2K, followed by Bank Transfer at $94K by the end of August. This indicates that digital payment methods account for a substantial share of customer purchases.

!\[Visualization specific to category 6](./E-Commerce\_Project/Customerbehavior.png)





# Recommendations:

Based on the insights and findings above, we would recommend the marketing \& sales team to consider the following:

* Utilizing seasonal sales patterns to plan inventory and promotions ahead of peak periods due to the unusual spike in June, while introducing targeted offers or campaigns during slower months. This can help the marketing team maintain demand and handle large swings in monthly revenue.
* Review of product pricing, margins, and promotional strategies across high-volume products should be iterated to determine whether pricing or product mix adjustments could improve revenue and profitability without reducing demand. This is as a result of products like Monkstraps which drive more sales (575 units) but amount to relatively lower revenue.
* Re-evaluate Derby and loafers as these products barely make up 10% of revenue overall. Attempting to sell bundle offers and utilizing cross-selling alternatives as these may maximize incoming traffic.
* Supporting the strongest digital payment options while maintaining convenient alternatives such as cash may help identify opportunities to improve checkout convenience and reduce friction across customer segments.
* Green footwears made up 24% of sales volume and generated the highest revenue ($86K) from Q1-Q3. Strategic and marketing planning to push these products in massive volumes near summer time may increase orders and revenue overall.

# Assumptions and Caveats:

Throughout the analysis, few assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* The analysis is only limited to MoM (month over month) comparisons because the date range only spans from 1/1/2026 - 08-14-2026 (i.e. 8 months) which barely make up a year.
* Some records had null values and were handled by eliminating them before analysis.
* Inconsistencies were also found, particularly in the category, brand, and products field and were further resolved by standardization.



# Key take-aways:

The following are Key take-aways recorded from the analysis:

* Sales performance was highly seasonal, with revenue peaking at approximately $70.8K in June before declining sharply in the following months.
* Products like Monkstraps despite making the highest sales volume (575 units sold) did not make it to the Top 3 products that contributed to revenue.
* High sales volume did not always translate into high profitability. Monkstraps led in units sold, while Canvas generated the highest profit at $63.4K.
* Customer purchasing patterns varied across products and colours. Green footwear recorded the highest purchase volume at 964 units, but demand weakened considerably in some later months.
* Digital payments generated the most revenue, with Card at approximately $99.2K and Bank Transfer at $94K, while Cash still represented a significant volume of purchases.
* The June-to-July slowdown affected both revenue and AOV, with revenue falling 30.1% and AOV declining 10.5%, highlighting the need to monitor both sales volume and purchase value.
* Product, category, payment, and customer-level analysis provides a clearer picture than revenue alone, helping Beets identify where demand, profitability, and purchasing behaviour differ.
* Formal footwear was the strongest category, contributing approximately $180K in revenue and $82K in profit, making it a major driver of overall business performance.

