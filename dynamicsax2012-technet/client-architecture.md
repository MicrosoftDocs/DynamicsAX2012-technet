---
title: Client architecture
TOCTitle: Client architecture
ms:assetid: 11025338-70dd-4bba-8c13-37c58779f1c5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309595(v=AX.60)
ms:contentKeyID: 35132550
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Client architecture [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the high-level architecture of the Windows client for Microsoft Dynamics AX.

The client application is a 32-bit Windows application that provides a rich user interface for the Microsoft Dynamics AX application. The client is typically used by employees in the organization. External users, and users who do not require the rich user interface that the client application offers, can use Enterprise Portal for Microsoft Dynamics AX. Enterprise Portal provides access to the Microsoft Dynamics AX application from a web browser.


> [!NOTE]
> <P>Because of the volume of communication that passes between the client and the server, you may experience diminished response time if your network does not meet the minimum requirements for latency and bandwidth. For more information, see the <A href="http://go.microsoft.com/fwlink/?linkid=165377">System requirements</A>.</P>



## Client functionality

The client application provides the following functionality:

  - **Rich user interface** – The client application that provides a rich user interface that consists of forms, menus, and controls. The client includes more than 3,000 forms that are built from a combination of metadata and X++ code. The Microsoft Dynamics AX forms use X++ to process events and business logic. Forms can host managed WinForms or Windows Presentation Foundation (WPF) controls, and X++ can interoperate with managed, or .NET, classes and assemblies.

  - **The MorphX development environment** – The development environment is integrated into the client application. Authorized developers can use the MorphX development environment to enhance or customize the Microsoft Dynamics AX application.

  - **Integration with Microsoft Office** – The Microsoft Dynamics AX application can be integrated with Microsoft Office. Data in lists can be exported to Microsoft Excel, where that data can be formatted, manipulated, updated, modified, and saved back into Microsoft Dynamics AX. You can integrate Outlook with CRM to synchronize schedules and tasks bi-directionally.

  - **Unified communications** – The client provides integrated unified communications by using Microsoft Office Communicator. Important forms and controls use presence awareness for contacts and employees. These forms and controls also provide a visual indicator of the availability of contacts. Users can also use real-time messaging, such as instant messaging and outgoing voice communication.

  - **Integration with the Telephony Application Programming Interface (TAPI)** – The client supports TAPI, which is a standard Windows interface that is used to integrate telephone systems and Windows-based software. For example, your application displays information about the caller when you receive a call.

  - **Reports** – The Microsoft Dynamics AX application provides reports that are based on Microsoft SQL Server Reporting Services (SSRS).

## Client/server communication

The client communicates with various Microsoft Dynamics AX components in the following ways:

  - The client uses the remote procedure call (RPC) protocol to communicate with Application Object Server (AOS). The client never accesses the database or metadata directly. AOS sends the application objects and data to the client.

  - The data layer that the client uses is based on data sources that are specified in metadata for forms and queries. In addition, any X++ code that is required to retrieve data can use the built-in language support to query and adjust data.

  - The client uses a report Web Part to interact with the report server. By calling the web services that are exposed by the report server, the report control in the Web Part displays information that is contained in Reporting Services reports. These reports can include either transactional data from the Microsoft Dynamics AX application or OLAP cubes from Microsoft SQL Server Analysis Services. Cubes provide business analytics and key performance indicators (KPIs).

  - The client provides workflow forms, alerts, and controls so that users can participate in the business process by using the Workflow system. The Workflow system is a Microsoft Dynamics AX component that enables workflow processes by using Windows Communication Foundation classes.

  - The client provides a Help viewer, which is an application that displays context-sensitive Help topics. The Help topics are retrieved from a Help server that is located on-premises.

  - The client also provides Role Centers, or role-based home pages, for users. Role Centers provide role-specific tasks, activities, alerts, reports, and business intelligence that help users increase their productivity. To interact with the Role Centers that are provided by Enterprise Portal and hosted on Internet Information Services (IIS), the client uses a browser control.

The following figure illustrates the high-level client architecture.

![Architecture of the Microsoft Dynamics AX client](images/Dd309595.ClientArchitecture(AX.60).gif "Architecture of the Microsoft Dynamics AX client")

## See also

[System architecture](system-architecture.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

