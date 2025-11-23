# Sales Analytics Dashboard (Excel)

This project is a **Sales Analytics Dashboard** created entirely in **Microsoft Excel**. It allows you to analyze sales data, track revenue, profit, and costs, and visualize insights using **Excel functions and pivot tables**.

---

## Dataset

The dataset includes the following columns:

| Column Name      | Description                                 |
| ---------------- | ------------------------------------------- |
| Date             | Date of the transaction                     |
| Day              | Day of the week                             |
| Month            | Month of the transaction                    |
| Year             | Year of the transaction                     |
| Customer_Age     | Age of the customer                         |
| Age_Group        | Customer age group (e.g., 18-25, 26-35)     |
| Customer_Gender  | Gender of the customer                      |
| Country          | Customer country                            |
| State            | Customer state/region                       |
| Product_Category | Main category of the product                |
| Sub_Category     | Sub-category of the product                 |
| Product          | Product name                                |
| Order_Quantity   | Quantity of the product ordered             |
| Unit_Cost        | Cost per unit of the product                |
| Unit_Price       | Selling price per unit of the product       |
| Profit           | Profit from the order                       |
| Cost             | Total cost (Order_Quantity × Unit_Cost)     |
| Revenue          | Total revenue (Order_Quantity × Unit_Price) |
| Payment          | Payment method used                         |

---

## Project Workflow

1. **Data Collection**

   * Gathered sales data in Excel from company records or sample datasets.

2. **Data Preparation & Cleaning**

   * Structured the dataset with proper columns.
   * Removed duplicates and ensured correct data types.

3. **Excel Calculations**

   * **Revenue**: `=Order_Quantity * Unit_Price`
   * **Cost**: `=Order_Quantity * Unit_Cost`
   * **Profit**: `=Revenue - Cost`
   * Used **SUM()**, **IF()**, **VLOOKUP()**, **SUMIF()** to analyze data.

4. **Pivot Tables & Charts**

   * Created pivot tables to summarize data by:

     * Product or Product Category
     * Month or Year
     * Customer demographics (Age Group, Gender, Region)
   * Generated charts directly from pivot tables:

     * Bar charts for sales by product
     * Line charts for monthly revenue trends
     * Pie charts for customer demographics

---

## Objective

The main goal of this project is to **analyze sales data efficiently** and provide actionable insights:

* Track total sales, revenue, and profit
* Identify high-performing products and categories
* Understand customer demographics and regional sales trends
* Visualize trends over time for better decision-making

---

## Technologies Used

* **Microsoft Excel**

  * Functions: `SUM()`, `IF()`, `VLOOKUP()`, `SUMIF()`
  * Pivot Tables for summarizing data
  * Charts (Bar, Line, Pie) for visualization

---

## Future Enhancements

* Add slicers and filters for interactive analysis
* Incorporate conditional formatting for visual insights
* Extend to multi-sheet dashboards for larger datasets
* Export dashboard reports for presentations

---

This project demonstrates a complete workflow in **Excel**: from **data collection → preparation → cleaning → calculations → pivot tables → charts**, providing clear insights on **sales, revenue, and profit**.
