# **Task 3 - Establishing Relatinships Between Tables**

## **Introduction**

Welcome to this tutorial on establishing relationships between tables in MySQL Workbench. Tables in a database can be linked together by primary and foreign keys. In this guide, we will show you step-by-step how to create a foreign key (FK) in MySQL Workbench. You will need at least two tables in your database that reference each other to use these instructions.

Establishing relationship between tables requires the database contains at least two tables, and the tables contain related data. Our example models the relationship between a course and an instructor.

**_Note:_** _The examples we created below reference the examples from Task 1 and Task 2. If you want to follow along with the examples for this Task, create the examples from the previous tasks first_.

## **Creating Foreign Key**

The following instructions show how to create a foreign key (FK) in MySQLWorkbench.

**_Note:_** _For reference on primary and foreign keys, visit the [MySQL Reference Manual glossary][pk/fk]_.

1. **Double click** on the name of the schema that contains the table you want to edit from the menu on the left.  
   ![image](/images/TableTab.png)  
   The schema name should be bolded and a menu should open up beneath the name.  
  &nbsp;  

- **Click** on the arrow beside “Tables” to view the list of tables in the database.
  ![image](/images/TableTabOpen.png)  
  &nbsp;  

- **Hover** the mouse over the name of the table where the foreign key will be added.  
  ![image](/images/Term1Table.png)  
  Three icons should appear to the right of the table name.  
  &nbsp;  

- **Click** the wrench icon. The "Edit Table Screen" should come into view.  
  &nbsp;  

- **Click** the "Foreign Keys" tab in the menu near the bottom of the "Edit Table Screen".  
  ![image](/images/ForeignKeyTab.png)  
  The "Foreign Key Screen" should come into view.  
  &nbsp;  

- **Double click** < click to edit > underneath the "Foreign Key" heading on the left of the "Foreign Key Screen".
  ![image](/images/ClickToEdit.png)  
  &nbsp;  

- **Type** a name for your FK and press ENTER.  
  ![image](/images/NameFK.png) 
  We named our FK "term_1_courses_instructor_id".  
  &nbsp;  

- **Click** next to the FK name under the “Referenced Table” heading.  
  ![image](/images/RefTable.png)  
  A list of tables in your schema should appear.  
    &nbsp;  

- **Select** the table that the FK is referencing.
  ![image](/images/RefTableSelected.png)  
  In this example, we selected "instructors" as the referenced table.  
  &nbsp;  
   After making the FK, the table's columns' names should appear under "Foreign key details".  
  ![image](/images/ColumnNames.png)  
  &nbsp;  

- **Check** the box for your FK column beneath the "Column" heading under "Foreign key details".  
  ![image](/images/ColumnSelected.png)  
  Then, the referenced column should default to the primary key of the referenced table.  
  &nbsp;  

- **Select** the column the FK is referencing by clicking under the "Referenced Column" heading (if it is not already selected).  
  ![image](/images/SelectRefColumn.png)  
  &nbsp;  

- **Click** "Apply" at the bottom of the "Foreign Key Screen".  
  ![image](/images/ApplyFK.png)  
  A pop-up window should appear displaying the MySQL query for creating the FK.  
  &nbsp;  

- **Click** “Apply”, then "Close".  
  &nbsp;  

## **Conclusion**

Establishing relationships between tables is an important aspect of database management. In MySQL Workbench, this can be done by creating foreign keys between tables. By creating foreign keys, tables can reference each other and maintain data integrity. In this task, we learned how to create foreign keys in MySQL Workbench. We went through step-by-step instructions on how to create a foreign key, including selecting the tables and columns involved, and applying the changes.

[pk/fk]: https://dev.mysql.com/doc/refman/8.0/en/glossary.html