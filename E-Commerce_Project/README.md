<img width="2000" height="2000" alt="Blue and White Simple Shoe Store Logo" src="https://github.com/user-attachments/assets/bf43b214-dc9e-4eb4-98d2-1c4e5fc9d6fb" />


# Project Background

Beets, established in 2025, is a global e-commerce footwear retailer that sells sophisticated kinds of formal \& casual footwears to customers across multiple markets.
The store has valuable data on its sales, products, customer purchasing behavior and payment patterns, much of which have been underutilized. This Project rigorously analyzes this data in order to support better decision making and sustain Beet's overall commercial success and growth.



Insights and recommendations are provided on the following key areas:

Sales Trend Analysis: Evaluation of overall sales both by products and category, focusing on North Star Metrics: Revenue, Profit, Volume of orders and Average Order Value (AOV)

Brand & Product level Performance: An analysis of Beet's products, brands \& categories, including their impact on sales

Customer Behavior and Purchasing Pattern: Analysis of customer product preference and payment behaviour to understand their contribution to sales

The DAX Formulas used to calculate and aggregate new measures for this analysis can be found \[here]([https://docs.google.com/document/d/1ar1-KqKwVl\_Z9YIilHPeV29UvgUJwl3iw9Y3FPKfOKg/edit?usp=sharing](https://github.com/jirenonso/E-Commerce-Retail-Project/blob/main/E-Commerce_Project/DAX%20Formulas)).

A view of the dashboard used to report and explore the dataset is seen here <img width="679" height="511" alt="dashboard" src="https://github.com/user-attachments/assets/efe24ad2-bf19-4797-8246-ee516ddc8a53" />





# Data Structure \& Initial Checks

The data structure consists of two tables: Sales and Products, The Sales table contains 500 records.

<img width="636" height="497" alt="Project_ERD" src="https://github.com/user-attachments/assets/e2205f54-61e5-4b46-9563-e6305fc098d8" />


Before beginning the analysis, thorough cleaning was executed using power query to remove inconsistencies and handle nulls, hence improving data quality and integrity.



# Executive Summary

### Overview of Findings

After a spike in early June, Beets experienced a significant month-over-month decline in July with Key Performance Indicators showing month over month decrease: revenue by 30.1%, average order value by 10.5%. This decline points to changes in both sales volume and the value of customer purchases. While analysis of product, category, regional and payment performance revealed shifts in purchasing patterns across the business, the following sections will explore key factors and identify areas of improvement in order to strengthen product and category performance whilst understanding customer purchasing behavior for sustainable revenue growth.



Below is the overview section of the dashboard in action.



<img width="730" height="528" alt="dashboard_" src="https://github.com/user-attachments/assets/afff00e1-bc87-4eeb-b7b4-f676f49678d6" />







# Insights Deep Dive

### Sales Trend:

* Revenue peaked in June at approximately $70.8K recording the strongest monthly performance in the period analyzed. The spike was associated with unusually high sales of summer footwear across casual, formal and open categories.
* February sales declined 7.2% month over month, accompanied by a 14.3% decrease in units sold. Further investigations uncovered that this reduction in volume again was concentrated in the formal and casual categories.
* Average Order Value dropped sharply in March by 18.8%. This decline may be attributed to low selling products like Timberland having increased orders to the month prior. Subsequent months like May also experienced a decrease in AOV with July declining 10.5% relative to June. The corresponding decline in AOV and revenue suggests that the post-June slowdown reflected significant changes in both sales volume and customer purchases.
* August saw a dip in total sales (18.4%) making it the month with the lowest sales recorded.

<img width="667" height="175" alt="Sales_trend" src="https://github.com/user-attachments/assets/1b9236a7-24d5-4ef2-b0a9-a6eaf4d96c56" />




### Product \& Category Performance:

* &#x20;Monkstraps recorded the highest sales volume, with 575 units sold, followed by Oxford (561 units) and Boots (540 units). These products were the strongest volume    drivers during the period analyzed.
* In Q1, Q2 \& Q3, Canvas generated the highest profit at $63.4K, followed by Oxford ($58.9K) and Brogues ($58.5K). This signals that the products selling the most units are not necessarily the products generating the most profit.
* Formal footwear was the strongest-performing category, generating approximately $180K in revenue and $82K in profit from 2,000 units sold. Casual footwear followed with $83K in revenue, 935 units sold, and $38K in profit.
* Monkstraps and Boots combined sold the most units but made comparatively lower revenue, generating $51.1K and $41.1K respectively. This highlights the importance of looking beyond sales when evaluating product performance.


<img width="620" height="178" alt="Screenshot 2026-10-04 015759" src="https://github.com/user-attachments/assets/cd609b0a-fa59-4441-b29d-71b2f803e9c4" />



### Customer Behavior \& Preference:

* In Q1 \& Q2 combined, Clarks generated the highest revenue  ($110k, 1234 units sold) selling across formal and casual categories but in Q3, Zara generated the most sales ($25k, 280 units) selling majorly across the same categories as well.
* Green footwears recorded the highest purchase volume overall (964 units sold and $86K in revenue) but interestingly had low orders in January and no orders at all in both July \& August. Further observations found that they sold poorly across the utility categories. This shift in demand signals customer purchasing patterns during summer periods.
* Cash payments accounted for 1,049 units sold, showing that customers still use cash for a significant volume of purchases despite Card and Bank Transfer generating more revenue.
* Card payments generated the highest revenue at approximately $99.2K, followed by Bank Transfer at $94K by the end of August. This indicates that digital payment methods account for a substantial share of customer purchases.

<img width="358" height="219" alt="customer_behavior" src="https://github.com/user-attachments/assets/176c52f8-8200-4c63-a971-9a9030673344" />






# Recommendations:

Based on the insights and findings above, we would recommend the marketing \& sales team to consider the following:
## Recommendations

| Priority   | Action                                                                                                                                                                                                                                                           | Owner                           | Impact                                                                                                   | Metric to Track                                                                                          |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| **High**   | Use historical seasonal sales patterns to plan inventory and promotions ahead of peak periods, particularly around the June sales spike. Introduce targeted campaigns and offers during slower months to stabilize demand.                                       | Marketing & Inventory Teams     | **Reduce month-to-month revenue volatility by 10–15%** and improve sales during slower periods.          | Monthly Revenue Growth; Revenue Volatility; Inventory Turnover; Campaign Conversion Rate                 |
| **High**   | Review pricing, margins, and promotional strategies for high-volume products such as Monkstraps, which generated **575 units sold but comparatively lower revenue**. Test pricing and product-mix adjustments while monitoring demand.                           | Product & Pricing Team          | **Increase revenue per unit by 5–10%** on high-volume products without materially reducing sales volume. | Revenue per Unit; Gross Margin %; Units Sold; Product Conversion Rate                                    |
| **Medium** | Re-evaluate Derby and Loafers, which collectively contribute a relatively small share of overall revenue. Test bundle offers and cross-selling with stronger-performing products to improve their commercial performance.                                        | Merchandising & Marketing Teams | **Increase Derby and Loafer revenue by 10%** through bundles and cross-selling opportunities.            | Product Revenue; Bundle Conversion Rate; Cross-Sell Rate; Average Order Value                            |
| **Medium** | Continue supporting high-performing digital payment methods such as Card and Bank Transfer while maintaining convenient alternatives such as Cash. Review payment-level performance to identify checkout friction and opportunities to improve payment adoption. | Payments & Product Teams        | **Increase digital payment adoption by 5%** while maintaining access to alternative payment methods.     | Digital Payment Share; Payment Success Rate; Checkout Conversion Rate; Payment Method Revenue            |
| **High**   | Use the strong performance of Green footwear to inform seasonal inventory and marketing decisions. Increase promotional visibility and inventory availability ahead of periods when demand for Green footwear historically rises.                                | Marketing & Inventory Teams     | **Increase Green footwear sales volume by 10–15%** during peak seasonal periods.                         | Green Footwear Units Sold; Green Footwear Revenue; Inventory Sell-Through Rate; Campaign Conversion Rate |



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

