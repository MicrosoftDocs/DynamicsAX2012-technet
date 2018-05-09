---
title: Configure an AOS instance to print
TOCTitle: Configure an AOS instance to print
ms:assetid: f19b21a4-6299-48e2-9d1d-938bd0411d07
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569633(v=AX.60)
ms:contentKeyID: 35949379
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure an AOS instance to print 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By default, users cannot print documents or reports from a printer connected to a Microsoft Dynamics AX Application Object Server (AOS). You must enable printing in the AOS and client configuration files, as described in this topic.

## Before you begin

1.  You must configure the printer attached to the AOS server as a shared printer by using Windows Server Print Management features. You must also add the printer to the list of available printers on client workstations. For more information, see the Windows Server Print Management documentation on Microsoft TechNet.

2.  You must configure the printer so that the account that is used by the AOS service has permission to access the printer. If the account does not have permission, AOS and Microsoft Dynamics AX clients cannot print from the AOS. By default, the Network Service account does not have permission to connect to printers on a network. If the AOS is running as Network Service, you must grant the Network Service account access to the printer.

## Configure an AOS instance to print

1.  Open the server configuration utility. Click **Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**.

2.  Verify that the AOS instance and configuration that you want to modify are selected.

3.  On the **Application Object Server** tab, click **Allow clients to connect to printers on this server**, and then click **OK**.

## Configure a client to print

1.  Open the client configuration utility. Click **Start** \> **Control Panel** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Configuration**.

2.  Verify that the configuration target and configuration that you want to modify are selected.

3.  On the **Connection** tab, click **Connect to printers on the server**, and then click **OK**.

## See also

[Batch server overview](batch-server-overview.md)

[Configure an AOS instance as a batch server](configure-an-aos-instance-as-a-batch-server.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

