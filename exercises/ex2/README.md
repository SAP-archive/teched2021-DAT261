# Exercise 2 - Creating Instances

We can create SAP HANA, Data Lake, Adaptive Server Enterprise, and Adaptive Server Enterprise Replication instances on the SAP HANA Cloud Central Overview page.
Note - You can see the options to create Data Lake, ASE, and ASE Replication instances only if you have subscribed to use them.

1. Click here on the Create button dropdown to see the list of type of instances that you can create. First let us create an SAP HANA Instance. Click on SAP HANA Database option. Here is the pop up you will see if you go ahead with the option of creating SAP HANA Cloud instance. On this pop up, we see info icons corresponding to certain fields, on clicking them we get more details and insights on the respective fields. Let us have a look at info icon next to the field Instance Name.

<br>![](/exercises/ex2/images/02_01_0010.png)

2. Click on info icon, and we see a pop up with details related to the field.   
Below are the details on the fields that you see on this Create Instance pop up, what are the values they take and the details on steps to successfully create an SAP HANA Cloud instance.
Organization - The Cloud Foundry organization in which the instance is created
Space - The Cloud Foundry space in which the instance is created
Instance Name - The name of the instance. The name must start and end with an alphanumeric character. The name can include the underscore character _.
Description - A description of the instance.
Administrator Password - The password of the database 'superuser' DBADMIN. The password must have at least 8 characters and comprise at least one uppercase letter, two lowercase letters, and at least one number. The password must not include the user name, the characters ' " ` \ ; [ ], or control characters, such as newline, backspace, tab.
 

3. Click on Next Step once all the fields are rightly filled. The pop up for Step 2 in creating an instance has hyperlinks that leads us to Help documentations that give us in depth details on the memory size of the databases. Clicking on these hyperlinks opens a new tab with Help documentation details.

4. Click on SAP HANA Database Documentation hyperlink. Here is the look of new tab that has details on the database instance sizes.
Further details on the fields present on step 2 are as below:
Memory - The size of your (compressed) in-memory data in your SAP HANA database
Compute - The number of vCPUs of your SAP HANA database
The number of vCPUs is allocated according to the size of memory of your instance.
Storage - The disk storage space of your SAP HANA database.
The disk storage space is allocated according to the memory size of your SAP HANA database.

5. Click on Next Step button, once the memory and storage configurations are done. In Step 3, you have the option to make configurations related to Allowed connections like IP address settings. Then there is an Additional Features sections to make configurations on Script Server and Document Store capabilities.

6. Click on Next Step to proceed to Data Lake related settings. In this step, you have the option to create a data lake instance along with creating an SAP HANA Cloud instance. To do so, you must just enable the Create Data Lake toggle button and fill in related details to it. 

7. Click on Create Data Lake toggle button to create a Data Lake instance as well. In Step 4, enter the Data Lake instance name, make configurations to the required Storage services. Click on Next Step.

8. Adjust the size if necessary and click on Next Step. This section will have enabled fields only if we choose to create a Data Lake IQ instance in the previous step. Here you have the liberty to make configurations on the IP address settings as per your requirements.

9. Click on Create Instance button, and you will be redirected to the SAP Cloud Central overview page to see the instance you have just initiated to create.

10. On the Cloud Central overview page, after the SAP HANA instance is created, we see a status CREATING next to the instance we just created. On clicking on this status (hyperlink) we get details on when the instance creation was initiated.






Continue to - [Exercise 3 - Excercise 3 ](../ex_3/README.md)
