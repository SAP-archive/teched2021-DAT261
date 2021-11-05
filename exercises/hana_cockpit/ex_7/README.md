# Exercise 7: Performance Management

Managing and monitoring past and current information about the performance of the SAP HANA database is important for root-cause analysis and the prevention of future performance issues. We already learned about the Performance Monitor and Memory Analysis applications to visualize and analyze current and historical performance data.

In this exercise, you'll explore the additional performance management tools available in the SAP HANA cockpit

1. Locate the *Threads* card. This card shows the number of active and blocked threads in the database. Clicking on it takes you to the *Threads* app, which is used to monitor the longest-running threads active in your system. It may be useful to see, for example, how long a thread is running, or if a thread is blocked for an inexplicable length of time.

    ![Threads Card](./images/7-01_ThreadsCard.png)

2. Click on the **Threads** card to launch the *Threads* application. When you launch this app, you'll see detailed information for approximately the 1,000 longest-running threads currently active in the database.

    For each statement, you can see the duration, as well as the name of the service that is executing the thread. You can identify the host, the port, and the thread type, whether the statement is related to a blocking transaction, and much more. Clicking on a thread offers you the option to navigate to the sessions or blocked transactions associated with that connection ID. If a thread is involved in a blocked transaction or using an excessive amount of memory, you can cancel the operation executing the thread. You can view the call stack for this thread, although that is typically only useful to SAP Support when analyzing incidents. The threads can be grouped or sorted using the Group and Sort icon. You can view much more details on the threads by adding columns to the table via the Settings button.

    ![Threads Application](./images/7-02_ThreadsApp.png)

3. Click the **Summary arrow** above the table. In addition to the thread details, you can see a summary of the top 5 application and database users, and information about the total number of threads by status and type.

    ![Threads Summary](./images/7-03_ThreadsApp-Summary.png)

4. Click the **Back** button at the top left to return to the Database Overview page.

5. Locate the **Sessions** card. This card shows the currently running and total number of sessions in the database. Analyzing the sessions connected to your SAP HANA database can help you identify which applications or which users are currently connected to your system, as well as what they are doing in terms of SQL execution.

    ![Sessions Card](./images/7-05_ThreadsCard.png)

Continue to [Exercise 8: ](../ex_8)