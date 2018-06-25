---
title: Set up a store database profile
TOCTitle: Set up a store database profile
ms:assetid: 1f059b04-1ef8-4d5f-83ae-fb458fee7938
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677385(v=AX.60)
ms:contentKeyID: 49384165
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up a store database profile [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

A database profile provides the information that enables Microsoft Dynamics AX to communicate with a retail store database or an online channel database.


> [!NOTE]
> <P>The information in this topic applies only to Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack.</P>



1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Database profiles**.

2.  Press CTRL+N to create a new database profile. Optionally, you can click **Copy** to create a new profile that is based on the currently selected profile.

3.  Complete the following information:
    
      - **Name** – Type a name for the profile.
    
      - **Version** – Select the version of Microsoft SQL Server for the database.
    
      - **Server name** – Type the name of the database server.
    
      - **Database name** – Type the name of the database that is used for the selected store or register.
    
      - **Encrypt database connection** – Select the check box to use the encrypted connection option in SQL Server for this database connection.
    
      - **Commerce Data Exchange: Synch Service** – Select the profile for the correct instance of Commerce Data Exchange: Synch Service.

4.  Click **Test connection** to test the connection string for the selected database profile. For information about how to resolve connection errors, see [Troubleshoot a connection](troubleshoot-a-connection.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

