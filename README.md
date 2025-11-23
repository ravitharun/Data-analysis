# Sales Analytics Dashboard (Excel)

This project is a **Sales Analytics Dashboard** created entirely in **Excel**. It allows you to analyze sales data, track revenue, profit, and costs, and visualize insights using Excel charts and functions.

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

2. **Data Preparation**

   * Organized the data into structured columns.
   * Checked for missing or inconsistent entries.

3. **Data Cleaning**

   * Removed duplicates and irrelevant data.
   * Ensured proper data types (dates, numbers, categories).

4. **Excel Calculations**

   * **Revenue**: `=Order_Quantity * Unit_Price`
   * **Cost**: `=Order_Quantity * Unit_Cost`
   * **Profit**: `=Revenue - Cost`
   * Used **SUM()** function to calculate total Revenue, Cost, and Profit for summary analysis.

5. **Dashboard Visualization**

   * Created interactive **Excel charts** to display:

     * Bar charts for sales per product or category
     * Line charts for monthly revenue and profit trends
     * Pie charts for customer demographics (age group, gender)
     * Regional sales analysis with conditional formatting or maps

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

  * Functions: `SUM()`, `IF()`, `VLOOKUP()`, `SUMIF()`, etc.
  * Charts: Bar, Line, Pie, and conditional formatting for dashboards

---

## Future Enhancements

* Add slicers and filters for interactive analysis
* Use pivot tables for dynamic summary reports
* Incorporate advanced Excel formulas for forecasting sales trends
* Export Excel dashboard to PDF or PowerPoint for reporting

---

This Excel project demonstrates the full workflow from **data collection → preparation → cleaning → calculation → visualization**, providing a clear picture of sales, revenue, and profit for decision-making.
