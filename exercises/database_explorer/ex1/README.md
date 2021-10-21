In this excercise, we will launch an instance of SAP HANA Database Explorer and walk through some of its core features.

1. From the SAP BTP Cockpit, you can choose to open the SAP HANA Database Explorer by clicking the Actions dropdown on your instance, and selecting **Open in Database Explorer**.

    *image here: BTP Cockpit*

    Note: Trial instances are shut down overnight. Instances can be restarted by clicking the **Manage SAP HANA Cloud** button, and selecting **Start** on the dropdown menu for your instance.


    You may be prompted to enter database login credentials at this point. Enter the DBADMIN user credentials which were set during the SAP HANA instance creation process.


2. Hover over your database in the databases menu. A summary should appear that identifies the type as a cockpit database.

    *image here: db summary*
    
     Right-click on the database name and select **Show Overview**. The release your database belongs to can be identified by looking at the last section of the Version field. The year 

    *image here: overview page* 

    *In this example, the database is from a release in July 2021, week 30 of the year.*

3. At the top of the left pane, click the arrow next to the database icon, to expand the object hierarchy for the database. You will see that it holds catalog objects and database diagnostic files (trace files, or log files).

    Expand **Catalog** then **schemas**, this will present a list of the schemas available for this database. Directly above the list is a search bar, you can search for the **System** schema, and right-click and select **Open** to view details.

    *image here: schema menu*

4. Next, we will be creating a new SAP HANA database. To do this, Click the + button at the top of the left pane. 

    Select SAP HANA Database from the dropdown menu. The host is the first section of the API endpoint for your instance. This information can be found under **Actions** for your instance on HANA Cloud Platform Cockpit. The port number is the second section of the API endpoint, and for a trial instance this value is likely 443.

    Specify a desired User and Password. Make sure to select **Save password** and **Connect to the database securely using TSL\SSL**. Deselect **Verify the server's certificate using the trusted certificate below**.






