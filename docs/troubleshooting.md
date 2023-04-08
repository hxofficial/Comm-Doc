# **Troubleshooting**

## **1 - Error connecting to database**

Open System Settings > MySQL and click "Start MySQL server".

## **2 - Error entering data into table**

### **2.1 - Fill in all required fields**

Make sure that all columns are filled in before pressing "Apply". Do not enter data into columns set to Auto Increment.

### **2.2 - Click outside of cell**

Make sure that the cell for the last piece of data that you entered is not highlighted before pressing "Apply". Click the background of the "Result Grid" to deselect the cell.

## **3 - Error creating FK**

Make sure that the datatype of the foreign key column is the same as the datatype of the primary key in the reference table.

## **4 - Forgot root password for localhost database**

[This guide in the MySQL reference manual](https://dev.mysql.com/doc/refman/8.0/en/resetting-permissions.html) explains how to reset the root password created during instiallation of MySQL. Remembering this password is essential in order to connect to the localhost database.
