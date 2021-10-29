# Exercise 4 - Statement Library

In this exercise, we will explore the statement library and demonstrate how to import and run statements from the SQL Statement Collection for SAP HANA. 

1. The statement library can be accessed by the context menu on the database.

    ![](images/OpenStatementLibrary.png)

    The statement library is associated with the user used to log into the SAP BTP Cockpit.

2. Statements can be either system or user statements.  System statements are not editable and are from the monitoring view M_SYSTEM_INFORMATION_STATEMENTS.

    ![](images/SystemStatements.png)

    The following is an example result of running the **Connection Attempts and Status** system statement after a successful and then failed connect attempt.

    ![](images/SystemStatementsConnections.png)

    ```sql
    CONNECT USER1 PASSWORD Password1;
    CONNECT USER1 PASSWORD WrongPwd;
    ```

3. User statements can be added from the SQL Console.

    ![](images/AddUserStatement.png)

    ```sql
    SELECT * FROM HOTEL.RESERVATION
        WHERE ARRIVAL >= CURRENT_DATE ORDER BY ARRIVAL ASC;
    ```

    >Note that the SQL Console tab name is used for the name in the statement library.

    ![](images/UserStatementAdded.png)

    Alternatively, they can be imported from a file or from a zip file.

4. A commonly used set of diagnostic SQL statements can be downloaded from [SAP Note 1969700 - SQL Statement Collection for SAP HANA](https://launchpad.support.sap.com/#/notes/1969700).

    ![](images/SQLStatementCollectionNote.png)

    Once unzipped, it can be seen that there are statements for different versions of SAP HANA. 

    The following steps import statements that apply to SAP HANA Cloud.

    * Create a zip of statements that contain **SHC**.
        
        ![](images/CreateZip.png)

    * Import the zip file.

        ![](images/Import.png)

        ![](images/ImportSHCStatements.png)

    * Execute a statement such as the **HANA_Configuration_MiniChecks_SHC**.
    
        ![](images/HANAConfigurationMiniChecks.png)

        ![](images/HANAConfigurationMiniChecksResult.png)

This concludes the exercises on the statement library.
    
Continue to - [Exercise 5 - Further Steps with the SAP HANA Database Explorer](../ex5/README.md)