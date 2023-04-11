---
title: Troubleshoot a connection
TOCTitle: Troubleshoot a connection
ms:assetid: 038b12e9-0218-4fca-8737-9c38184fe155
ms:mtpsurl: https://technet.microsoft.com/library/JJ878424(v=AX.60)
ms:contentKeyID: 50632069
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Troubleshoot a connection 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Connection profiles enable the components of Retail to communicate with each other. When you are setting up a connection profile and test the connection, you may receive an error, such as "Cannot connect to Synch Service," "Cannot connect to database," or "Error getting error message." Use the information in this topic to troubleshoot these errors.

## Troubleshoot connections in AX 2012 R3

If you’re using AX 2012 R3, see [Troubleshoot issues in Async Server or Async Client](troubleshoot-issues-in-async-server-or-async-client.md) for more information about troubleshooting connections.

## Troubleshoot connections in AX 2012 R2 or AX 2012 Feature Pack

If you’re using AX 2012 R2 or AX 2012 Feature Pack, use the following troubleshooting steps.

  - Test connections between components. Use the **Test connection** buttons in the **Database profile** form, the **AOS profile** form, and the **Synch Service profile** form.

  - Use ping, Telnet, or another network utility to verify that the Microsoft Dynamics AX computer at the head office can connect to the location computer. If it cannot, make sure that the firewall on the location computer is open to the required ports or programs. If the firewall is already open, work with the network administrator to correct the network configuration.

  - On the location computer, verify that remote connections to Microsoft SQL Server are enabled, and that SQL Server users and permissions are set up correctly. For more information about these requirements, see [Configure SQL Server for the Retail databases](configure-sql-server-for-the-retail-databases.md).

  - Verify that Commerce Data Exchange: Synch Service is running on the location computer. If it is, see whether the Synch Service log contains errors.
    

    > [!NOTE]
    > <P>If logging is not turned on, turn it on, restart Synch Service, and then check the log. For information about how to set up logging, see <A href="configure-settings-for-synch-service.md">Configure settings for Synch Service</A>.</P>



  - Verify that the connection information in the database profile is correct.

  - Bypass Internet Protocol security (IPsec) for the location and in the Synch Service settings on the location computer. For information about how to bypass IPsec, see [Configure or bypass IPsec for Synch Service](configure-or-bypass-ipsec-for-synch-service.md).

  


