---
title: Set up a profile for Async Server
TOCTitle: Set up a profile for Async Server
ms:assetid: 008f91db-9179-48b7-8a2f-f23e10ed8c5a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn621048(v=AX.60)
ms:contentKeyID: 62200198
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailCDXSchedulerInterval
- MsDynAx060.Forms.RetailCDXSchedulerInterval
---

# Set up a profile for Async Server [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A profile for Async Server specifies how frequently Async Client checks for data packages to download and creates data packages to upload. You must configure data download and upload intervals for each instance of Async Client in the environment.

Async Client is part of Commerce Data Exchange, the asynchronous system that shares data between the Microsoft Dynamics AX database and retail channel databases. Async Client is installed for each channel, and communicates with the channel database. Commerce Data Exchange also includes Async Server, which is installed at headquarters and communicates with the Microsoft Dynamics AX database. For more information about Commerce Data Exchange, see the [Commerce Data Exchange documentation](http://go.microsoft.com/fwlink/?linkid=391057) on TechNet.


> [!NOTE]
> <P>The information in this topic applies only if you are using Microsoft Dynamics AX 2012 R3.</P>



1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Async Server profile**.

2.  Click **New** to create a new profile.

3.  Enter a name and description for the profile.

4.  In the **Data download interval in minutes** field, enter the interval at which Async Client checks for data packages that are ready to be downloaded from Microsoft Dynamics AX to the channel. Data packages are downloaded from the working folder for Commerce Data Exchange.

5.  In the **Data upload interval in minutes** field, enter the interval at which Async Client creates and uploads data from the channel. Data packages are uploaded to the working folder for Commerce Data Exchange.

## See also

[Specify working folders for Commerce Data Exchange](specify-working-folders-for-commerce-data-exchange.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

