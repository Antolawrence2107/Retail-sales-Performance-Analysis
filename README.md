# Retail-sales-Performance-Analysis
To analyze retail sales data using Excel and Power BI to identify sales trends, top-performing products, and customer behavior. 
Tools Used:
o	Microsoft Excel: Data Cleaning, Transformation, and Validation
o	Power BI: Data Modeling, DAX Calculations, and Dashboard Creation


Data Cleaning & Transformation (Excel)
o	Performed data preparation and cleaning using Excel before importing into Power BI:
o	Removed missing, duplicate, and inconsistent entries
o	standardized date and numeric formats (e.g., SaleDate, Quantity)
o	Used Excel formulas like TRIM, IFERROR, and VLOOKUP for corrections
o	Merged multiple sheets (Customers, Products, Stores, Sales) for integration
o	Ensured consistency between CustomerID, ProductID, and StoreID
o	Added calculated columns (Total Amount = Quantity × Unit Price)
o	Result: A clean and transformed dataset ready for Power BI modeling.

Data Modeling (Power BI)
Schema Type: Star Schema
Relationships:
o	Sales → Customers (CustomerID)
o	Sales → Products (ProductID)
o	Sales → Stores (StoreID)


Dashboard Design
Visuals Used:
o	KPI Cards: Total Sales, Quantity, Customers, stores, sales Profit 
o	Line Chart: Sales Trend over Time 
o	Bar Chart: Sales by Category & Sub Category
o	Donut Chart: Sales by Gender
o	Map: Sales by State 
o	Line Chart: Stores sale by Month
o	Scatter Chart – Unit Price vs Quantity

