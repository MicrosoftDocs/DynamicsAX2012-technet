---
title: Change AOS ports
TOCTitle: Change AOS ports
ms:assetid: 2ba82a8b-bde4-4813-b231-5f025ff89927
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569616(v=AX.60)
ms:contentKeyID: 35949278
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Change AOS ports [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By default, an instance of Application Object Server (AOS) runs on TCP/IP port 2712, services WSDL port 8101, and services endpoint port 8201. You can change the TCP/IP port, provided that the new port number is not used by another AOS instance or another application. You cannot change the services port. If you want to specify different services ports, you must install a new instance of AOS and specify the port numbers of the services ports in Setup.

Each AOS instance requires a unique TCP/IP port and services port. By default, every time that you install an additional AOS instance on a computer, the port numbers are incremented by 1. For example, by default, the second AOS instance on a computer is assigned to TCP/IP port 2713, services WSDL port 8102, and services endpoint port 8202. If the same port number is used for more than one AOS instance on a computer, one of the AOS instances that have conflicting port numbers does not start. This topic describes how to change the TCP/IP port for an AOS instance by using the Microsoft Dynamics AX 2012 Server Configuration utility.

1.  Open the server configuration utility. Click **Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**.

2.  Verify that the AOS instance and configuration that you want to modify are selected.

3.  On the **Application Object Server** tab, in the **TCP/IP port** box, type the port number that you want the AOS instance to run on, and then click **OK**.

## See also

[Install multiple AOS instances](install-multiple-aos-instances.md)

[Manage AOS performance and availability](manage-aos-performance-and-availability.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

