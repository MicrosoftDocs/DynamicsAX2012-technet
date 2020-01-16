---
title: Microsoft Dynamics AX components
TOCTitle: Microsoft Dynamics AX components
ms:assetid: edf3904f-2c2d-412a-8afa-47dcdbf2396e
ms:mtpsurl: https://technet.microsoft.com/library/Gg732276(v=AX.60)
ms:contentKeyID: 35133218
author: Khairunj
ms.date: 04/29/2014
mtps_version: v=AX.60
---

# Microsoft Dynamics AX components 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the components of Microsoft Dynamics AX that you can install by using the Setup wizard.

## Databases

Databases include the Microsoft Dynamics AX database, the model store, and the baseline database. The AOS connects to the Microsoft Dynamics AX database to process transactions. The AOS connects to the model store to display application elements such as forms and reports. The baseline database contains a model store that is used to upgrade X++ code to Microsoft Dynamics AX 2012. The baseline database is used to analyze application updates before they are applied.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 R3 and Microsoft Dynamics AX 2012 R2, the model store and the business data are stored in separate databases. In earlier versions of Microsoft Dynamics AX 2012, the model store and business data are stored in a single database.</P>



For information about how to install the databases, see [Install the Microsoft Dynamics AX databases](install-the-microsoft-dynamics-ax-databases.md).

Other Microsoft Dynamics AX components, such as Enterprise Portal and Reporting Services extensions, also include databases. The additional databases are created when you install those components and their prerequisites. They are not installed as part of the Microsoft Dynamics AX databases component.

## Server components

Server components include AOS and the Microsoft Dynamics AX components that run on Internet Information Services (IIS). For information about how to install one of the server components, click the corresponding link in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Application Object Server (AOS)</p></td>
<td><p>The AOS service controls communications among Microsoft Dynamics AX clients, databases, and applications.</p></td>
<td><p><a href="install-an-application-object-server-aos-instance.md">Install an Application Object Server (AOS) instance</a></p></td>
</tr>
<tr class="even">
<td><p>Enterprise Portal for Microsoft Dynamics AX (web server)</p></td>
<td><p>Enterprise Portal is a SharePoint site that lets trusted users access Microsoft Dynamics AX data and functionality. Anonymous users can access only limited functionality, such as catalog information and questionnaires.</p></td>
<td><p><a href="install-enterprise-portal.md">Install Enterprise Portal</a></p></td>
</tr>
<tr class="odd">
<td><p>Enterprise Search (web server)</p></td>
<td><p>Enterprise Search lets client users and Enterprise Portal users search for data, forms, and reports in Microsoft Dynamics AX by entering simple search terms. Enterprise Search uses Microsoft Search Server Express or SharePoint Server and the Business Data Connectivity Service (BCS).</p></td>
<td><p><a href="install-search.md">Install Search</a></p></td>
</tr>
<tr class="even">
<td><p>Help Server (web server)</p></td>
<td><p>Help server is an IIS web site that stores Help documentation that is used in Microsoft Dynamics AX. Help server simplifies the task of updating and customizing Help.</p></td>
<td><p><a href="install-help-server.md">Install help server</a></p></td>
</tr>
</tbody>
</table>


## Business intelligence components

Business intelligence components provide reporting and analytical functionality that you can use to view and interpret business data. For information about how to install one of the business intelligence components, click the corresponding link in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reporting Services extensions</p></td>
<td><p>Integration with Microsoft SQL Server Reporting Services lets you create reports by using Reporting Services.</p></td>
<td><p><a href="install-reporting-services-extensions-for-microsoft-dynamics-ax.md">Install Reporting Services extensions for Microsoft Dynamics AX</a></p></td>
</tr>
<tr class="even">
<td><p>Analysis Services configuration</p></td>
<td><p>Integration with Microsoft SQL Server Analysis Services lets you use cubes for business intelligence and analytical reporting in Microsoft Dynamics AX.</p></td>
<td><p><a href="configure-analysis-services-by-running-setup.md">Configure Analysis Services by running Setup</a></p></td>
</tr>
</tbody>
</table>


