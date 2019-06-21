#Create New Budget Manager in BI 360

##Purpose

As new staff joins CSBA or Staff is assigned new responsibilities we are asked to add Staff members as new Budget Mangers in BI 360 so that they can Manage the budget for a given department or sub department.

 

##Scope

Add an existing Staff member as a Budget Manager in BI 360 for a given department or sub department.

 

##Prerequisites

- Staff Members must have an Active directory Account

- Need to know the departments or sub departments which the Staff member can access

- Acquire an authorization from the Staff member's manager to be added as Budget Manager

 

##Procedure

Adding a staff Member as a Budget Manager requires adding the Staff Member in 3 separate applications, BI 360 Administration Application, BI 360 Data Warehouse and SQL Server.  In addition to adding the User in these applications appropriate Roles and Permissions must be assigned the user.

 

###Add the User in BI 360 Administration Application

1. Follow the instructions on the Create new User in BI 360 Administration Application page to create the new User in BI360 Administration Application

 

####Assign Role(s) to the User

1. Follow the instruction on the Assign Role(s) in BI360 Administration Application page to assign appropriate Role(s) to the User in BI360 Administration Application.  These Role(s) will determine which department or sub department's budget this user can manage.

 

####Assign "Player" license to the User

1. Follow the instruction on the Assign License in BI360 Administration Application page to assign "Player" license to the User in BI360 Administration Application

 

###Add the User in Data Warehouse Application

1. Follow the instruction on the Create new User in Data Warehouse page to Create new User in Data Warehouse Application
2. Select the new user from the list
3. Assign user the "Planning" license by checking the planning box

 

###Add the User with Roles in SQL Server

1. Follow the instruction on the Add a Database User in SQL Server to create the SQL Server User in BI360DW database

2. Follow the instruction on the Assign Roles to a Database Users to assign the "BI360_Users" role in BI360DW database to the new user

3. Follow the instruction on the Add a Database User in SQL Server to Create the SQL Server User in "OSR_Repository" database

4. Follow the instruction on the Assign Roles to a Database Users to assign the "db_datawriter" & "db_datareader" roles in "OSR_Repository" database to the new user
