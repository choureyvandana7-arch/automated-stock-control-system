# 📦 Inventory & Stock Reorder Management System

## 📌 Project Overview

The **Inventory & Stock Reorder Management System** is an MS Excel-based project designed to manage product inventory, monitor stock availability, identify low-stock products, and calculate reorder quantities automatically.

This project helps businesses maintain proper inventory records, avoid stock shortages, and make better purchasing decisions using Excel formulas, charts, dashboards, and conditional formatting.

## 🎯 Project Objectives

- To maintain product and inventory records.
- To monitor current stock availability.
- To identify products that need to be reordered.
- To calculate reorder quantities automatically.
- To calculate the total value of available inventory.
- To maintain purchase order records.
- To present inventory information through charts and dashboards.

## 🛠️ Tools & Technologies Used

- Microsoft Excel
- Excel Formulas and Functions
- Excel Charts and Graphs
- Conditional Formatting
- Data Validation
- Tables and Filters
- GitHub

## 📂 Project Structure

The workbook contains five worksheets:

### 1. Inventory Management Sheet
- Product ID and Product Name
- Product Category
- Supplier Details
- Unit Cost
- Current Stock
- Reorder Level
- Target Stock
- Automatic Reorder Quantity
- Stock Value
- Stock Status
- Last Updated Date
- Lead Time and Remarks

### 2. Dashboard
The dashboard provides a visual summary of inventory performance.

It displays:
- Total Number of Products
- Total Units in Stock
- Products to Reorder
- Out-of-Stock Products
- Total Inventory Value
- Total Units to Reorder
- Products Currently in Stock

**Charts included:**
- Pie Chart – Products by Stock Status
- Bar Chart – Inventory Value by Category
- Comparison Chart – Current Stock vs Reorder Level

### 3. Reorder Report
This worksheet identifies products that require replenishment.

It displays:
- Product Name
- Supplier
- Current Stock
- Reorder Level
- Target Stock
- Reorder Quantity
- Estimated Order Cost

### 4. Purchase Log
This sheet maintains purchase order records, including:
- Order ID
- Order Date
- Product ID
- Product Name
- Supplier
- Quantity Ordered
- Unit Cost
- Total Order Cost

### 5. Project Guide
Contains the project introduction, objectives, working process, formulas, features, and conclusion.

## 🧮 Excel Formulas Used

| Excel Function | Purpose |
|---|---|
| IF() | Determines stock status and reorder quantity |
| MAX() | Prevents negative reorder quantities |
| SUM() | Calculates total stock and inventory value |
| COUNTIF() | Counts products according to stock status |
| COUNTA() | Counts total products |
| SUMIF() | Calculates inventory value by category |
| FILTER() | Displays products that need reordering |

### Important Calculations

**1. Reorder Quantity**

If Current Stock is less than or equal to Reorder Level:

Reorder Quantity = Target Stock - Current Stock

Otherwise, Reorder Quantity = 0.
# 📦 Inventory & Stock Reorder Management System

## 📌 Project Overview

The **Inventory & Stock Reorder Management System** is an MS Excel-based project designed to manage product inventory, monitor stock availability, identify low-stock products, and calculate reorder quantities automatically.

This project helps businesses maintain proper inventory records, avoid stock shortages, and make better purchasing decisions using Excel formulas, charts, dashboards, and conditional formatting.

## 🎯 Project Objectives

- To maintain product and inventory records.
- To monitor current stock availability.
- To identify products that need to be reordered.
- To calculate reorder quantities automatically.
- To calculate the total value of available inventory.
- To maintain purchase order records.
- To present inventory information through charts and dashboards.

## 🛠️ Tools & Technologies Used

- Microsoft Excel
- Excel Formulas and Functions
- Excel Charts and Graphs
- Conditional Formatting
- Data Validation
- Tables and Filters
- GitHub

## 📂 Project Structure

The workbook contains five worksheets:

### 1. Inventory Management Sheet
- Product ID and Product Name
- Product Category
- Supplier Details
- Unit Cost
- Current Stock
- Reorder Level
- Target Stock
- Automatic Reorder Quantity
- Stock Value
- Stock Status
- Last Updated Date
- Lead Time and Remarks