## Management Reporter components

Management Reporter for Microsoft Dynamics ERP is the recommended financial reporting solution for Microsoft Dynamics AX 2012. For information about how to install one of the Management Reporter components, click the corresponding link in the following table.


> [!NOTE]
> <P>Management Reporter components are available in the Setup wizard in AX 2012 R3 and cumulative update 7 for Microsoft Dynamics AX 2012 R2.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Management Reporter for Microsoft Dynamics ERP</p></td>
<td><p>Use Management Reporter to create, distribute, and analyze financial statements and other financial reports.</p></td>
<td><p><a href="install-management-reporter-server-components.md">Install Management Reporter server components</a></p></td>
</tr>
<tr class="even">
<td><p>Report Designer for Management Reporter</p></td>
<td><p>Report Designer is a component of Management Reporter that is used to create the building blocks that define a report.</p></td>
<td><p><a href="install-report-designer-for-management-reporter.md">Install Report Designer for Management Reporter</a></p></td>
</tr>
</tbody>
</table>


## Client components

Client components give users access to Microsoft Dynamics AX data and functionality. For information about how to install one of the client components, click the corresponding link in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Microsoft Dynamics AX Windows client</p></td>
<td><p>The Microsoft Dynamics AX client is an interface to Microsoft Dynamics AX data and functionality.</p></td>
<td><p><a href="install-the-microsoft-dynamics-ax-client.md">Install the Microsoft Dynamics AX client</a></p></td>
</tr>
<tr class="even">
<td><p>Microsoft Office Add-ins</p></td>
<td><p>Use the Office Add-ins to integrate the Microsoft Dynamics AX client with Microsoft Excel or Microsoft Word.</p>
<p>In Microsoft Dynamics AX 2012 R3 and cumulative update 7 for Microsoft Dynamics AX 2012 R2, the Microsoft Project client add-in is included with the Office Add-ins. With the Microsoft Project client add-in, users can take advantage of features in both Microsoft Dynamics AX and Microsoft Project to manage a project.</p></td>
<td><p><a href="install-office-add-ins.md">Install Office Add-ins</a></p></td>
</tr>
<tr class="odd">
<td><p>Remote Desktop Services integration</p></td>
<td><p>The Remote Desktop Services integration components support integration with local applications, such as Microsoft Word and Microsoft Excel, when Microsoft Dynamics AX is hosted on a Remote Desktop server.</p></td>
<td><p><a href="install-remote-desktop-services-integration.md">Install Remote Desktop Services integration</a></p></td>
</tr>
</tbody>
</table>


## Developer tools

Developer tools are used to customize Microsoft Dynamics AX. For example, you can create customizations or extensions to Enterprise Portal, or you can create advanced production reports for Microsoft Dynamics AX by using Reporting Services. For information about how to install one of the developer tools, click the corresponding link in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Debugger</p></td>
<td><p>The debugger tool provides debugging capabilities for X++ developers.</p></td>
<td><p><a href="install-the-debugger.md">Install the debugger</a></p></td>
</tr>
<tr class="even">
<td><p>Visual Studio Tools</p></td>
<td><p>Visual Studio Tools integrate the development of Microsoft Dynamics AX with Visual Studio. Developers can use these tools to create managed code that accesses X++ objects.</p></td>
<td><p><a href="install-visual-studio-tools.md">Install Visual Studio Tools</a></p></td>
</tr>
<tr class="odd">
<td><p>Trace Parser</p></td>
<td><p>The Trace Parser consolidates information from multiple sources, such as RPC and SQL, to provide an integrated view of the application’s performance at run time.</p></td>
<td><p><a href="install-the-trace-parser.md">Install the Trace Parser</a></p></td>
</tr>
</tbody>
</table>


## Integration components

