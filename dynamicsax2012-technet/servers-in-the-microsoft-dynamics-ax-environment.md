---
title: Servers in the Microsoft Dynamics AX environment
TOCTitle: Servers in the Microsoft Dynamics AX environment
ms:assetid: 1369d6c1-b19c-436b-b726-49a26c15867c
ms:mtpsurl: https://technet.microsoft.com/library/Aa496913(v=AX.60)
ms:contentKeyID: 35132554
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Servers in the Microsoft Dynamics AX environment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A production deployment of Microsoft Dynamics AX requires multiple servers. This topic describes the types of server that may be required in your implementation.

## Servers in a minimum installation of Microsoft Dynamics AX

A minimum installation of Microsoft Dynamics AX consists of a business database, a model store, an instance of Application Object Server (AOS), and at least one client. These components can be installed on computers that are arranged in various topologies, but the system does not run unless all elements are installed.

## Application Object Server

An AOS server is a computer that runs the AOS Windows service. The AOS service controls communications among Microsoft Dynamics AX clients, databases, and applications. You can install the AOS on a single computer, or you can create a server cluster for load balancing.

## Database server

A Microsoft SQL Server database server hosts the database that stores Microsoft Dynamics AX transaction data. The database server also hosts the model store, which is the database that stores application elements. These application elements include customizations.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 R3 and AX 2012 R2, the model store and the business data are stored in separate databases. In earlier versions of AX 2012, the model store and business data are stored in a single database.</P>



## Servers in a complete installation of Microsoft Dynamics AX

For some Microsoft Dynamics AX functionality, you must have one or more of the following additional servers.

## Report server

A report server is a server that runs Microsoft SQL Server Reporting Services. Reporting Services is a server-based solution that lets users create and publish both traditional, paper-based reports and interactive, web-based reports.

For more information about how to set up a report server, see [Install Reporting Services extensions for Microsoft Dynamics AX](install-reporting-services-extensions-for-microsoft-dynamics-ax.md).

## Analysis server

An analysis server enhances the reporting functionality in Microsoft Dynamics AX by linking to Microsoft SQL Server Analysis Services. An analysis server provides enhanced support for online analytical processing (OLAP).

For more information about how to set up an analysis server, see [Configure Analysis Services](configure-analysis-services.md).

## Web server

A web server hosts the websites that are required for some Microsoft Dynamics AX features. These features include Enterprise Portal for Microsoft Dynamics AX, Help server, Enterprise Search, Warehouse Mobile Devices Portal, web services on IIS, and the Retail online store.

## Other servers in the environment

The following servers are typically found in infrastructures that run Microsoft Dynamics AX. This documentation provides information about how to use Microsoft Dynamics AX together with these servers. For information about how to install and set up these servers, see the documentation for each server.

## Domain controller

A domain controller in an Active Directory network manages user logons and access to network and shared resources.

## Messaging server

A messaging server enables email messages and instant messages to be sent and received. Microsoft Dynamics AX can use email to send alerts to users. Microsoft Dynamics AX requires that the messaging server support SMTP.

  


