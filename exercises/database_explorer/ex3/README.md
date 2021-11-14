# Exercise 3 - Catalog Browser and Object Search

In this exercise, we will explore some of the functionality that the catalog browser and object search provide when working with database objects.  

>For this exercise and the remaining exercises please use the DBADMIN user.  
>
> ![](images/ConnectedToDBADMIN.png)

1. Database objects such as a table can be located in the catalog browser by navigating to **Tables** and specifying a schema such as **HOTEL**.

    ![](images/TablesInCatalogBrowser.png)

    Alternatively, a table can be found by selecting **Tables** and choosing **Show Tables** from the context menu.
    
    ![](images/TablesInCatalogBrowser2.png)

    Additional filters can be applied in this view by clicking on the column header.  A schema filter with a value of HOTEL was applied in the screenshot above.

2. The properties of a selected object such as the RESERVATION table can be viewed by choosing **Open** from a selected table's context menu.

    ![](images/OpenTable.png)

    The table information is displayed.

    ![](images/TableColumns.png)

    The runtime information of a table such as the number of records, or the memory consumption can also be viewed.

    ![](images/RuntimeInformation.png)

3.  The SQL used to create, select, or insert into a table can be generated via the table's context menu. 

    ![](images/GenerateCreate.png)

4. The dependencies of an object can be shown.  As an example, the ROOM table is shown below as it has a foreign key reference to the HOTEL table. 

    ![](images/FindDepencies.png)

5. Database objects can also be found using the object search.  The below search looks for any functions or procedures in the schema HOTEL in the database DEMO_HANA_DB (DBADMIN). 

    ![](images/ObjectSearch.png)

    An object search can be performed across a selected database or across all databases.

    ![](images/SearchAcrossAllDatabases.png)

6. An object such as the stored procedure RESERVATION_GENERATOR can be opened by clicking on it.  

    ![](images/ClickOnStoredProcedure.png)

    Once opened, notice that there is an option to call the stored procedure.

    ![](images/CallStoredProcedure1.png)

    This stored procedure takes an input parameter and when executed will generate 100 new reservations.
 
    ![](images/CallStoredProcedure2.png)

7. Additional functionality is available from the context menu of a stored procedure such as **Analyze SQLScript Code** which can provide suggestions for code quality, security, or performance and **Open for Debugging** which enables stored procedures, functions, or anonymous blocks to be debugged. 

    ![](images/AnalyzeSQLScriptCode.png)

    For additional details on SQLScript analysis and debugging, see [Troubleshoot SQL with SAP HANA Database Explorer](https://developers.sap.com/tutorials/hana-dbx-troubleshooting.html).

This concludes the exercises on the catalog browser and object search.

Continue to - [Exercise 4 - Working with the Statement Library ](../ex4/README.md)