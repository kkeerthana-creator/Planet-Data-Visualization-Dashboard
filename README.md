# Case Study 2 - Power BI Report

This is my Power BI dashboard for the shipments case study.

## What's in it

I built this using 6 tables:
- **Shipments** - the main fact table with Boxes and Amount data
- **Dimension Data** - has Product, Geo, and Cost_per_box info
- **Calendar** - date table with month_name for filtering
- **products** - product reference table (Cost_per_box)
- **people** - has the Team info
- **locations** - geo/location reference data

## Pages

**Page 1**
- Month slicer to filter everything
- Bar chart showing Cost_per_box by month

**Page 2**
- Column chart: Boxes shipped by Product
- Bar chart: Amount by Product

**Page 3**
- Pie chart: Boxes by Team
- Line chart: Cost_per_box by Product

**Page 4**
- Map showing shipments by Geo

## Notes
- Used the default Fluent theme, didn't rename the pages or add custom titles yet
- Export is set to allow summarized data
- Made with Power BI Desktop
