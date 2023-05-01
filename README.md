Download Link: https://assignmentchef.com/product/solved-bit-3444-homework-6-typed-dataset-drag-n-drop-and-linq-query
<br>
<u>Homework 6 Submission</u>: This is an individual homework assignment. Compress your complete VB project folder into a .zip file. The file name should have the format: 6_LastName_F.zip. Upload the .zip file to our homework submission site.

You will develop <strong>MyBroker</strong> v3.0 using a typed DataSet and LINQ queries.

<strong> </strong><strong>Database File: </strong>Please use the StocksDB database file that I posted for Homework 5.

Alternatively, you can use your own database provided that the database design is correct. <strong> </strong>

<strong>Typed DataSet</strong>: Develop a typed DataSet application using the Drag-N-Drop technique.

<h1>(100 Points)</h1>

<ul>

 <li>Use the Drag-N-Drop technique to develop this application, which is used to browse, add, modify, delete, and save stock trading request records. The user interface, after applying the Drag-N-Drop technique, should look like the following screenshot. Please make sure that the three <strong>ComboBox</strong> Controls are used to display the stock ticker value, order type value, and request status value, respectively. You should drag the TradingRequests <strong>DataTable</strong> and drop it on the form. Do NOT drag individual fields from different <strong>DataTable</strong> <strong>(25 Points)</strong></li>

</ul>




<ul>

 <li>Modify the data binding settings of the first <strong>ComboBox</strong> control showing stock ticker symbol. Instead of showing ticker symbol, the ComboBox controls should display the corresponding company’s full name for the user’s convenience. <strong>(25 Points)</strong></li>

</ul>

Parameterized Query: Create a parameterized query so that the user can search for trading requests by order type. The ability to conduct a partial search is not necessary. (<strong>10 Points</strong>)




<ul>

 <li>LINQ Query 1: Add a search <strong>TextBox</strong>, a search <strong>ToolStripButton</strong>, and a reset <strong>ToolStripButton</strong> on the <strong>BindingNavigator</strong> You should assign an appropriate icon image to each of the <strong>ToolStripButton</strong> objects. The user can use these newly created objects to search trading request records by ticker symbol. The user types a ticker symbol in the search <strong>TextBox</strong>. When the user clicks the search <strong>ToolStripButton</strong>, your program should use a LINQ query to search those trading requests made for the specified ticker symbol. When the user clicks the reset Button, your program should reset the search result to display all trading requests. <strong>(20 Points) </strong></li>

</ul>




<ul>

 <li>LINQ Query 2: For the stock ticker currently selected in the company ComboBox control, create LINQ queries to display the total stock quantity of BUY tradining requests and total stock quantity of SELL tradining requests. Display both quantities on the user form by placing more Windows controls (e.g., TextBox and Label controls). <strong>(20 Points) </strong></li>

</ul>

<strong> </strong>