# Exercise 3: Managing Services

To monitor the health of your SAP HANA database in more detail, for example to troubleshoot performance bottlenecks, you can analyze the status and memory usage of individual database services. The Memory Analysis application is helpful here as it provides a more detailed breakdown of memory usage. It enables you to visualize and explore the memory allocation of every service of a selected host during a specified time range. If you notice an increase in overall memory usage, you can investigate whether it's due to a particular component, subcomponent, or table.

In this exercise, you review the information displayed in the Services card, examine the different database service management operations you have access to, and perform a basic analysis of memory usage.

1. Locate the *Services* card.  It displays metrics regarding the operational status of the SAP HANA database. Here you see the status of the database, "Running" in this case. Other possible values include "Running with issues", "Stopped", "Error" or "No SQL Access". Click the button **Manage Services**.

    ![Services Card](./images/3-01_ServicesCard.png)

2. The Manage Services app enables you to monitor the health of your SAP HANA database in more detail, for example, to troubleshoot performance bottlenecks, you can analyze the status and resource usage of individual database services. If necessary, you can perform follow-up operations, such as stopping a service, or killing a service. You can also reset memory statistics and navigate to Alerts application. Other operations available here include:

    - View detailed service information
    - View CPU usage of the service. Clicking on the mini bar chart redirects you to the Performance Monitor to see more details
    - View memory usage of the service, showing used memory (dark green), peak memory (light green), effective allocation limit (grey bar) and physical memory (light grey background)
    - Sort the table and add/remove other metrics (e.g. used memory, CPU process %, etc.) and search for specific services

    ![Manage Services App](./images/3-02_ManageServicesApp.png)

Continue to [Exercise 4: ](../ex_4)