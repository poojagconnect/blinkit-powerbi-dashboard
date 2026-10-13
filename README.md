# blinkit-powerbi-dashboard
Interactive Power BI dashboard analysing Blinkit grocery sales by item type, outlet size, location and outlet type.

# Blinkit Sales Analysis Dashboard

An interactive Power BI dashboard that analyses Blinkit grocery sales data to identify top-performing and lagging segments.

## Live Dashboard
https://alliancebschool-my.sharepoint.com/:u:/g/personal/gpoojamba25_aac_alliance_edu_in/IQDxh4jCHBUgSIgItwcOswKKATznY5BhpnZn30RNH8cGWo0?e=RZTu65

## Dashboard Preview
<img width="874" height="476" alt="image" src="https://github.com/user-attachments/assets/0c531652-fcbf-435e-84fa-b35aef3b91a4" />
<img width="725" height="365" alt="image" src="https://github.com/user-attachments/assets/e3dbfb1c-3206-4a77-ac79-d77b21f68ad3" />
<img width="803" height="355" alt="image" src="https://github.com/user-attachments/assets/6747cfcf-655e-465b-9935-0d073bebd20a" />

## KPIs Tracked
| KPI | Value | How it is calculated |
|---|---|---|
| Total Sales | 1.20M | Sum of Sales |
| Average Sales | 141 | Average of Sales per item |
| Number of Items | 8,523 | Count of records |
| Average Ratings | 3.9 | Average of Rating |

## Analysis Covered
- Sales by item type and fat content
- Sales by outlet size, outlet location type and outlet type
- Sales by outlet establishment year
- Item visibility, ratings and sales compared by outlet type

## Features
- Slicers to filter by outlet location type, outlet size and item type
- Dynamic metric selector to switch between Total Sales, Average Sales, Number of Items and Average Ratings

## Key Insights
- **Supermarket Type1 dominates sales:** it contributes about 787.5K, or 65.5% of total sales, from 5,577 items. Grocery Store (151.9K), Supermarket Type2 (131.5K) and Type3 (130.7K) each contribute only 11-13%.
- **Fruits & Vegetables and Snack Foods lead item types:** together they bring in about 29% of sales (178.1K and 175.4K). Seafood, Breakfast and Starchy Foods are the weakest categories, each under 2%.
- **Tier 3 cities lead on location:** Tier 3 generates 472.1K (39.3%), ahead of Tier 2 (393.2K) and Tier 1 (336.4K).
- **Medium-sized outlets sell the most:** they account for 42.3% of sales (507.9K), ahead of Small (37.0%) and High (20.7%).
- **Outlets established in 2018 are the top year group:** they contribute 204.5K (17.0%), well above the other years (about 130K each). Outlets from 2011 are the lowest at 78.1K.
- **Low Fat items make up 64.6% of sales** (776.3K) against 35.4% for Regular items.
- **Sales are driven by volume, not price or ratings:** average sales per item (about 141) and average ratings (about 3.9) are nearly the same across all segments, so the segments with more items sell more.
- **Grocery Stores have the highest item visibility** (0.10 against about 0.06 for supermarkets) but contribute only 12.6% of sales, so higher visibility does not mean higher sales.

## Data Preparation
- Cleaned the Item Fat Content column in Power Query by standardising "LF", "low fat" and "reg" into "Low Fat" and "Regular".
- Set correct data types for all 12 columns.
- Created DAX measures for Total Sales, Average Sales, No of items and Average Ratings.

## Tools Used
Power BI, DAX, Power Query, Microsoft Excel

## Dataset
BlinkIT Grocery Data (Excel file): 8,523 item-level records with 12 columns: Item Identifier, Item Type, Item Fat Content, Item Weight, Item Visibility, Sales, Rating, Outlet Identifier, Outlet Establishment Year, Outlet Size, Outlet Location Type and Outlet Type.
