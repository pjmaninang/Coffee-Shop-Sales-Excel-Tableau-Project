![banner](https://github.com/pjmaninang/Coffee-Shop-Sales-Excel-Tableau-Project/blob/main/banner.jpg?raw=true)
# Coffee-Shop-Sales-Excel-Tableau-Project

## Project Overview

Maven Roasters, a fictional coffee shop with three store locations in New York, is wanting to analyze its sales and revenue data from the first half of the year in 2023. 

The company has provided a substantial amount of transactional data from January 2023 - June 2023 based on product offerings amongst the three different locations. This project analyzes and visualizes this transactional data in order to uncover critical insights that will help to improve Maven Roaster's success.

Through cleaning and aggregating data in Excel Power Query, as well creating a visualization in Tableau, insights and recommendations were focused on the following key objectives:

- Monitor revenue growth and performance trends – Evaluate monthly and hourly sales patterns across all store locations to identify periods of strong performance and detect potential slowdowns in traffic
- Assess product performance and profitability – Analyzed category and product-level revenue and sales volumes to pinpoint high-value items, as well as underperforming products that may require marketing support, repositioning, or removal from the portfolio

An interactive Tableau dashboard can be viewed and downloaded [here](https://public.tableau.com/app/profile/pj.maninang/viz/CoffeeShopDashboard_17530521998800/SalesDashboard)

Cleaned and aggregated excel file can be downloaded [here](https://github.com/pjmaninang/Coffee-Shop-Sales-Excel-Tableau-Project/blob/main/Power%20Query%20Cleaned%20Data.xlsx)

The original dataset can be found and downloaded [here](https://www.kaggle.com/datasets/agungpambudi/trends-product-coffee-shop-sales-revenue-dataset)

## Data Structure

Maven Roaster's transactional data consisted of 1 transaction table with a total row count of 149,117 records.
![Table](https://github.com/pjmaninang/Coffee-Shop-Sales-Excel-Tableau-Project/blob/main/Table.png?raw=true)

## Executive Summary

### Overview of Findings

From January to June 2023, total revenue grew by approximately 103%, driven by significant gains in the second quarter and peak month-over-month growth in March (29.80%) and May (31.77%). Morning hours between 8 AM and 11 AM consistently deliver the highest sales, with Astoria maintaining strong performance throughout the day, while Hell’s Kitchen and Lower Manhattan see steep declines in later hours. At 8 PM, when only the latter two locations remain open, revenue drops to just $3,000, far below all other time slots. Product performance is heavily concentrated in Coffee and Tea, led by the high-margin Barista Espresso, while several offerings—including Green Beans, Green Tea, Organic Chocolate, and Packaged Chocolate—underperform despite occasional short-term growth spikes. Maven Roasters should continue to focus on maximizing high-performing categories and peak-hour sales, while implementing targeted strategies to boost non-peak and late-day performance, and reassessing or reconfiguring low-yield products and operating hours to optimize profitability.

Below is an overview of the top of the interactive Tableau dashboard:
![overview](https://github.com/pjmaninang/Coffee-Shop-Sales-Excel-Tableau-Project/blob/main/Dashboard%20Overview.png?raw=true)

## Findings and Insights

### Sales and Revenue Trends

- Revenue more than doubled in six months, total sales growing by approximately 103% from January to June 2023, driven by strong gains in the second quarter
- Highest month-over-month growth was in March and May with March boasting a 29.80% increase over February, and May recording the largest surge at 31.77% compared to April, signaling strong seasonal or promotional impacts during these periods
- Morning hours dominate daily revenue with sales consistently peaking around the times of 8 AM to 11 AM, reinforcing the importance of capturing morning customer traffic
- Across all three locations, peak revenue hours occur between 8 AM and 11 AM, but the Astoria location stands out for maintaining steady sales throughout the entire day. In contrast, Hell’s Kitchen and Lower Manhattan experience noticeable revenue declines in the later hours
- At 8:00 PM when only Lower Manhattan and Hell’s Kitchen are still open, total revenue drops to roughly $3,000, far below other time slots where even the lowest morning revenue at 6:00 AM still reaches about $20,000

### Product Performance and Profitability

- Coffee and Tea dominate category revenue – Coffee generated $269,592 and Tea $196,406, accounting for the majority of total category sales
- Barista Espresso leads in both revenue and quantity sold – This product is the top revenue driver while also ranking highly in units sold, underscoring its profitability and customer appeal
- Several products underperform across both metrics – Green Beans, Green Tea, and Organic Chocolate consistently rank in the bottom five for both revenue and quantity sold, signaling potential candidates for removal, repositioning, or targeted promotions
- Despite achieving a 48% month-over-month revenue increase from March to April, Packaged Chocolate has generated only $4,408 in total revenue to date, making it the lowest-performing product category, suggesting that further investment should be contingent on validating sustained demand, potentially through targeted promotions, bundling strategies, or seasonal offerings

## Recommendations

- Continue to prioritize Coffee and Tea offerings—especially high-margin leaders like Barista Espresso—through prominent menu placement, upselling strategies, and inventory optimization to sustain profitability
- While 8 AM–11 AM remains the dominant revenue window, implement targeted promotions, loyalty rewards, or bundled offers in the afternoon and evening—particularly for Hell’s Kitchen and Lower Manhattan—to extend customer engagement beyond morning peaks
- Given the low return of approximately $3,000 in total revenue at 8:00 PM, evaluate the cost-effectiveness of extended hours for Hell’s Kitchen and Lower Manhattan. Consider either adjusting closing times or introducing evening-specific draws such as live events, dessert specials, or limited-edition beverages to stimulate demand
- For consistently low-revenue items such as Green Beans, Green Tea, Organic Chocolate, and Packaged Chocolate, potentially test different product strategies such as short-term promotions or even seasonal rotations to assess the potential of these products, and discontinue offerings that fail to meet minimum sales or profitability benchmarks

## Limitations

- The dataset only spans January to June 2023, restricting the ability to perform true year-over-year comparisons or assess long-term seasonal patterns. This also limits forecasting accuracy for future performance
- Although product-level revenue and quantity sold are available, full cost data for every item is not provided, making it impossible to calculate precise profit margins for all products
