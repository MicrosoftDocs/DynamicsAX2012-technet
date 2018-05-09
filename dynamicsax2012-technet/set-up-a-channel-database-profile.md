---
title: Set up a channel database profile
TOCTitle: Set up a channel database profile
ms:assetid: 03e67a5d-792b-4d3f-9122-21eab9cd6b61
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn621049(v=AX.60)
ms:contentKeyID: 62200199
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailCDXDataStore
- MsDynAx060.Forms.RetailCDXDataStore
---

# Set up a channel database profile 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A channel database profile provides the information that enables Microsoft Dynamics AX to communicate with a retail channel database.


> [!NOTE]
> <P>The information in this topic applies only if you are using Microsoft Dynamics AX 2012 R3.</P>



1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Channel database**.

2.  Click **New** to create a new channel database profile.

3.  Enter the following information:
    
      - **Channel database ID** – Type a name for the profile.
    
      - **Channel data group** – Select a channel data group for the database. When you run a distribution schedule, a data package is generated for each data group. All channel databases in a data group subscribe to the same data.
        
        A data group can contain one or more databases, but a database can belong to only one data group.
    
      - **User name** and **Password** – Enter the user name and password that Async Client uses to communicate with Async Server. The user name is case-sensitive. You must use a unique user name for each channel database profile. The user name and password that you enter are created and used only for the channel database profile. The user is not required to exist in Microsoft Dynamics AX, in Active Directory, or on the local operating system.
    
      - **Async Server profile** – Select the Async Server profile to use with the database.

4.  On the **Retail channel** FastTab, click **Add** to select the channels that use this database.

5.  If you are using features that require Retail Server, such as Retail Modern POS, enter channel database information in the **Retail Server** FastTab. Enter the name of the server that hosts the channel database, and enter the name of the channel database.

6.  If you are using Synch Service for compatibility with an earlier version of Retail POS, the **Synch Service** FastTab is displayed. For more information about how to use earlier versions of Retail POS, see the [Support for Previous POS Versions](http://go.microsoft.com/fwlink/?linkid=259822) white paper.

7.  To synchronize all data for the channel database, click **Full data sync** and then select the distribution schedule that is named **Full sync**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

