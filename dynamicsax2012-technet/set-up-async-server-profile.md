---
title: Set up Async Server profile
TOCTitle: Set up Async Server profile
ms:assetid: 00faba1a-26cf-4bb6-b28d-b6361b30aa9b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn859554(v=AX.60)
ms:contentKeyID: 63820130
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Set up Async Server profile 


A profile for Async Server specifies how frequently Async Client checks for data packages to download and creates data packages to upload. You must configure data download and upload intervals for each instance of Async Client in the environment.

Async Client is part of Commerce Data Exchange, the asynchronous system that shares data between the Retail essentials database and retail channel databases. Async Client is installed for each channel, and communicates with the channel database. Commerce Data Exchange also includes Async Server, which is installed at headquarters and communicates with the Retail essentials database in each store. For more information about Commerce Data Exchange, see the [Commerce Data Exchange documentation](http://go.microsoft.com/fwlink/?linkid=391057) on TechNet.

1.  Click **Retail essentials** \> **Data synchronization** \> **Setup** \> **Store integration** \> **Async Server profile**.

2.  Click **New** to create a new profile.

3.  Enter a name and description for the profile.

4.  In the **Data download interval in minutes** field, enter the interval at which Async Client checks for data packages that are ready to be downloaded from Retail essentials to the channel. Data packages are downloaded from the working folder for Commerce Data Exchange.

5.  In the **Data upload interval in minutes** field, enter the interval at which Async Client creates and uploads data from the channel. Data packages are uploaded to the working folder for Commerce Data Exchange.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