Integration components enable integration between Microsoft Dynamics AX and external applications. For information about how to install one of the integration components, click the corresponding link in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Web services on IIS</p></td>
<td><p>Web services on IIS are an optional component. Services that are hosted on AOS are available to users and applications over the intranet. However, to consume services over the Internet, you must host services on IIS.</p></td>
<td><p><a href="install-web-services-on-iis.md">Install web services on IIS</a></p></td>
</tr>
<tr class="even">
<td><p>.NET Business Connector</p></td>
<td><p>The .NET Business Connector enables applications to interact with instances of Application Object Server (AOS).</p></td>
<td><p><a href="install-the-net-business-connector.md">Install the .NET Business Connector</a></p>
<div class="alert">

> [!NOTE]
> <P>.NET Business Connector is installed automatically when Microsoft Dynamics AX components that require it are installed.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Synchronization proxy and synchronization service for Microsoft Project Server</p></td>
<td><p>The synchronization proxy and synchronization service for Microsoft Project enable you to synchronize project data in Microsoft Dynamics AX with data in Microsoft Project Server.</p></td>
<td><p><a href="install-the-synchronization-proxy-for-microsoft-project-server.md">Install the synchronization proxy for Microsoft Project Server</a></p>
<p><a href="install-the-synchronization-service-for-microsoft-project-server.md">Install the synchronization service for Microsoft Project Server</a></p></td>
</tr>
</tbody>
</table>


## Management utilities

Management utilities let you configure and manage Microsoft Dynamics AX components and artifacts, such as reports and web controls, from the metadata store.

For information about how to install management utilities, see [Install management utilities](install-management-utilities.md).

## Retail components

Microsoft Dynamics AX for Retail provides mid-market and large retailers a complete head office and point of sale (POS) solution. It can help retailers increase financial returns, improve service, manage growth, and streamline efficiencies. Microsoft Dynamics AX for Retail consists of several components that are typically distributed across multiple computers and locations.

For information about how to install one of the retail components, click the corresponding link in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Description</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Retail headquarters</p></td>
<td><p>Retail headquarters includes components that are necessary to use Retail functionality in Microsoft Dynamics AX.</p></td>
<td><p><a href="install-retail-headquarters.md">Install Retail headquarters</a></p></td>
</tr>
<tr class="even">
<td><p>Retail POS</p></td>
<td><p>Retail POS is the point of sale (POS) program for Microsoft Dynamics AX.</p></td>
<td><p><a href="install-retail-pos.md">Install Retail POS (point of sale)</a></p></td>
</tr>
<tr class="odd">
<td><p>Retail Modern POS</p></td>
<td><p>Modern POS (point of sale) provides the services that enable Windows 8.1 clients to interface with Retail.</p>
<div class="alert">

> [!NOTE]
> <P>Modern POS is available only in AX 2012 R3.</P>


</div></td>
<td><p><a href="install-retail-modern-pos.md">Install Modern POS</a></p></td>
</tr>
<tr class="even">
<td><p>Retail channel database</p></td>
<td><p>Channel databases hold Retail data for one or more retail channels, such as online stores or brick-and-mortar stores.</p>
<div class="alert">

> [!NOTE]
> <P>Retail channel database is available only in AX 2012 R3.</P>


</div></td>
<td><p><a href="install-a-retail-channel-database.md">Install a retail channel database</a></p></td>
</tr>
<tr class="odd">
<td><p>Commerce Data Exchange: Synch Service (Retail Store Connect)</p></td>
<td><p>Synch Service shares data among the head office, stores, and individual point of sale (POS) terminals.</p>
<div class="alert">

> [!NOTE]
> <P>In AX 2012 R3, deploy this component only if you need to support previous versions of Retail POS while you upgrade (N-1).</P>


