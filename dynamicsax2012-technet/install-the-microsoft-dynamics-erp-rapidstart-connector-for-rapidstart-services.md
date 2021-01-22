---
title: Install the Microsoft Dynamics ERP RapidStart Connector for RapidStart Services
TOCTitle: Install the Microsoft Dynamics ERP RapidStart Connector for RapidStart Services
ms:assetid: 6090d764-4615-4ea5-bba5-90cbaff4df96
ms:mtpsurl: https://technet.microsoft.com/library/Dn193996(v=AX.60)
ms:contentKeyID: 52348249
author: Khairunj
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- RapidStart
- Connector service
---

# Install the Microsoft Dynamics ERP RapidStart Connector for RapidStart Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

Microsoft Dynamics ERP RapidStart Connector is a service that enables Microsoft Dynamics ERP RapidStart Services to communicate with an on-premise installation of Microsoft Dynamics AX Application Object Server (AOS). You must install Microsoft Dynamics ERP RapidStart Connector on the same computer that is running the AOS instance. You must install one instance of Microsoft Dynamics ERP RapidStart Connector for each AOS instance that has to connect with RapidStart Services.

You can install more than one instance of Microsoft Dynamics ERP RapidStart Connector on the same computer.

## Prerequisites

Before you install Microsoft Dynamics ERP RapidStart Connector on the computer that is running the AOS instance, install the following applications:

  - The Microsoft .NET Framework version 4.0

  - ASP.NET 4.0

A check is performed during the installation of Microsoft Dynamics ERP RapidStart Connector to verify that the prerequisite applications are installed.

## Install Microsoft Dynamics ERP RapidStart Connector

If you have installed Microsoft Dynamics AX 2012 Feature Pack or Microsoft Dynamics AX 2012, an earlier version of Microsoft Dynamics ERP RapidStart Connector is automatically installed together with the AOS instance. You must uninstall this earlier version of Microsoft Dynamics ERP RapidStart Connector. You are prompted to uninstall the earlier version when you install the current version of Microsoft Dynamics ERP RapidStart Connector.

1.  On the computer where the AOS instance is installed, download the current version of Microsoft Dynamics ERP RapidStart Connector from the following location:
    
    [Microsoft Dynamics ERP RapidStart Connector](https://go.microsoft.com/fwlink/?linkid=286818).

2.  Run the installer package for Microsoft Dynamics ERP RapidStart Connector. Accept the terms in the license agreement, and select the file location for the installation.

3.  Enter the logon credentials for the system administrator for RapidStart Services.
    
    These logon credentials must belong to a valid administrator in the Microsoft Dynamics AX 2012 implementation. The Microsoft Dynamics ERP RapidStart Connector does not run on these credentials, but if valid credentials are not entered, the service will not start.

4.  Register the AOS instance as the endpoint for the Microsoft Dynamics ERP RapidStart Connector instance. For more information about how to register an AOS instance for Microsoft Dynamics ERP RapidStart Connector, see [Register a Microsoft Dynamics ERP endpoint in RapidStart Services](register-a-microsoft-dynamics-erp-endpoint-in-rapidstart-services.md).

## See also

[The architecture of the Microsoft Dynamics ERP RapidStart Connector](the-architecture-of-the-microsoft-dynamics-erp-rapidstart-connector.md)

  


