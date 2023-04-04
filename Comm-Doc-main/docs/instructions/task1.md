# Task 1 - Creating and Dropping Schemas

## Create a schema

1- Open MySQLWorkbench by clicking on the MySQLWorkbench icon,
<img src="/images/MYSQL-icon.png" alt= “” width="40px" height="40px"> which opens the “Home Window”.

This window displays a section titled "MySQL Connections". One connection called “Local instance: 3306” should already exist.
![image](/images/HomePage.png)

2- Click on the "Local Instance 3306" connection to connect to your local MySQL server.![image](/images/RootConnection.png)

Once you are connected you will see a screen with several tabs on top and in the toolbar on top you will see a Schema button which creates you a database.

![image](/images/Toolbar.png)

4- Click on the schema button
![image](/images/Schema-icon.png) you will now be prompted to enter a name for your new schema.

5- Enter a name for your new schema.

**Note:**
Choose a name that is descriptive and easy to remember and do not change the character set and the collation setting
![image](/images/Create_schema.png)

6-click on the "Apply" button, after you have entered your schema name and selected a collation

Once you click on the apply button you will get a pop-up message that shows you MYSQl query which is the command related to the task you are doing manually.

7- click on apply again.
![image](/images/completeSchema.png)

Congratulations! You have just created your first schema in MySQL Workbench.
You can now begin adding tables to your new schema.

## Drop a schema

1-Right click on the schema that you created, you will see a screen with several tabs.
![image](/images/drop_rightclick.png)

2-delete your schema (database) by selecting the drop schema button from the list.
![image](/images/DropSchema.png)

A pop-up notification asking for your confirmation to delete your schema should be expected.

3- Click on “Drop Now”
![image](/images/DropNow.png)

Congratulations! You have just deleted your first schema.