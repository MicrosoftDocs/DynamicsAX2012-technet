---
title: Install multiple AOS instances
TOCTitle: Install multiple AOS instances
ms:assetid: 9522d7e0-7bac-492e-a8b3-63d97676ecfc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ee355067(v=AX.60)
ms:contentKeyID: 35132772
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install multiple AOS instances 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to install multiple instances of Application Object Servers (AOS) for Microsoft Dynamics AX 2012. You can install up to 99 AOS instances in your environment.


> [!IMPORTANT]
> <P>You must install an initial AOS instance and complete the <STRONG>Initialization checklist</STRONG> on that instance before you install additional AOS instances. If you install additional AOS instances before you have completed the <STRONG>Initialization checklist</STRONG> those AOS instances will not start. For more information, see <A href="install-an-aos-instance.md">Install an AOS instance</A>.</P>



## Install an AOS instance on multiple computers

In most production environments, you install multiple AOS instances, each on a different server. You can use multiple AOS instances to support batch processing and load balancing. Install each AOS instance in the way that is described in [Install an AOS instance](install-an-aos-instance.md), and make sure that you point every AOS instance to the same database. The first user who installs an AOS instance is automatically added to Microsoft Dynamics AX as an administrator. If subsequent AOS instances are installed by different users, you must manually add those users to the Microsoft Dynamics AX System administrator role to grant them administrative rights in Microsoft Dynamics AX.

You can use a single domain account for all instances of the AOS service, or you can specify a different account for each instance.

## Install multiple AOS instances on one computer

In some testing and development scenarios, you may want to install multiple AOS instances on the same computer. For example, if you are developing code for multiple versions of Microsoft Dynamics AX, you can install different versions of AOS side by side.

Install each AOS instance in the way that is described in [Install an AOS instance](install-an-aos-instance.md). If you install an AOS instance on a server that already has an AOS instance, you must specify a unique port number for each instance. By default, every time that you install an additional AOS instance on a computer, the TCP/IP, WSDL, and NET-TCP port numbers are incremented by 1. If the same port number is used for more than one AOS instance on a computer, one of the AOS instances that have conflicting port numbers does not start.

## See also

[Application Object Server security and protection](application-object-server-security-and-protection.md)

[Configure an AOS instance as a batch server](configure-an-aos-instance-as-a-batch-server.md)

[Manage an AOS configuration](manage-an-aos-configuration.md)

  


