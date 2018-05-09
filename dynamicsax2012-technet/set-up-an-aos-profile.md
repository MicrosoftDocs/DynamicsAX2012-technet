---
title: Set up an AOS profile
TOCTitle: Set up an AOS profile
ms:assetid: 3d6d6d31-c732-4310-b7a1-6d8f06d06608
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677394(v=AX.60)
ms:contentKeyID: 49384174
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up an AOS profile 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

An Application Object Server (AOS) profile provides the connection string that enables Commerce Data Exchange: Synch Service to communicate with the Microsoft Dynamics AX database.


> [!NOTE]
> <P>The information in this topic applies only to Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack.</P>



1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **AOS profiles**.

2.  Press CTRL+N to create a new AOS profile.

3.  Complete the following information:
    
      - **Name** – Enter a unique name for the profile.
    
      - **Server name** – Enter the name of the server where the AOS instance is installed.
    
      - **Instance name** – The name of the AOS instance.
    
      - **TCP/IP port** – Enter the TCP/IP port for the AOS instance.
    
      - **Commerce Data Exchange: Synch Service** – Select the Synch Service profile to associate with the AOS profile.

4.  Click **Test connection** to confirm that the connection string for the selected AOS profile is correct. For information about how to resolve connection errors, see [Troubleshoot a connection](troubleshoot-a-connection.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