</div></td>
<td><p><a href="install-commerce-data-exchange-synch-service-retail-store-connect.md">Install Commerce Data Exchange: Synch Service (Retail Store Connect)</a></p></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange: Real-time Service (Retail Transaction Service)</p></td>
<td><p>Real-time Service is an integrated service that provides real-time communication between Microsoft Dynamics AX and individual point of sale (POS) devices.</p></td>
<td><p><a href="install-commerce-data-exchange-real-time-service-retail-transaction-service.md">Install Commerce Data Exchange: Real-time Service (Retail Transaction Service)</a></p></td>
</tr>
<tr class="odd">
<td><p>Commerce Data Exchange: Async Server</p></td>
<td><p>Async Server is part of the asynchronous system that shares data between the Microsoft Dynamics AX database and channel databases. Async Server is installed at headquarters and communicates with the Microsoft Dynamics AX database.</p>
<div class="alert">

> [!NOTE]
> <P>Async Server is available only in AX 2012 R3.</P>


</div></td>
<td><p><a href="install-commerce-data-exchange-async-server.md">Install Commerce Data Exchange: Async Server</a></p></td>
</tr>
<tr class="even">
<td><p>Commerce Data Exchange: Async Client</p></td>
<td><p>Async Client is part of the asynchronous system that shares data between the Microsoft Dynamics AX database and channel databases. Async Client is installed at the channel and communicates with the channel database.</p>
<div class="alert">

> [!NOTE]
> <P>Async Client is available only in AX 2012 R3.</P>


</div></td>
<td><p><a href="install-commerce-data-exchange-async-client.md">Install Commerce Data Exchange: Async Client</a></p></td>
</tr>
<tr class="odd">
<td><p>Retail Channel Configuration Utility (Retail Store Database Utility)</p></td>
<td><p>The Retail Channel Configuration Utility is used configure Retail databases and database connections.</p></td>
<td><p><a href="install-the-retail-channel-configuration-utility-retail-store-database-utility.md">Install the Retail Channel Configuration Utility (Retail Store Database Utility)</a></p></td>
</tr>
<tr class="even">
<td><p>Retail Server</p></td>
<td><p>Retail Server provides services and business logic for Modern POS (point of sale) clients.</p>
<div class="alert">

> [!NOTE]
> <P>Retail Server is available only in AX 2012 R3.</P>


</div></td>
<td><p><a href="install-retail-server.md">Install Retail Server</a></p></td>
</tr>
<tr class="odd">
<td><p>Retail hardware station</p></td>
<td><p>Retail Hardware Station provides services for Modern POS (point of sale) clients and peripherals such as printers, cash drawers, or payment devices that enable these devices to communicate with Retail Server.</p>
<div class="alert">

> [!NOTE]
> <P>Hardware station is available only in AX 2012 R3.</P>


</div></td>
<td><p><a href="install-retail-hardware-station.md">Install Retail Hardware Station</a></p></td>
</tr>
<tr class="even">
<td><p>Retail Online Channel</p></td>
<td><p>Retail Online Channel includes components that are needed to provision an online sales channel using SharePoint. This component allows you to integrate data from Microsoft Dynamics AX into the SharePoint site.</p>
<div class="alert">

> [!NOTE]
> <P>Retail Online Channel is available only in AX 2012 R3 and AX 2012 R2.</P>


</div></td>
<td><p><a href="install-a-retail-online-store-e-commerce.md">Install a Microsoft Dynamics AX Retail online store (e-commerce)</a></p></td>
</tr>
<tr class="odd">
<td><p>Retail mass deployment toolkit</p></td>
<td><p>The Retail mass deployment toolkit enables you to use System Center Configuration Manager (SCCM) to deploy retail components.</p>
<div class="alert">

> [!NOTE]
> <P>Retail mass deployment toolkit is available only in AX 2012 R3.</P>


