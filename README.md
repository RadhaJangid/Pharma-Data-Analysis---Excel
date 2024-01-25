<h1 style="font-family:verdana;">Pharma-Data-Analysis - Excel</h1> 
  <p>In this 'Data Analysis' project, we'll analyze a global Pharmaceutical     
     Manufacturing Company's raw sales data and draw meaningful insights.</p>
	
<h2 style="font-family:verdana;">Overview</h2>
  <p>This project represents my work as an intern at Psyliq, where I had the 
     opportunity to analyze a dataset related to the pharmaceutical industry. Using Excel, I conducted a 
     comprehensive analysis and successfully completed the project.</p>
	
<h2 style="font-family:verdana;">DATASET INFO</h2>
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
<h2 style="font-family:verdana;">Project Details</h2>
<h5 style="font-family:verdana;">Internship : Psyliq</h5>
<h5 style="font-family:verdana;">Domain/Field : Analytics</h5>
<h5 style="font-family:verdana;">Project Type : Data Analysis</h5>
<h5 style="font-family:verdana;">Tools Used:
<ul>
  <li>Excel</li>
</ul></h5>

<h2 style="font-family:verdana;">Key Highlights</h2>
<h4 style="font-family:verdana;">Objective</h4><hr width="5%" size="1" color="yellow">
<p style="font-family:courier;">Conducted in-depth analysis of the pharmaceutical dataset. Utilized Excel to extract valuable insights from the data. Successfully completed the project, contributing to Psyliq's data analysis efforts.</p>

<h4 style="font-family:verdana;">Loading Data</h4>
<p style="font-family:courier;">Loaded the data into Microsoft Excel, applied:-<br>
<i><b>Basic formatting- </b> is an essential step in presenting data in a clear and organized manner.<br> 
	It involves :-</i>
        <ul>
          <li>Adjust the font size</li>
          <li>Adjust column size</li>
          <li>Highlight the header</li>
          <li>Use different background colors</li>
          <li>Center the title</li>
          <li>Give borders around the ranges of values</li>
	  <li>Convert the given data range into table</li>
        </ul>
    </li>
  </p>
  <h4 style="font-family:verdana;">Data Cleaning & Processing</h4>
 <ul>
	  <li>Assigning the correct data type to each column</li>
	  <li>Remove Duplicates</li>
   	  <li>The "Quantity" and "Sales" columns contain negative values, indicating errors in data entry. To 
              remove these errors from the Quantity and Sales columns, we create two new columns called 
              Custom Quantity, Custom Sales and use ABS() to handle these negative values.</li>
	  <li>183 values ​​in the City column have an encoding or display issue. To correct the values ​​we 
              create a separate table with two columns: one for the wrong values ​​and the other for the 
              correct values. This table will be used as reference for  improvements.
              VLOOKUP function is used to look up the correct value from the correction table in a new 
              column.</li>    
	  
  </ul>

 <h2 style="font-family:verdana;">How to Use</h2>
 <p style="font-family:courier;">I am attaching the link of, Excel file used for this  Data Analysis Project. 
    Feel free to explore the code and findings.</p>

<h2 style="font-family:verdana;">Acknowledgments</h2>
<p style="font-family:courier;">I'd like to express my gratitude to Psyliq for providing me with this 
   valuable opportunity to work on this project and gain experience in data analysis.</p>
