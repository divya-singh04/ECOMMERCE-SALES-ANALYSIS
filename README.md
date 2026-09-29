# ECOMMERCE-SALES-ANALYSIS

# 📊 E-Commerce Sales Analysis Dashboard

An interactive Excel dashboard that turns nearly 10,000 order lines into a clear story: what's selling, where it's selling, and whether it's actually making money.

![Dashboard preview](Dashboard_Preview.png)

## Why I built it

Sales numbers alone can be misleading. A category can look like a hero on revenue and quietly lose money on profit. I built this dashboard to see the full picture at a glance, and to let anyone slice it by year, customer segment, and region in a single click.

## What's inside

**KPI cards** (with trend lines and year-over-year growth)
- Sales
- Profit
- Quantity
- Number of Orders
- Profit Margin

**Charts**
- **Sales and Profit Analysis**: monthly sales vs. profit, to spot seasonality and loss-making months
- **Category-wise Profit**: waterfall chart showing how Furniture, Office Supplies and Technology add up to total profit
- **Category-wise Sales Share %**: donut chart of each category's slice of sales
- **Sales by State**: US map shaded by sales volume
- **Top 5 Sub-Categories by Sales**: Appliances, Phones, Chairs, Storage, Paper

**Filters (slicers)**
- Year (2011–2014)
- Segment (Consumer, Corporate, Home Office)
- Region (Central, East, South, West)

## What the dashboard shows

The screenshot is filtered to **2013 · Home Office · Central**:

| Metric | Value | YoY |
|---|---|---|
| Sales | $20,008.23 | ▲ 20.62% |
| Profit | $2,217.00 | ▲ 14.41% |
| Quantity | 430 | ▲ 14.41% |
| Orders | 107 | ▲ 28.64% |
| Profit Margin | 11.08% | ▼ 5.15% |

**Things worth noticing in this view**
- Sales, profit and orders grew year over year, but profit margin slipped, so growth came at a cost.
- **Furniture is loss-making** (about −$642K on the waterfall) and is the only category dragging profit down.
- **Office Supplies is the biggest sales driver at 46.36%**, and Furniture holds the smallest share at 25.75%.

> All figures change with the slicers. Clear the filters to see the full 2011–2014, all-segment, all-region picture.

## Dataset

- **Sheet:** `Data`, 9,994 rows covering orders from Jan 2011 to Dec 2014
- **Geography:** United States, 49 states, 4 regions
- **Columns:** Order ID, Order/Ship Date, Ship Mode, Customer, Segment, State, City, Region, Category, Sub-Category, Product, Sales, Quantity, Discount, Profit
- **Categories:** Furniture, Office Supplies, Technology

## How it's built

- **Tool:** Microsoft Excel
- **Pivot Tables** feed every chart and KPI (supporting sheets: `Sheet1`–`Sheet3`)
- **Slicers** are connected to all pivots so the whole dashboard filters together
- **Charts:** combo (area + column), waterfall, donut, map, bar, and sparklines-style trend lines
- **Layout:** the `layout` sheet holds the final dashboard

## How to use it

1. Download `Ecommerce_Sales_Analysis.xlsx` and open it in Excel (2016 or later, since the waterfall and map charts need it).
2. Go to the dashboard sheet.
3. Click the **Year**, **Segment** and **Region** slicers. Hold `Ctrl` to select multiple values.
4. Use the clear-filter icon on each slicer to reset.

## Skills demonstrated

Data cleaning · Pivot Tables · Slicers · KPI design · YoY analysis · Dashboard layout · Data storytelling

## Author

**Divya**: aspiring Data Analyst based in Mumbai.
Let's connect on LinkedIn: _add your link here_