</div></td>
<td><p><a href="install-the-retail-mass-deployment-toolkit.md">Install retail mass deployment toolkit</a></p></td>
</tr>
<tr class="even">
<td><p>Retail SDK</p></td>
<td><p>The Retail Software Development Kit (SDK) includes sample code and templates that can be used to customize Retail for Microsoft Dynamics AX.</p></td>
<td><p><a href="install-retail-sdk-retail-pos-plug-ins.md">Install Retail SDK (Retail POS Plug-ins)</a></p></td>
</tr>
<tr class="odd">
<td><p>Retail essentials</p></td>
<td><p>Retail essentials is a retail-centric configuration option for Microsoft Dynamics AX. Retail essentials provides a simplified, streamlined user experience that is optimized for organizations that use only the retail management functions of Microsoft Dynamics AX.</p></td>
<td><p><a href="install-retail-essentials-at-headquarters.md">Install Retail Essentials at headquarters</a></p>
<p><a href="install-retail-essentials-at-the-store-or-at-the-point-of-sale.md">Install Retail Essentials at the store or at the point of sale</a></p></td>
</tr>
</tbody>
</table>


## Connector for Microsoft Dynamics

Connector can be used to integrate data between Microsoft Dynamics CRM and Microsoft Dynamics AX. For example, you can integrate Microsoft Dynamics AX customers with Microsoft Dynamics CRM accounts. This gives you access to up-to-date customer and account information in both systems.


> [!NOTE]
> <P>Connector is available through the Microsoft Dynamics AX Setup wizard in AX 2012 R3 and cumulative update 7 for Microsoft Dynamics AX 2012.</P>



For more information about how to install Connector, see [Install Connector for Microsoft Dynamics](install-connector-for-microsoft-dynamics.md).

## RapidStart Connector

The Rapid Start Connector for Microsoft Dynamics AX enables RapidStart Services for Microsoft Dynamics ERP to communicate with an on-premises Microsoft Dynamics AX implementation.


> [!NOTE]
> <P>The RapidStart Connector is available through the Microsoft Dynamics AX Setup wizard in AX 2012 R3, AX 2012 R2, and Microsoft Dynamics AX 2012 Feature Pack.</P>



For more information about how to install RapidStart Connector, see [Install the RapidStart Connector](install-the-rapidstart-connector.md).

## VSS writer

The Volume Shadow Copy Service writer for Microsoft Dynamics AX, (AX VSS writer) can be used with Microsoft System Center 2012 Data Protection Manager (DPM) to protect Microsoft Dynamics AX data and servers. The AX VSS writer coordinates backup and restore operations.


> [!NOTE]
> <P>The AX VSS writer is available through the Microsoft Dynamics AX Setup wizard in AX 2012 R3 and cumulative update 7 for Microsoft Dynamics AX 2012 R2.</P>



For more information about how to install the VSS writer, see [Install the VSS writer for Microsoft Dynamics AX](install-the-vss-writer-for-microsoft-dynamics-ax.md).

## Warehouse Mobile Devices Portal

Warehouse Mobile Devices Portal enables users to complete tasks on mobile devices in the warehouse facility. It includes a website that can be accessed by mobile devices. Warehouse Mobile Devices Portal communicates with AOS by using Windows Communication Foundation (WCF) services.


> [!NOTE]
> <P>The Warehouse Mobile Devices Portal is available through the Microsoft Dynamics AX Setup wizard only in AX 2012 R3.</P>



For more information about how to install the Warehouse Mobile Devices Portal, see [Install Warehouse Mobile Devices Portal](install-warehouse-mobile-devices-portal.md).

## Data Import/Export Framework

The Microsoft Dynamics AX 2012 Data Import/Export Framework is an extension that helps you export data and import it into Microsoft Dynamics AX. Examples of the data that you can import include master data, open stock, and balances.


> [!NOTE]
> <P>The Data Import/Export Framework is available through the Microsoft Dynamics AX Setup wizard only in AX 2012 R3.</P>



For more information about how to install the Data Import/Export Framework, see [Install the Data import/export framework (DIXF, DMF)](install-the-data-import-export-framework-dixf-dmf.md).

  