### 2. Dashboard
The dashboard provides a visual summary of inventory performance.

It displays:
- Total Number of Products
- Total Units in Stock
- Products to Reorder
- Out-of-Stock Products
- Total Inventory Value
- Total Units to Reorder
- Products Currently in Stock

**Charts included:**
- Pie Chart – Products by Stock Status
- Bar Chart – Inventory Value by Category
- Comparison Chart – Current Stock vs Reorder Level

### 3. Reorder Report
This worksheet identifies products that require replenishment.

It displays:
- Product Name
- Supplier
- Current Stock
- Reorder Level
- Target Stock
- Reorder Quantity
- Estimated Order Cost

### 4. Purchase Log
This sheet maintains purchase order records, including:
- Order ID
- Order Date
- Product ID
- Product Name
- Supplier
- Quantity Ordered
- Unit Cost
- Total Order Cost

### 5. Project Guide
Contains the project introduction, objectives, working process, formulas, features, and conclusion.

## 🧮 Excel Formulas Used

| Excel Function | Purpose |
|---|---|
| IF() | Determines stock status and reorder quantity |
| MAX() | Prevents negative reorder quantities |
| SUM() | Calculates total stock and inventory value |
| COUNTIF() | Counts products according to stock status |
| COUNTA() | Counts total products |
| SUMIF() | Calculates inventory value by category |
| FILTER() | Displays products that need reordering |

### Important Calculations

**1. Reorder Quantity**

If Current Stock is less than or equal to Reorder Level:

Reorder Quantity = Target Stock - Current Stock

Otherwise, Reorder Quantity = 0.

**2. Stock Value**

Stock Value = Unit Cost × Current Stock

**3. Total Order Cost**

Total Order Cost = Quantity Ordered × Unit Cost

**4. Stock Status**

- OUT OF STOCK – Current stock is zero.
- REORDER – Current stock is at or below the reorder level.
- IN STOCK – Current stock is above the reorder level.

## ✨ Key Features

- Automatic stock reorder calculation.
- Automatic inventory value calculation.
- Low-stock identification.
- Out-of-stock alerts.
- Interactive-style dashboard with visual charts.
- Purchase order tracking.
- Conditional formatting for stock status.
- Data validation to reduce incorrect entries.
- Excel tables with sorting and filtering.
- Sample data for 20 products.

## ▶️ How to Use the Project

1. Download the Excel workbook from this repository.
2. Open it using Microsoft Excel.
3. Navigate to the Inventory worksheet.
4. Update the sample product details and stock quantities.
5. Enter the unit cost, reorder level, and target stock.
6. The Excel formulas automatically calculate reorder quantities, stock values, and stock status.
7. Check the Dashboard to view inventory performance.
8. Open the Reorder Report to identify products requiring new stock.
9. Use the Purchase Log to maintain purchase records.

**Note:** The Reorder Report uses the Excel FILTER function, which requires a compatible version of Microsoft Excel, such as Microsoft 365 or Excel 2021 and later.

## 📊 Sample Project Data

This workbook contains sample inventory data for 20 products across different categories, including:

- Electronics
- Accessories
- Stationery
- Office Supplies

The sample data is provided for demonstration purposes and can be replaced with actual business inventory records.

## 🎓 Learning Outcomes

Through this project, I learned how to:

- Create an inventory management system using MS Excel.
- Apply Excel formulas and functions.
- Automate stock reorder calculations.
- Use conditional formatting and data validation.
- Create dashboards using charts and graphs.
- Organize and analyze inventory data.
- Manage project files using GitHub.

## 🏁 Conclusion

The Inventory & Stock Reorder Management System provides an efficient way to monitor inventory, identify stock shortages, calculate reorder quantities, and track purchase records.

By using Excel formulas, charts, and dashboards, this project makes inventory management easier, more organized, and more effective.

---

**Project Name:** Inventory & Stock Reorder Management System  
**Technology:** Microsoft Excel  
**Project Type:** Excel Data Management Project  
**Repository:** GitHub# automated-stock-control-system
