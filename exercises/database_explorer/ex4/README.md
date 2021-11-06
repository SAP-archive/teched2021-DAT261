# Exercise 4 - Working with the Statement Library

In this exercise, we will explore the statement library and demonstrate how to import and run statements from the SQL Statement Collection for SAP HANA. 

1. The statement library can be accessed by the context menu on the database.

    ![](images/OpenStatementLibrary.png)

    The contents of the statement library are associated with the user used to log into the SAP BTP Cockpit and not a specfic database.

2. Statements can be either system or user statements.  System statements are not editable and are from the monitoring view M_SYSTEM_INFORMATION_STATEMENTS.

    ![](images/SystemStatements.png)

    The following is an example result of running the **Connection Attempts and Status** system statement after a successful and then two failed connect attempts.

    ![](images/SystemStatementsConnections.png)

    ```sql
    CONNECT USER1 PASSWORD Password1;
    CONNECT USER1 PASSWORD WrongPwd;
    CONNECT USER1 PASSWORD WrongPwd2;

    (SELECT 'CURRENT_STATUS' AS STATUS, USER_NAME, LAST_SUCCESSFUL_CONNECT, LAST_INVALID_CONNECT_ATTEMPT, INVALID_CONNECT_ATTEMPTS FROM SYS.USERS WHERE USER_NAME NOT LIKE '_SYS%' AND USER_NAME != 'SYS' UNION (SELECT 'HISTORIC_CONNECT_ATTEMPTS' AS STATUS, USER_NAME, SUCCESSFUL_CONNECT_TIME AS LAST_SUCCESSFUL_CONNECT, NULL, INVALID_CONNECT_ATTEMPTS FROM SYS.INVALID_CONNECT_ATTEMPTS WHERE USER_NAME NOT LIKE '_SYS%' AND USER_NAME != 'SYS')) ORDER BY USER_NAME, STATUS;
    ```

    >The SQL calls the system view [INVALID_CONNECDT_ATTEMPTS](https://help.sap.com/viewer/c1d3f60099654ecfb3fe36ac93c121bb/latest/en-US/ea60f23498704b6ea225f44595151f61.html) which provides the number of invalid connection attempts between two successful connections.

3. User statements can be added from the SQL console.  

    Paste the below contents into a SQL Console, rename the tab to Future Check-ins, and press the **Add to Statement Library** toolbar.

    ```sql
    /* 

    [DESCRIPTION]

    - All check-ins today or in the future

    */

    SELECT * FROM HOTEL.RESERVATION
        WHERE ARRIVAL >= CURRENT_DATE ORDER BY ARRIVAL ASC;
    ```

    ![](images/AddUserStatement.png)

    >Note that the SQL console tab name is used for the name in the statement library.

    Notice that a new user statement has been added to the statement library.

    ![](images/UserStatementAdded.png)

4. A commonly used set of diagnostic SQL statements can be downloaded from [SAP Note 1969700 - SQL Statement Collection for SAP HANA](https://launchpad.support.sap.com/#/notes/1969700).

    ![](images/SQLStatementCollectionNote.png)

    Once unzipped, it can be seen that there are statements for different versions of SAP HANA. 

    The following steps import statements that apply specifically to SAP HANA Cloud.

    * Create a zip of statements that contain **SHC**.
        
        ![](images/CreateZip.png)

    * Import the zip file.

        ![](images/Import.png)

        ![](images/ImportSHCStatements.png)

    * Execute a statement such as the **HANA_Configuration_MiniChecks_SHC**.
    
        ![](images/HANAConfigurationMiniChecks.png)

        Notice below that the results show the value for a check, what the expected range of values is for each check, an X if the value is outside the expected range, and an SAP Note to reference for further information. 

        ![](images/HANAConfigurationMiniChecksResult.png)

This concludes the exercises on the statement library.
    
Continue to - [Exercise 5 - Further Steps with the SAP HANA Database Explorer](../ex5/README.md)