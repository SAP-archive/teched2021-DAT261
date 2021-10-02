# Exercise 5 - Start, Stop, Upgrade an instance and other actions

In this section we will discuss about how to Start and Stop the databases from the SAP HANA Cloud Central Overview page. On clicking the More(...) button under the Actions column for any type of instance, we see a Stop option to stop the particular instance


1. Click on "..." button.

<br>![](/exercises/ex2/images/02_01_0010.png)

2. Click on Stop. A pop up shows up, confirming if you want to continue with stopping the instance. If yes, click on Stop button.

3. On the Overview page, you can see that the status for instance you just stopped has changed to 'Stopping'. Click on the hyperlink status to see more details on the status.

4. Now let us Start an instance that has been already Stopped. Click on More(...) button under the Actions column

5. Click on Start. We can see that the instance has moved to status Starting. And on clicking the Starting hyperlink we see details on the date and time when the instance was initiated and updated.

6. We also have another option that allows us to Upgrade the SAP HANA instance. We can find this option under the Actions list.

7. Click on More(...) button under Actions column.

8. A pop up appears saying that a new revision for the instance is available and if we want to continue with the Update process. If you would like an update now, click on Update button else click on Cancel to quit from the pop up. Click on Cancel for now.

9. Let us now have a look at an SAP HANA instance that already has a Data lake instance associated with it. When you see the Actions list for such an SAP HANA instance, you can notice that Add Data lake option is Disabled. Also, the Upgrade option too is Disabled for an instance that is Stopped.

10. Click on More(...) button under the Actions column. In the Action list we can notice that Add Data Lake and Upgrade options are disabled. This is solely because the instance is Stopped and already has a Data lake instance associated with it.

11. Now let us talk about the other Actions available for each of the instance. Click on More (...) button under the Actions column for an SAP HANA instance.

12. Click on Open in SAP HANA Cockpit option in the Actions list. We can directly open the SAP HANA Cockpit to administer the SAP HANA instance from the SAP HANA Cloud Central page.

13. SAP HANA Cockpit is opened in an adjacent new tab. Here enter the valid Username and Password for the instance. Click on Ok. Once the credentials are validated, we are at the SAP HANA Cockpit Database Overview page, where in we can perform various monitoring and administrating operations on our HANA instance.

14. We can also open the SAP HANA Database Explorer to create SQL scripts, run them and also administer the SAP HANA instance directly from the Cloud Central page. Click on Open in SAP HANA Database Explorer option in the Actions list for an SAP HANA instance. SAP HANA Database Explorer is opened in an adjacent new tab. 

15. Get back to the Cloud Central Overview page and choose the Actions list for an SAP HANA instance again. Now click on Open SQL Console option. SAP HANA Database Explorer opens up in a new tab, but this time with an SQL Console already opened.

16. Let us now explore the actions for a Data lake instance. Click on More(...) button under the Actions column corresponding to a Data Lake instance. 

17. First is the Copy SQL Endpoint functionality - On clicking this, the SQL endpoint is copied to the clipboard. Click on Copy SQL Endpoint.

18.










Continue to - [Exercise 4 - Excercise 4 ](../ex_4/README.md)
