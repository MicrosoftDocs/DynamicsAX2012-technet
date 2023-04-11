---
title: Drain users from an AOS
TOCTitle: Drain users from an AOS
ms:assetid: d19bd816-cd9e-423a-94c7-aceb946baa30
ms:mtpsurl: https://technet.microsoft.com/library/Hh433538(v=AX.60)
ms:contentKeyID: 36941331
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Drain users from an AOS 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to close client sessions that are connected to an instance of Application Object Server (AOS) for Microsoft Dynamics AX. When you close client sessions without force, you are said to drain users. Administrators drain users from an AOS instance before they perform maintenance on the server or take it offline.


> [!IMPORTANT]
> <P>The following procedure requires that you click the <STRONG>Reject new clients</STRONG> button in Microsoft Dynamics AX. After you click this button, you must not close your client. If you close your client before you click the <STRONG>Accept new clients</STRONG> button, you cannot open a new client session unless you restart the AOS instance by using the Windows Services Management console, or unless you reset the SysServerSessions table in Microsoft SQL Server to a value of 1.</P>



1.  Click **System administration** \> **Common** \> **Users** \> **Online users**.

2.  On the **Server instances** tab, select the AOS instance that you want to perform maintenance on.

3.  Click **Reject new clients**.

4.  When you are prompted, click **OK** to stop the AOS instance from accepting new client connections.
    
    After 5 minutes, all users receive a message informing them that they must save their work, because the administrator is shutting down the AOS instance. No new client connections are accepted during this time. The server forces client sessions to close after they have been idle for 2 minutes. Client sessions for administrators are never closed. When the number of clients that are connected to the AOS instance is displayed as 0 (zero), you can perform maintenance on the server.

5.  After you have finished performing maintenance on the server, click **Accept new clients** or restart the AOS instance.

## See also

[Start or stop the AOS Windows service](start-or-stop-the-aos-windows-service.md)

[Manage load balancing](manage-load-balancing.md)

  


