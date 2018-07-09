---
title: Reporting architecture
TOCTitle: Reporting architecture
ms:assetid: 93229fa6-e507-47a9-8a8b-1d2cb28f4bfe
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd361996(v=AX.60)
ms:contentKeyID: 35132767
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Reporting architecture [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the architecture of the reporting functionality in Microsoft Dynamics AX.

## Architecture for typical installations

The following diagram illustrates how a report is rendered in Microsoft Dynamics AX. This diagram represents the reporting architecture when one of the following versions of Microsoft SQL Server Reporting Services is installed:

  - Reporting Services 2008 in native mode

  - Reporting Services 2008 in SharePoint integrated mode

  - Reporting Services 2008 R2 in native mode

  - Reporting Services 2008 R2 in SharePoint integrated mode

  - Reporting Services 2012 in native mode

  - Reporting Services 2014 in native mode


> [!NOTE]
> <P>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or R3.</P>



![Reporting architecture](images/Dd361996.BI_SSRSArchitecture(AX.60).gif "Reporting architecture")

To better understand how a report is rendered, review the following steps:

1.  **A user requests a report.**
    
    A menu item in the Microsoft Dynamics AX client may be bound to a report for Reporting Services. After a user clicks the menu item, a parameters form is displayed to the user. The user enters parameters to filter the data that is displayed on the report.
    
    The Microsoft Dynamics AX client then requests the report from an instance of Reporting Services. The request includes the parameters that the user entered.

2.  **Reporting Services receives the request and requests the report data from the Microsoft Dynamics AX server.**
    
    Reporting Services receives the request and examines the report. The report is stored as an .rdl file. The .rdl file indicates the report’s data source. The data source may be a Microsoft Dynamics AX query, a report data provider class, or an external data source that is accessed through report data methods.
    
    If a Microsoft Dynamics AX data source is used for the report, Reporting Services uses the Microsoft Dynamics AX data extension to retrieve the data.
    
    Reporting Services then requests metadata about the data source from Microsoft Dynamics AX. Then Reporting Services requests the data for the report.

3.  **The Microsoft Dynamics AX server receives the request and sends the report data back to Reporting Services.**
    
    The Microsoft Dynamics AX services examine the query in the Application Object Tree (AOT) to return the requested metadata. The services also run the query to generate the data for the report.
    
    Microsoft Dynamics AX then returns the metadata and data to Reporting Services.
    

    > [!NOTE]
    > <P>Microsoft Dynamics AX enforces security on all data that it returns. If the user who is running the report is not allowed to see a specific field, the data for that field is not returned.</P>



4.  **Reporting Services renders the report and sends it to the Microsoft Dynamics AX client.**
    
    The Microsoft Dynamics AX customization extension formats the report. The customization extension uses metadata to provide automatic formatting of data and can affect the positioning and layout of elements on the report.
    
    Reporting Services then renders the report into a visual representation and sends that representation to the Microsoft Dynamics AX client.

5.  **The report is displayed to the user.**
    
    The Microsoft Dynamics AX client displays the report to the user in the report viewer control.

## Architecture for Reporting Services 2012 or 2014 installations in SharePoint integrated mode

The following diagram illustrates how a report is rendered in Microsoft Dynamics AX. This diagram represents the reporting architecture when Reporting Services 2012 or 2014 is installed in SharePoint integrated mode.


> [!NOTE]
> <P>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or R3.</P>



![Architecture for SSRS 2012 SharePoint mode](images/Dd361996.BI_SSRSArchitecture_(AX.60).gif "Architecture for SSRS 2012 SharePoint mode")

To better understand how a report is rendered, review the following steps:

1.  **A user requests a report.**
    
    A menu item in the Microsoft Dynamics AX client may be bound to a report for Reporting Services. After a user clicks the menu item, a parameters form is displayed to the user. The user enters parameters to filter the data that is displayed on the report.
    
    The Microsoft Dynamics AX client then requests the report from the Reporting Services service application in SharePoint. The request includes the parameters that the user entered.

2.  **The Reporting Services service application receives the request and requests the report data from the Microsoft Dynamics AX server.**
    
    The Reporting Services service application receives the request and examines the report. The report is stored as an .rdl file. The .rdl file indicates the report’s data source. The data source may be a Microsoft Dynamics AX query, a report data provider class, or an external data source that is accessed through report data methods.
    
    If a Microsoft Dynamics AX data source is used for the report, the Reporting Services service application uses the Microsoft Dynamics AX data extension to retrieve the data.
    
    The Reporting Services service application then requests metadata about the data source from Microsoft Dynamics AX. Then the Reporting Services service application requests the data for the report.

3.  **The Microsoft Dynamics AX server receives the request and sends the report data back to the Reporting Services service application.**
    
    The Microsoft Dynamics AX services examine the query in the Application Object Tree (AOT) to return the requested metadata. The services also run the query to generate the data for the report.
    
    Microsoft Dynamics AX then returns the metadata and data to the Reporting Services service application.
    

    > [!NOTE]
    > <P>Microsoft Dynamics AX enforces security on all data that it returns. If the user who is running the report is not allowed to see a specific field, the data for that field is not returned.</P>



4.  **The Reporting Services service application renders the report and sends it to the Microsoft Dynamics AX client.**
    
    The Microsoft Dynamics AX customization extension formats the report. The customization extension uses metadata to provide automatic formatting of data and can affect the positioning and layout of elements on the report.
    
    The Reporting Services service application then renders the report into a visual representation and sends that representation to the Microsoft Dynamics AX client.

5.  **The report is displayed to the user.**
    
    The Microsoft Dynamics AX client displays the report to the user in the report viewer control.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

