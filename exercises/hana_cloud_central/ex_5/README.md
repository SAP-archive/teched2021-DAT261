# Exercise 5 - Start, Stop, Upgrade Instances, and Other Actions

In this section we will discuss about how to start, stop, and upgrade instances from the SAP HANA Cloud Central application.


1. Click on "..." button.
    <kbd>
    ![](./images/1.png)
    </kbd>
    
2. Click on Stop. A pop up shows up, confirming if you want to continue with stopping the instance. Note: Please do not stop the instance now so that we can proceed with other actions that could be performed. Click on 'Cancel'.
    <kbd>
    ![](./images/2.png)
    </kbd>
      
3. If you confirm to stop the instance, you see the status getting changed to 'Stopping' and you can see more details by clicking on the hyperlink.
    <kbd>
    ![](./images/3.png)
    </kbd>
    <kbd>
    ![](./images/4.png)
    </kbd>
    
4. Now let us start an instance that has been already stopped. Click on More(...) button under the Actions column.
    <kbd>
    ![](./images/5.png)
    </kbd>
      
5. Click on Start. We can see that the instance has moved to status 'Starting'. On clicking the 'Starting' hyperlink we see details on the date and time when the instance was initiated and updated.
    <kbd>
    ![](./images/9.png)
    </kbd>
    <kbd>
    ![](./images/10.png)
    </kbd>
    <kbd>
    ![](./images/11.png)
    </kbd>

6. We also have another option that allows us to Upgrade the SAP HANA instance. We can find this option under the Actions list. Click on Upgrade button under Actions column if there is any upgrade available.
    <kbd>
    ![](./images/28.png)
    </kbd>
    
    You can also click on the notification icon to check for any upgrades.
    <kbd>
    ![](./images/30.png)
    </kbd>
      
7. A pop up appears saying that a new revision for the instance is available and if we want to continue with the Update process. If you would like an update now, click on Update button else click on Cancel to quit from the pop up. Click on Cancel for now.
    <kbd>
    ![](./images/31.png)
    </kbd>
      
8. Let us now have a look at an SAP HANA instance that already has a Data lake instance associated with it. When you see the Actions list for such an SAP HANA instance, you can notice that Add Data lake option is not available. 
    <kbd>
    ![](./images/29.png)
    </kbd>
      
    When there is no data lake associated, you can see Add Data Lake option in the Action list.
    <kbd>
    ![](./images/8.png)
    </kbd>
      
9. Now let us talk about the other Actions available for each of the instance. Click on More (...) button under the Actions column for an SAP HANA instance. Click on Open in SAP HANA Cockpit option in the Actions list. We can directly open the SAP HANA Cockpit to administer the SAP HANA instance from the SAP HANA Cloud Central page.
    <kbd>
    ![](./images/32.png)
    </kbd>
      
10. SAP HANA Cockpit is opened in an adjacent new tab. Here enter the valid Username and Password for the instance. Click on Ok. Once the credentials are validated, we are at the SAP HANA Cockpit, Database Overview page, where we can perform various monitoring and administrating operations on our HANA instances.
    <kbd>
    ![](./images/13_a.png)
    </kbd>
    <kbd>
    ![](./images/13_b.png)
    </kbd>
      
11. We can also open the SAP HANA Database Explorer to create SQL scripts, run them and also administer the SAP HANA instance directly from the Cloud Central page. Click on Open in SAP HANA Database Explorer option in the Actions list for an SAP HANA instance. SAP HANA Database Explorer is opened in an adjacent new tab.
    <kbd>
    ![](./images/33.png)
    </kbd>
    <kbd>
    ![](./images/14_b.png)
    </kbd>
    
12. Get back to the Cloud Central Overview page and choose the Actions list for an SAP HANA instance again. Now click on Open SQL Console option. SAP HANA Database Explorer opens up in a new tab, but this time with an SQL Console already opened.
    <kbd>
    ![](./images/34.png)
    </kbd>
    <kbd>
    ![](./images/15_b.png)
    </kbd>

13. Let us now explore the actions for a Data lake instance. Click on More(...) button under the Actions column corresponding to a Data Lake instance. First is the Manage File Container. Click on it. You can edit the configuarations and click on save. You can find more information related to this option in [here](https://blogs.sap.com/2021/08/05/setting-up-initial-access-to-hana-cloud-data-lake-files/).
    <kbd>
    ![](./images/16.png)
    </kbd>
    <kbd>
    ![](./images/17.png)
    </kbd>
    <kbd>
    ![](./images/18.png)
    </kbd>

14. Copy SQL Endpoint functionality - On clicking this, the SQL endpoint is copied to the clipboard. Click on Copy SQL Endpoint.
    <kbd>
    ![](./images/19.png)
    </kbd>

15. We get a success message saying that the SQL endpoint is copied to the clipboard.
    <kbd>
    ![](./images/20.png)
    </kbd>

16. Next is the Copy Instance ID option - This will help us copy the instance id to the clipboard. This function is similar to the previous copy option we discussed. On clicking Copy Instance ID option, we get a success message.
    <kbd>
    ![](./images/21.png)
    </kbd>
    <kbd>
    ![](./images/22.png)
    </kbd>

17. Click on Copy Configuration. A popup open with options to copy configuration to clipboard or download it as a JSON file. Depending on how often you will use your instance configuration, either copy or save the JSON-compliant string.
    <kbd>
    ![](./images/23.png)
    </kbd>
    <kbd>
    ![](./images/24.png)
    </kbd>

18. Copy Files Rest API Endpoint- copies it to the clipboard.
    <kbd>
    ![](./images/25.png)
    </kbd>
    <kbd>
    ![](./images/26.png)
    </kbd>
      
19. Other Copy options help in directly copying the Landscape Id, Port ID, Coordinator Endpoint and Worker. You can find these options in the Actions list for a Data Lake instance. All the IDs are directly copied to the clipboard.
    <kbd>
    ![](./images/27.png)
    </kbd>

Continue to - [Exercise 6 - Delete Instances ](../ex_6/README.md)
