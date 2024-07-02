[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2021-DAT261)](https://api.reuse.software/info/github.com/SAP-samples/teched2021-DAT261)

# DAT261 - Get Hands-On Experience with Administering and Operating SAP HANA Cloud

Welcome to the Hands-On Workshop session DAT261 – Administering and Operating SAP HANA Cloud!

## Overview

In this session, we’ll introduce you to the different administration and monitoring tools for SAP HANA Cloud and show you how you can get common operational tasks done efficiently using the web-based tools SAP HANA Cloud Central, SAP HANA cockpit, and SAP HANA database explorer.

## Requirements

To complete this workshop, you need access to an SAP Business Technology Platform (SAP BTP) account. You can access SAP HANA Cloud from within SAP BTP and you can use a trial or non-trial version of SAP HANA Cloud. **This workshop assumes that you already have an SAP HANA Cloud account (trial or non-trial).** If you do not have an SAP HANA Cloud trial account, you can register for free at https://www.sap.com/cmp/td/sap-hana-cloud-trial.html.

In your SAP HANA Cloud account (trial or non-trial), perform the following steps:

1.	Enter the **"trial"** subaccount
2.	Enter the **"dev"** space
3.	Click **"SAP HANA Cloud"** from the left navigation bar
4.	Click the button **"Create Instance"** in the top right to invoke the Create Instance wizard
5.	Enter **"DEMO_HANA_DB"** for the instance name
6.	Enter and confirm your administrator password – ***PLEASE REMEMBER IT!***
7.	Click the button **"Create Instance"** at the bottom

A new SAP HANA Cloud instance will be created and this process will take approx. 25 minutes.  You may need to refresh the page to see the instance as "Running" (as opposed to "Creating").

# SAP HANA Cloud Central

The SAP HANA Cloud Central tool provides database administrators (DBAs) with a simple and centralized overview of their SAP HANA Cloud databases and SAP HANA Cloud data lake instances. You can also perform management tasks such as creating new instances, checking their status, reviewing any notifications and alerts that might have been raised, examining memory and storage consumption, and start/stop/edit/delete your instances. This section of the workshop will introduce you to the SAP HANA Cloud Central tool and how you can use it to perform different operations.

To begin, ensure you have logged in to the SAP BTP Cockpit and you have navigated to the “SAP HANA Cloud” page.

## SAP HANA Cloud Central Exercises

- [Getting Started: Launch SAP HANA Cloud Central](exercises/hana_cloud_central/ex0/)
- [Exercise 1 - Create Instances](exercises/hana_cloud_central/ex2/)
- [Exercise 2 - Apply Filters](exercises/hana_cloud_central/ex1/)
- [Exercise 3 - Edit Instances](exercises/hana_cloud_central/ex_3/)
- [Exercise 4 - Grouping, Sorting, and Other Settings](exercises/hana_cloud_central/ex_4/)
- [Exercise 5 - Start, Stop, Upgrade Instances, and Other Actions](exercises/hana_cloud_central/ex_5/)
- [Exercise 6 - Delete Instances](exercises/hana_cloud_central/ex_6/)
- [Exercise 7 - Giving Feedback](exercises/hana_cloud_central/ex_7/)

# SAP HANA Cockpit

The SAP HANA cockpit tool provides administration and monitoring of individual SAP HANA Cloud database instances. With the SAP HANA cockpit, you can monitor resource utilization (memory, CPU and disk), alerts, table usage, SAP HANA services, SAP HANA native storage extensions (NSE), and database performance metrics (threads, sessions, SQL statements, workload classes and connections). You can also administer backups, configuration parameters, table distribution, smart data access (SDA) and smart data integration (SDI). Finally, you can perform security tasks such as user & role management, data encryption, auditing, data anonymization and trust configuration. This workshop guides you through the basic operations to manage SAP HANA Cloud databases.

## Requirements

Completed the SAP HANA Cloud Central [Exercise 1 - Create Instances](exercises/hana_cloud_central/ex2/) or have access to a SAP HANA Cloud instance.

## SAP HANA Cockpit Exercises


- [Exercise 1 - The Database Overview Page](exercises/hana_cockpit/ex_1/)
- [Exercise 2 - Configuring Database Properties](exercises/hana_cockpit/ex_2/)
- [Exercise 3 - Managing Services](exercises/hana_cockpit/ex_3/)
- [Exercise 4 - Managing Alerts](exercises/hana_cockpit/ex_4/)
- [Exercise 5 - Monitoring Memory Usage](exercises/hana_cockpit/ex_5/)
- [Exercise 6 - Security Basics](exercises/hana_cockpit/ex_6/)
- [Exercise 7 - Performance Management](exercises/hana_cockpit/ex_7/)
- [Exercise 8 - Database Backup](exercises/hana_cockpit/ex_8/)
- [Exercise 9 - Recent Activities and Frequently Used Apps](exercises/hana_cockpit/ex_9/)
- [Exercise 10 - Managing Workload Classes](exercises/hana_cockpit/ex_10/)



# SAP HANA Database Explorer

The SAP HANA database explorer is a web-based tool for browsing and working with SAP HANA database objects such as tables, views, functions, stored procedures, executing SQL statements, importing and exporting data, debugging SQLScript, working with multi-model data such as graph, spatial and JSON collections,  viewing trace files, and creating remote sources.  As of March 2021, it also offers support for Data Lake IQ connections.


## Requirements

Completed the SAP HANA Cloud Central [Exercise 1 - Create Instances](exercises/hana_cloud_central/ex2/) or have access to a SAP HANA Cloud instance.


## SAP HANA Database Explorer Exercises


- [Exercise 1 - Launch and Connect with the SAP HANA Database Explorer](exercises/database_explorer/ex1/)
- [Exercise 2 - Using the SQL Console](exercises/database_explorer/ex2/)
- [Exercise 3 - Catalog Browser and Object Search](exercises/database_explorer/ex3/)
- [Exercise 4 - Working with the Statement Library](exercises/database_explorer/ex4/)
- [Exercise 5 - Further Steps with the SAP HANA Database Explorer](exercises/database_explorer/ex5/)
 

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2024 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
