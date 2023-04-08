# Task 2 - Creating Tables and Entering Data

## **Introduction**

In this guide, we will show you step-by-step how to create a new table in MySQL Workbench and add data to it. You will learn how to define the columns for your table, specify data types and properties, and enter data into the table.

**_Note:_** _The examples that we create below are referenced in Task 3 – Establishing Relationships Between Tables. Complete these examples if you want to follow the examples in Task 3_.

## **Creating Tables**

1. **Find and Double click** on the schema that you want to create a table in through the schema list.  
    ![image](/images/SelectSchema.png)  
   Once you have selected the schema, clicking on it will bring up a screen with multiple tabs.  
   ![image](/images/TableTab.png)  
   &nbsp;  

* **Right click** on the "Tables" tab and click on "Create Table". We named our table "term_1_courses".
   ![image](/images/SelectCreateTable.png)  
  You should see the “Edit Table Screen” and be prompted to enter a name for your new table.  
   &nbsp;  

* **Enter** a name for the table.  
![image](/images/SelectTableName.png)  
 We named our table "term_1_courses".  
  &nbsp;  

* **Click** on "<click to edit\>" to define the first column. For each column, you will need to enter a name, data type, and any properties that you want to assign to that column.  
  ![image](/images/Constraint.png)  
  For our example we added the following columns:  
  \- "course_id" with datatype `INT` and "PK", "NN", and "AI" checked,  
  \- "course_code" with datatype `TEXT` and "NN" checked,  
  \- "description" with datatype `TEXT` and "NN" checked,  
  \- "instructor_id" with datatype `INT`.  
   &nbsp;  
  _Note:_ _For reference on data types, visit the [MySQL Reference Manual section on data types][data types]._  
  &nbsp;  

* **Click** on the "Apply" button once you have defined all of your columns to create your new table. A pop-up window should appear displaying the MySQL query for creating the table.  
![image](/images/ApplyTabble.png)  
  &nbsp;  

* **Click** "Apply", then "Close".  

Congratulations! You have just created a table in MySQL Workbench, you can now begin adding data to your new table.

## **Entering Data**

1. **Click** on the schema where you created a table.  
   &nbsp;  

* **Click** on "Tables" to open the list  
  ![image](/images/TableTab.png)  
   &nbsp;  

* **Hover** your mouse over the table where you want to insert data. A row selection button <img src="/images/RowSelectionbtn.png" alt= “” width="30px" height="30px"> should appear.  
   &nbsp;  

* **Click** on the row selection button.Then you will see a "Data" tab, where you have all the columns that you created earlier in your table.  
  ![image](/images/DataTab.png)  
   &nbsp;  

* **Double click** on `NULL` underneath a column name. `NULL` should disappear and the area should be highlighted with a border.  
  ![image](/images/CourseCode.png)  
   &nbsp;  

* **Type** your data.  
  ![image](/images/TypeDataIn.png)  
   &nbsp;  

* **Continue** entering data for each column until you have entered all the data you want to insert into the row.  
  ![image](/images/completedcolumn.png)  
  We added a course called "COMM1116" with a description "Business Communications"  
   &nbsp;  
  **_Note:_** _When enterering a row of data, input can be empty when the column does not have the property "Not Null" (NN), or if it has the "Auto Increment" (AI) property._  
   &nbsp;  

* **Click** on the "Apply" button to insert the data into the table. A pop-up window should appear displaying the MySQL query for entering the data.  
  &nbsp;  

* **Click** "Apply", then "Close".  

Congratulations! You have just inserted data into a MySQL Workbench table.

[data types]: https://dev.mysql.com/doc/refman/8.0/en/data-types.html

## **Knowledge Check**

To show what you've learned, complete the following instructions to create a new table.

**_Note: _** _The examples on this page must be completed to follow the examples in Task 3._

1. **Create** a new table called "instructors" in the "full_stack_web_development" schema  
  &nbsp;  

* **Create** the following columns:  
  \- "instructor_id" with datatype `INT` and "PK", "NN", and "AI" checked,  
  \- "name" with datatype `TEXT` and "NN" checked.  
  &nbsp;

* **Enter** a new row of data and enter an instructor name.

## **Conclusion**

Creating tables and entering data into them is an essential skill in MySQL Workbench that every user must learn. By following the step-by-step instructions in this tutorial, you should be able to create a new table in MySQL Workbench, define its columns, and enter data into the table.
Remember to specify the appropriate data types and properties for each column and leave the "Auto Increment" columns blank if applicable.
