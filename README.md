# SAP HANA Cloud Central

## Description

In this guide, we will introduce you to the newest of our database management tools for SAP HANA Cloud: SAP HANA Cloud Central and show you how you can manage your instances and perform various administrative actions.  

## Overview

The aim of the SAP HANA Cloud Central tool is to provide database administrators (DBAs) with a simple and centralized overview of their SAP HANA Cloud database and data lake instances. You can also perform management tasks such as creating new instances, checking their status, reviewing any notifications and alerts that might have been raised, examining memory and storage consumption, and start/stop/edit/delete your instances.
This guide will introduce you to the SAP HANA Cloud Central tool and how you can use it perform the above-mentioned operations.
To begin, ensure you have logged in to the SAP BTP Cockpit and you have navigated to the “SAP HANA Cloud” page (see steps 1-3 in previous section).


## Requirements

To complete this guide, you need access to an SAP Business Technology Platform (SAP BTP) account, formerly known as SAP Cloud Platform. You access SAP HANA Cloud from within SAP BTP and you can use a trial or non-trial version of SAP HANA Cloud.
This guide assumes that you already have an SAP HANA Cloud account (trial or non-trial).  If that's the case, proceed to the next chapter.
If you do not have an SAP HANA Cloud trial account, you can register for free at https://www.sap.com/cmp/td/sap-hana-cloud-trial.html. Once you have successfully registered and your account is set up, perform the following steps:
1.	Enter the "trial" subaccount
2.	Enter the "dev" space
3.	Click "SAP HANA Cloud" from the left navigation bar
4.	Click the button "Create Instance" in the top right to invoke the Create Instance wizard
5.	Note - If you are a non-trial customer who has subscribed for ASE or Data Lake, then you have the liberty to choose from the dropdown to create an ASE, ASE Replication or Data Lake instances
6.	Enter "XYZ" for the instance name
7.	Enter and confirm your administrator password – please remember it!
8.	Click the button "Create Instance" at the bottom
A new SAP HANA Cloud instance will be created, and this process will take approx. 25 minutes.  You may need to refresh the page to see the instance as "Running" (as opposed to "Creating").  Once that's done, proceed to the next chapter.



## Exercises

Provide the exercise content here directly in README.md using [markdown](https://guides.github.com/features/mastering-markdown/) and linking to the specific exercise pages, below is an example.

- [Launch SAP HANA Cloud Central](exercises/ex0/)
- [Apply Filters](exercises/ex1/)
- [Create Instances](exercises/ex2/)
- [Edit Instances](exercises/ex3/)
- [Configure Storage](exercises/ex4/)
- [Start, Stop, and Upgrade Instances](exercises/ex5/)
- [Delete Instances](exercises/ex6/)

 

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2021 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
