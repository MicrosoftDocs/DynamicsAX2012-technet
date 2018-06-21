---
title: The architecture of the Microsoft Dynamics ERP RapidStart Connector
TOCTitle: The architecture of the Microsoft Dynamics ERP RapidStart Connector
ms:assetid: 64656e31-00e5-4d3e-a6d0-32d3f796ec69
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn221770(v=AX.60)
ms:contentKeyID: 54161564
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- Connector
- architecture
- Dynamics AX
- RapidStart
- RapidStart endpoint
---

# The architecture of the Microsoft Dynamics ERP RapidStart Connector [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

Microsoft Dynamics ERP RapidStart Connector is a service that enables Microsoft Dynamics ERP RapidStart Services to communicate with an on-premise installation of Microsoft Dynamics AX Application Object Server (AOS). You must install Microsoft Dynamics ERP RapidStart Connector on the same computer that is running the AOS instance. You must install one instance of Microsoft Dynamics ERP RapidStart Connector for each AOS instance that has to connect with RapidStart Services.

You can install more than one instance of Microsoft Dynamics ERP RapidStart Connector on the same computer.

## Prerequisites

Before you install Microsoft Dynamics ERP RapidStart Connector on the computer that is running the AOS instance, install the following applications on the computer:

  - The Microsoft .NET Framework version 4.0

  - ASP.NET 4.0

During the installation of Microsoft Dynamics ERP RapidStart Connector, a check is performed to verify that the prerequisite applications are installed.

## Install Microsoft Dynamics ERP RapidStart Connector

If you have installed Microsoft Dynamics AX 2012 Feature Pack and Microsoft Dynamics AX 2012, an earlier version of Microsoft Dynamics ERP RapidStart Connector is automatically installed together with the AOS instance. You must uninstall this earlier version. You are prompted to uninstall the earlier version when you install the current version of Microsoft Dynamics ERP RapidStart Connector.

1.  On the computer where the AOS instance is installed, download the current version of Microsoft Dynamics ERP RapidStart Connector from the following location:
    
    [Microsoft Dynamics ERP RapidStart Connector](http://go.microsoft.com/fwlink/?linkid=286818)

2.  Run the installer package for Microsoft Dynamics ERP RapidStart Connector. Accept the terms in the license agreement, and select the file location for the installation.

3.  Log on to RapidStart Services.
    

    > [!NOTE]
    > <P>You must be assigned the following permissions to log on to RapidStart Services:</P>
    > <UL>
    > <LI>
    > <P>System administrator for the target AOS instance</P>
    > <LI>
    > <P>Administrator on the computer that is running the AOS instance</P>
    > <LI>
    > <P>A role in Microsoft Dynamics AX that has permission to enable services for Microsoft Dynamics AX</P></LI></UL>



4.  Register the Microsoft Dynamics ERP RapidStart Connector service.

5.  Optional: If your dataset for RapidStart Services is very large, you might want to use the Data Import/Export Framework to load the data into Microsoft Dynamics AX. To use the Data Import/Export Framework, select the settings on the **Data import export framework** tab in the **Microsoft Dynamics ERP RapidStart Connector settings** form. For more information, see Install the Data Import/Export Framework service.

## Register an AOS instance

1.  Open Microsoft Dynamics ERP RapidStart Connector from the **Start** menu.

2.  In the **Microsoft Dynamics ERP RapidStart Services Connector Settings** form, on the **General** tab, in the **Microsoft Dynamics ERP service host** field, enter the name of the computer that is running the AOS instance.

3.  The values in the remaining fields are added automatically. You can modify these values.

4.  Click **Activate**. When activation is completed, an activation URL is displayed in the **Activation ID** field.

5.  Click the link for the activation URL. You might be prompted for the credentials that you used to register for RapidStart Services. Select the service instance for the target AOS instance. The target AOS instance is also known as the endpoint.

6.  Click **Start service**. If the service does not start automatically, you can manually start the AOS service.

7.  You receive the following message: **Endpoint updated successfully**. To verify the update, click **Manage endpoints**. The server name is listed on the **Target deployments** page of RapidStart Services.

Optional: You can load the configuration data from Microsoft Dynamics ERP RapidStart Services into Microsoft Dynamics AX 2012 by using the Data Import/Export Framework. The Data Import/Export Framework is available from Microsoft Dynamics AX InformationSource. You can access InformationSource by using the same credentials that you use for PartnerSource and CustomerSource.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

