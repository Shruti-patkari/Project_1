**Mobile Management System**
 
 **Customer Details – README**

This VB.NET Windows Forms app loads customer records from an Access database and shows each customer’s sale items.

 **Features**

* Load customers from `customertable`
* Navigate: First, Last, Next, Previous
* Display sale items from `saleitemdetails` in a DataGridView
* Insert new customer records
* Close the form

 **How it Works**

* On form load, customers are loaded into a DataSet.
* Navigation changes the row index and updates the textboxes.
* `navigate()` loads sale items for the selected customer.
* `btnclear` inserts a new record into the database.

 **Database**

* `customertable`: customer info
* `saleitemdetails`: sale items linked by `custautoid`

**Requirements**

* VB.NET
* Access Database (.mdb / .accdb)
* OleDb Provider

**Project is done by-
SHRUTI PATKARI.**
