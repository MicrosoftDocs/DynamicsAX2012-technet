---
title: Troubleshoot the Microsoft Dynamics ERP Connector service
TOCTitle: Troubleshoot the Microsoft Dynamics ERP Connector service
ms:assetid: 2cf6d8d4-bfcf-4807-80dc-d3d07285066b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn193991(v=AX.60)
ms:contentKeyID: 52348246
ms.date: 03/16/2013
mtps_version: v=AX.60
---

# Troubleshoot the Microsoft Dynamics ERP Connector service 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes solutions for issues that you might encounter when you work with the Microsoft Dynamics ERP RapidStart Connector.

## The Connector service does not start

Make sure that the administrator account that you provided credentials for when you set up the Microsoft Dynamics ERP RapidStart Connector is an administrator account in your implementation of Microsoft Dynamics AX 2012.

Open Windows Event Viewer, and check whether any errors are reported. Resolve any errors before you try to start the Connector service again.

If the instance of Microsoft Dynamics AX Application Object Server (AOS) where the Microsoft Dynamics ERP RapidStart Connector is installed is a virtual machine, make sure that the virtual machine is connected to the Internet. In some cases, you must update network-related settings before the virtual machine has Internet access.

## The Activate link in the Microsoft Dynamics ERP RapidStart Connector is not available

The version of the Microsoft Dynamics ERP RapidStart Connector that you are using is out of date. Uninstall this version, and then download and install the current version from [Microsoft Dynamics ERP RapidStart Connector](http://go.microsoft.com/fwlink/?linkid=286818).

Follow these steps to check the version number of the Microsoft Dynamics ERP RapidStart Connector that is installed on the same computer as your AOS instance.

1.  Open Windows Control Panel, and then click **Programs** \> **Uninstall a program**.

2.  In the list of installed programs, locate **Microsoft Dynamics ERP RapidStart Services Connector**.
    
    The version number is displayed in the **Version** column.

