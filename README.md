# Sale-and-Shipment-Analysis
![](images/sale_logistics.jpg)
## 1. Abstract
This dashboard presents key insights, offering a comprehensive overview of sales and shipment performance in Power BI.
  - The Sales Performance Dashboard showcases sales trends over recent years while providing detailed insights into the sales team's performance. Track employee progress and performance through Year-over-Year (YoY) reports on top-performing sales executives, measured by revenue generated and units sold. Additionally, analyze individual sales locations using interactive maps, covering countries and top regional customers.

  - The Shipment Performance Dashboard provides an in-depth analysis of annual shipping performance. Gain a clear overview of shipment delays and better understand high-value customers to optimize operations and strengthen business relationships.

## 2. Data source
Originally crafted by Microsoft, the Northwind database has served as a sample database foundation for their instructional materials across a range of database products for numerous years. Within the Northwind database lies the sales data of the fictional enterprise "Northwind Traders," engaged in the global import and export of specialty foods.
And here is the link: [HERE](https://drive.google.com/drive/folders/1sNHbkw6k1TcuiePujyqh3pWCCi9CXa9c?usp=drive_link)

## 3. Methodology
### a. Data Model
Firstly, I need to import all the tables into Power BI. Then, check all the relationships that were automatically created is correct or not.
### b. Create a calendar table
Because this data is analyzed based on dates so much, it is necessary to create a calendar to manage all dates for all tables. I used DAX to create it because the structure contains a lot of Date columns.
