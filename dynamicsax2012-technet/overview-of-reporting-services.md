---
title: Overview of Reporting Services
TOCTitle: Overview of Reporting Services
ms:assetid: 38f68dc5-b863-44bf-b913-a640bb3a9cfd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309644(v=AX.60)
ms:contentKeyID: 35132837
ms.date: 06/04/2014
mtps_version: v=AX.60
---

# Overview of Reporting Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft SQL Server Reporting Services is now the primary reporting platform for Microsoft Dynamics AX. The default, preconfigured reports that are included with Microsoft Dynamics AX run on the Reporting Services platform.

Before you integrate Microsoft Dynamics AX and Reporting Services, review this topic to better understand the concepts and components of Reporting Services.

## Reporting Services modes

When you install Reporting Services, you must select a mode in which to run Reporting Services. Two modes are available: native mode and SharePoint integrated mode.

## Native mode

In native mode, a report server is a stand-alone application server. Native mode is the default mode for Reporting Services.

If the report server is running in native mode, the reports that are included with Microsoft Dynamics AX are deployed to the Report Manager website. You can manage and view the reports from this website. The following picture shows the Report Manager website that contains Microsoft Dynamics AX reports.

![Reporting Services in native mode](images/Dd309644.BI_SSRSNativeMode(AX.60).png "Reporting Services in native mode")

For instructions about how to configure Reporting Services in native mode, see [Before you install the Reporting Services extensions](before-you-install-the-reporting-services-extensions.md).

## SharePoint integrated mode

In SharePoint integrated mode, a report server runs in a SharePoint server farm.

> [!NOTE]
> <P>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or later.</P>

If the report server is running in SharePoint integrated mode, the reports that are included with Microsoft Dynamics AX are deployed to a document library on a SharePoint website. You can manage and view the reports from this document library. The following picture shows a document library that contains Microsoft Dynamics AX reports.

![Document library in SharePoint](images/Dd309644.BI_DocumentLibrary(AX.60).png "Document library in SharePoint")

For instructions about how to configure Reporting Services in SharePoint integrated mode, see [Before you install the Reporting Services extensions](before-you-install-the-reporting-services-extensions.md).

## Reporting Services Configuration Manager

After you install a Reporting Services instance, you can use Reporting Services Configuration Manager. This tool helps you configure settings and specify which accounts are used by the Reporting Services instance. For more information about how to use Reporting Services Configuration Manager, see [Before you install the Reporting Services extensions](before-you-install-the-reporting-services-extensions.md).


> [!NOTE]
> <P>Reporting Services Configuration Manager is not used to configure and administer an instance of Reporting Services 2012 or 2014 that is running in SharePoint integrated mode.</P>



The following picture shows the Reporting Services Configuration Manager that is included with Reporting Services 2012.

![Reporting Services Configuration Manager](images/Dd309644.BI_SSRSConfigurationManager(AX.60).png "Reporting Services Configuration Manager")

## Report Manager

When you configure a Reporting Services instance that is running in native mode, a website that is named *Report Manager* is created. As the Microsoft Dynamics AX administrator, you deploy the reports that are included with Microsoft Dynamics AX to this site.

By default, the URL of the Report Manager site is http://[SSRSServerName]:80/Reports. The following picture shows the Report Manager website.

![Report Manager](images/Dd309644.BI_ReportManager(AX.60).png "Report Manager")

## Reporting Services web service

When you configure a Reporting Services instance, a web service is created. Users cannot access reports unless this service is running.

The URL of the web service is typically http://[SSRSServerName]:80/ReportServer. However, if you are using Reporting Services 2012 or 2014 in SharePoint integrated mode, the URL is typically http://[SharePointServerName]/_vti_bin/ReportServer or http:[SharePointServerName]/sites/[SiteName]/_vti_bin/ReportServer.

The following picture shows the web service for an instance of Reporting Services that is running in native mode.

![Reporting Services web service](images/Dd309644.BI_SSRSWebService(AX.60).png "Reporting Services web service")

## Report Builder

Report Builder is an ad hoc reporting tool that lets users create their own reports. For more information about how to use Report Builder to create a report that accesses Microsoft Dynamics AX data, see [Create a report by using SQL Server Report Builder to connect to a cube](create-a-report-by-using-sql-server-report-builder-to-connect-to-a-cube.md).

The following picture shows Report Builder in design mode.

![Report Builder](images/Gg731920.BI_ReportBuilderUsingCube(AX.60).png "Report Builder")

  


