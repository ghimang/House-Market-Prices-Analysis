# 🏠 House Market Dashboard – Power BI
Overview
This Power BI dashboard provides a comprehensive analysis of the housing market, focusing on regional trends, sales performance, pricing dynamics, and influential factors. The report is built using two primary tables:

Measures Table1: Contains calculated metrics such as average prices, growth rates, and sales summaries.

Housing Data: Contains granular transaction-level data including property details, pricing, dates, and regional information.

## 📊 Report Pages
### 1. House Market Overview
Median Sales Price Change by Region
Bar chart showing year-over-year change in median prices for Jutland, Zealand, Fyn & Islands, and Bornholm.

Units Sold
Latest number of units sold in the most recent year and quarter (77 units).

12 Month Sales
Total housing market transaction value: 13 billion.

Offer Price vs. Purchase Price
Scatter plot visualizing pricing consistency across the market.

YOY Sales Growth by Sales Type
Line chart showing Year-Over-Year growth by sales type:

Auction: +0.29

Regular/Other: -0.21

Family Sale: -0.75

### 2. Sales Performance
Sales by Region
Spline area chart indicating total sales volume:

Zealand: 95bn

Jutland: 81bn

Fyn & Islands: 15bn

Key Influencers
Analyzed factor: Age (2–17) contributes to an average price increase of 411.5K.

Offer to SQM Ratio by Sales Type
Bar chart showing price-per-square-meter:

Regular Sale: 15K

Other Sale: 14K

Family Sale: 12K

Auction: 11K

Average Price SQM by Region
Donut chart showing average price per square meter:

Zealand: 20.85K

Fyn & Islands: 13.62K

Jutland: 13K

Bornholm: 10.6K

## 📁 Data Model
Tables Used
### ✅ Measures Table1
Average Price SQM

Last 12 Month Sales

Median Sales Price Change

Offer to SQM Ratio

Sales by Region

TotalYTD Sales

Units sold in latest Year & Quarter

YOY_Sales_Growth

## ✅ Housing Data
%_change_between_offer_and_purchase

Age, area, city, region, zip_code

sales_type, house_type, house_id

Offer Price, purchase_price, sqm, sqm_price

date(MM/DD/YYYY), quarter, year_build

nominal_interest_rate, dk_annual_inflation_rate

yield_on_mortgage_credit_bonds, no_rooms

## 📌 Key Insights
Zealand leads in both average pricing and total sales.

Family sales are experiencing the steepest sales decline (-0.75 YOY).

Despite low sales growth, auctions show positive YOY growth and lower price-per-sqm.

Younger age groups (2–17) show a positive influence on purchase price.

## 🛠️ Tools Used
Microsoft Power BI

DAX (for Measures)

Data Model with Relationships between Measures Table and Housing Data
