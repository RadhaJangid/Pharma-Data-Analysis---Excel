#RRGGBB
# Pharma-Data-Analysis - Excel 

In this 'Data Analysis' project, we'll analyze a global Pharmaceutical Manufacturing Company's raw sales data and draw meaningful insights.
	
## Overview -

This project represents my work as an intern at Psyliq, where I had the opportunity to analyze a dataset related to the pharmaceutical industry. Using Excel, I conducted a comprehensive analysis and successfully completed the project.
	
## Dataset Info -
<div class="w3-container">
	<table class="w3-table-all w3-card-4">
		    <tr>
		      <th>COLUMN NAME</th>
		      <th>DATA TYPE</th>
		      <th>DESCRIPTION</th>
		    </tr>
		    <tr>
		      <td>Distributor</td>
		      <td>string</td>
		      <td>Name of Wholesaler</td>
		    </tr>
		    <tr>
		      <td>Customer Name</td>
		      <td>string</td>
		      <td>Name of customer</td>
		    </tr>
		    <tr>
		      <td>City</td>
		      <td>string</td>
		      <td>Customer's city</td>
		    </tr>
		    <tr>
		      <td>Country</td>
		      <td>string</td>
		      <td>Customer's country</td>
		    </tr>
		    <tr>
		        <td>Latitude</td>
		        <td>decimal</td>
		        <td>Customer's Geo Latitude</td>
		    </tr>
		    <tr>
		        <td>Longitude</td>
		        <td>decimal</td>
		        <td>Customer's Geo Longitude</td>
		    </tr>
		    <tr>
		        <td>Channel</td>
		        <td>string</td>
		        <td>Class of buyer (Hospital, Pharmacy)</td>
		    </tr>
		    <tr>
		        <td>Sub-channel</td>
		        <td>string</td>
		        <td>Sector of the buyer (Government, Private, etc.)</td>
		    </tr>    
		    <tr>
		      <td>Product Name</td>
		      <td>string</td>
		      <td>Name of Drug</td>
		    </tr>
		    <tr>
		      <td>Product Class</td>
		      <td>string</td>
		      <td>Class of Drug (Antibiotics, etc.)</td>
		    </tr>
		    <tr>
		      <td>Quantity</td>
		      <td>integer</td></td>
		      <td>Quantity purchased</td>
		    </tr>
		    <tr>
		      <td>Price</td>
		      <td>integer</td>
		      <td>Price product was sold for</td>
		    </tr>
		    <tr>
		        <td>Sales</td>
		        <td>decimal</td>
		        <td>Amount made from sale</td>
		    </tr>
		    <tr>
		      <td>Month</td>
		      <td>date</td>
		      <td>Month sale was made</td>
		    </tr>
		    <tr>
		      <td>Year</td>
		      <td>integer</td>
		      <td>Year sale was made</td>
		    </tr>
		    <tr>
		      <td>Name of Sales Rep</td>
		      <td>string</td>
		      <td>Name of the Sales rep who facilitated the sale</td>
		    </tr>
		    <tr>
		        <td>Manager</td>
		        <td>string</td>
		        <td>Sales rep's Manager Name</td>
		    </tr>
		    <tr>
		        <td>Sales Team</td>
		        <td>string</td>
		        <td>Sale rep's team</td>
		    </tr>
		</table>
 </div>
 
## Project Details - 
#### Internship : Psyliq
#### Domain/Field : Analytics
#### Project Type : Data Analysis
#### Tools Used:
* Excel


## Key Highlights -
### Objective

Conducted in-depth analysis of the pharmaceutical dataset. Utilized Excel to extract valuable insights from the data. Successfully completed the project, contributing to Psyliq's data analysis efforts.

### Loading Data
 Loaded the data into Microsoft Excel, applied:-
 
 **Basic formatting** is an essential step in presenting data in a clear and organized manner.It involves :-
 * Adjust the font size
 * Adjust column size
 * Highlight the header
 * Use different background colors
 * Center the title
 * Give borders around the ranges of values
 * Convert the given data range into table
      
 ### Data Cleaning & Processing
 - Assigning the correct data type to each column
 - Remove Duplicates
 - The "Quantity" and "Sales" columns contain negative values, indicating errors in data entry. To 
              remove these errors from the Quantity and Sales columns, we create two new columns called 
              Custom Quantity, Custom Sales and use ABS() to handle these negative values.
 - 183 values ​​in the City column have an encoding or display issue. To correct the values ​​we 
              create a separate table with two columns: one for the wrong values ​​and the other for the 
              correct values. This table will be used as reference for  improvements.
              VLOOKUP function is used to look up the correct value from the correction table in a new 
              column.
     
### Task
- Data is filtered to show only specific country records.
- The data is sorted in ascending order based on the "Sales" column.
- The data is summarized by calculating the total quantity of all products sold in the year 2023. 
- Conditional formatting applied to highlight all cells larger than $5,000 in the "Sales" column.
- Data validation is set to allow only specific cities from a predefined list in the "City" column.
- A pivot table has been created to summarize total sales by "channel".
- A bar chart is inserted to show sales quantity by "Product Category".
- Used the LOOKUP function to find the "Manager" for a specific "Sales Rep".
- Data is sorted by "Country" first in ascending order, and then in descending order by "month".
- Applied a filter  where "Product Category" is either "Antibiotic" or "Antiseptic".
- Added a calculated field to the pivot table to calculate the average price per unit sold.
- A line chart has been created to show the trend of total sales over the years.
- Nested IF function a is used to classify "sales" into three categories:low, medium and high
- Added slicers to pivot table to allow easy filtering by "month","Year."
- The existing pivot table is converted to a pivot chart.
- Used the INDEX and MATCH functions to find a "Sales Rep" for a specific "Customer Name".
- Applied a custom conditional format to highlight the top 10% of sales values with a distinct color.
- Scenario Manager is used to compare different scenarios for the future sales by changing variables like 
  "price" and "quantity".


## How to Use - 

I am attaching the link of, Excel file used for this  Data Analysis Project. Feel free to explore the code and findings.

## Acknowledgments -

I'd like to express my gratitude to Psyliq for providing me with this 
   valuable opportunity to work on this project and gain experience in data analysis.
