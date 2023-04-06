# Task 2 - Creating Tables and Data Entry

## **Introduction**

In this guide, we will show you step-by-step how to create a new table in MySQL Workbench and add data to it. You will learn how to define the columns for your table, specify data types and properties, and enter data into the table.

## **Create a Tables**

1. **Find and Double click** on the schema that you want to create a table in through the schema list.  
    ![image](/images/SelectSchema.png)  
   Once you have completed the initial step accurately and selected the schema, clicking on it will bring up a screen with multiple tabs.  
   ![image](/images/TableTab.png)

- **Right click** on the "Tables" tab and click on the create table button.  
   ![image](/images/SelectCreateTable.png)  
  You should see the “Edit Table Screen” and be prompted to enter a name for your new table.  
   ![image](/images/SelectTableName.png)

- **Define** the columns for your new table
  table.  
   ![image](/images/TableColumn.png)

- **Click** on the <click to edit\> button to add a new column. For each column, you will need to enter a name, data type, and any additional properties that you want to assign to that column.  
  ![image](/images/Constraint.png)
  **_Note -_** you might want to specify that a column is a primary key, unique, null or not null.For reference on data types, visit the [MySQL Reference Manual section on data types][data types].

- **Click** on the "Apply" button once you have defined all of your columns to create your new table.

Congratulations! You have just created a table in MySQL Workbench, you can now begin adding data to your new table.

## **Data Entry**

1. **Click** on the schema that you created a table.

- **Click** on the schema table to open the list  
  ![image](/images/TableTab.png)

- Hover your mouse over the table that you want to insert data, you will see a row selection button <img src="/images/RowSelectionbtn.png" alt= “” width="30px" height="30px">

- **Click** on the row selection button.Then you will see a "Data" tab, where you have all the columns that you created earlier in your table.  
  ![image](/images/DataTab.png)

- **Double click** on "NULL” underneath a column name.“NULL” should disappear and the area should be highlighted with a blue border.  
  ![image](/images/CourseCode.png)

- **Type** your data.  
  ![image](/images/TypeDataIn.png)

- Continue entering data for each column until you have entered all the data you want to insert into the table.  
  ![image](/images/completedcolumn.png)

> **Note:**
> If any columns are set to "Auto Increment" (AI), leave them blank.

- **Click** on the "Apply" button to insert the data into the table, Once you have entered all the data  
  ![image](/images/InsertedData.png)

Congratulations! You have just inserted data into a MySQL Workbench table.

[data types]: https://dev.mysql.com/doc/refman/8.0/en/data-types.html

## **Conclusion**

creating tables and entering data into them is an essential skill in MySQL Workbench that every user must learn. By following the step-by-step instructions in this tutorial, you should be able to create a new table in MySQL Workbench, define its columns, and enter data into the table.
Remember to specify the appropriate data types and properties for each column and leave the "Auto Increment" columns blank if applicable.
