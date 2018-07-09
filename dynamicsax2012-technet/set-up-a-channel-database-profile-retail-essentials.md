---
title: Set up a channel database profile (Retail essentials)
TOCTitle: Set up a channel database profile (Retail essentials)
ms:assetid: ac9c49cc-6d3d-41a8-8bcb-a03cf2075da0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736929(v=AX.60)
ms:contentKeyID: 62200406
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- ac9c49cc-6d3d-41a8-8bcb-a03cf2075da0
- MsDynAx060.ac9c49cc-6d3d-41a8-8bcb-a03cf2075da0
---

# Set up a channel database profile (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A channel database profile provides the information that enables Retail essentials to communicate with a retail channel database. This topic explains how to set up a channel database profile.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



1.  Click **Retail essentials** \> **Data synchronization** \> **Setup** \> **Store integration** \> **Channel database**.

2.  Click **New** to create a new channel database profile.

3.  Enter the following information:
    
      - **Channel database ID** – Type a name for the profile.
    
      - **Channel data group** – Select a channel data group for the database. When you run a distribution schedule, a data package is generated for each data group. All channel databases in a data group subscribe to the same data.
        
        A data group can contain one or more databases, but a database can belong to only one data group.
    
      - **User name** and **Password** – Enter the user name and password that Commerce Data Exchange: Async Client uses to communicate with Commerce Data Exchange: Async Server.
    
      - **Async Server profile** – Select the Async Server profile to use together with the database.

4.  On the **Retail channel** FastTab, click **Add** to select the channels that use this database.

5.  On the **Retail Server** FastTab, enter the name of the server that hosts the channel database, and enter the name of the channel database.

6.  To synchronize all data for the channel database, click **Full data sync**, and then select the distribution schedule that is named **Full sync**.

## See also

[Set up a profile for Async Server](set-up-a-profile-for-async-server.md)

[Create a channel data group (Retail essentials)](create-a-channel-data-group-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

