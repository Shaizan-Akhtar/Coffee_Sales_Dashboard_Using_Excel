# Coffee_Sales_Dashboard_Using_Excel

Dashboard Creation Summary:
I worked on a project to create a comprehensive dashboard using data from an Excel spreadsheet. The spreadsheet contained three sheets: Orders, Customers, and Products.

Data Preparation:

Orders Sheet:
Contained columns for Order ID, Order Date, Customer ID, Product ID, and Quantity.

Customers Sheet:
Contained columns for Customer Name, Email, Phone Number, Address Line 1, City, Country, Postal Code, and Loyalty Card.

Products Sheet:
Contained columns for Product ID, Coffee Type, Roast Type, Unit Price, Price per 100g, and Profit.

Steps Performed:

Data Integration Using VLOOKUP:
I used the VLOOKUP function to pull the Customer Name, Email, and Country from the Customers Sheet into the Orders Sheet.

Dynamic Lookup with INDEX and MATCH:
I applied the INDEX and MATCH functions to retrieve Coffee Type, Roast Type, Size, and Unit Price from the Products Sheet into the Orders Sheet for each order.

Sales Calculation:
I calculated the sales for each order by multiplying the Quantity column with the Unit Price column.

Coffee Type Abbreviation with IF():
I used the IF function to create a simplified coffee type abbreviation:

Rob for Robusta
Exc for Excelsa
Ara for Arabica
Lib for Liberica

Duplicate Check:
To ensure data accuracy, I checked for duplicate entries in the dataset. Thankfully, no duplicates were found.

Date Formatting:
Reformatted the Order Date column to display dates in the "dd-mmm-yyyy" format for better readability.

Size Column Customization:
Reformatted the Size column values (e.g., 1, 1.2, 0.5) to include one decimal place and added the unit "kg". The custom format used was:

Currency Formatting:
To make the Unit Price and Sales columns more recognizable, I formatted them to represent prices in USD.

Converting Data into a Table:
I converted the entire dataset into an Excel table for better organization and easier manipulation.

Dashboard Creation:
Sales by Coffee Type Over Time:

Created a Pivot Table to analyze sales by coffee type over time.
Grouped the dates by Year and Month to make the data more intuitive.
Created a Line Chart from the pivot table to visualize trends.
Added a Timeline Filter for the Order Date to enable dynamic time-based filtering.
Slicers for Interactivity:

Added three slicers for Roast Type, Coffee Type, and Loyalty Card to enhance interactivity.

Sales by Country:

Created a Pivot Table to analyze sales by country.
Built a Bar Chart to visualize country-wise sales, sorted by sales values in descending order.
Top 5 Customers by Sales:

Created another Pivot Table to identify the top 5 customers with the highest sales.
Created a Bar Chart for this data to visualize the results effectively.
Final Dashboard Layout:

On a new sheet, I combined all the visualizations, including the Line Chart, Bar Charts, and Slicers, to create the final dashboard.
The dashboard is interactive, allowing users to filter by time, roast type, loyalty card, and more.
