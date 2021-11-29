---
title: Prerequisite skills and knowledge
TOCTitle: Prerequisite skills and knowledge
ms:assetid: c83bd14c-79d9-4b8e-9338-acf45932076c
ms:mtpsurl: https://technet.microsoft.com/library/Dd362074(v=AX.60)
ms:contentKeyID: 35132871
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Prerequisite skills and knowledge 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX is built on several other Microsoft products and technologies. To implement the Microsoft Dynamics AX program in a manner that takes full advantage of this technology platform, you must have advanced information technology skills and knowledge.

## Prerequisites for system administrators

We recommend that system administrators who are preparing to deploy Microsoft Dynamics AX be familiar with general industry practices that pertain to the reliability, scalability, availability, performance optimization, security, and monitoring of a network infrastructure and applications. The base components of Microsoft Dynamics AX include Application Object Server (AOS), the database server, the model store, which was previously known as the application file server, and the Microsoft Dynamics AX client. To install the base components, you must understand the following Microsoft technologies:

  - The Windows Server operating system that is used to deploy the Microsoft Dynamics AX server components

  - The Windows client operating system that is used to deploy the Microsoft Dynamics AX Windows client

  - The Microsoft .NET Framework

  - Windows Server Terminal Services, if this technology is required

  - Advanced network management in an environment that uses Active Directory Domain Services.

The following table describes the skills and knowledge that are required to deploy specific components of a Microsoft Dynamics AX implementation.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Microsoft Dynamics AX component</p></th>
<th><p>Required skills and knowledge</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Database server</p></td>
<td><ul>
<li><p>Microsoft SQL Server® administration</p></li>
<li><p>The planning of relational database infrastructures and sizing of the database infrastructure</p></li>
<li><p>Performance optimization and monitoring of a database server</p></li>
<li><p>Database backup and recovery</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Reporting and analytics</p></td>
<td><ul>
<li><p>Microsoft SQL Server Analysis Services</p></li>
<li><p>Microsoft SQL Server Reporting Services</p></li>
<li><p>Internet Information Services (IIS), websites, virtual directories, application pools, and administration of web services</p></li>
<li><p>The Microsoft .NET Framework version 4 and ASP.NET</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Enterprise Portal for Microsoft Dynamics AX</p></td>
<td><ul>
<li><p>IIS administration</p></li>
<li><p>Microsoft® SharePoint® Foundation 2010 administration or Microsoft® SharePoint® Server 2010 administration, depending on the production version that is used</p></li>
<li><p>The .NET Framework version 4 and ASP.NET</p></li>
<li><p>The creation and management of websites, web services, virtual directories, and application pools</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Services and Application Integration Framework (AIF)</p></td>
<td><ul>
<li><p>IIS administration, if web services are deployed</p></li>
<li><p>Microsoft® BizTalk® Server, if you must integrate BizTalk Server with Microsoft Dynamics AX</p></li>
<li><p>The .NET Framework, especially Windows Communication Foundation (WCF)</p></li>
<li><p>Integration concepts, such as enterprise application integration (EAI), business-to-business (B2B), and synchronous and asynchronous transports</p></li>
<li><p>The creation and management of websites, web services, virtual directories, and application pools, if you deploy web services</p></li>
<li><p>The .NET Framework version 4 and ASP.NET</p></li>
<li><p>Message Queuing, which is also known as MSMQ, if this technology is used</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Workflow</p></td>
<td><ul>
<li><p>The .NET Framework, especially Windows Workflow Foundation</p></li>
<li><p>IIS administration, which is required during an upgrade from the previous release</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Microsoft Project Server integration functionality</p></td>
<td><ul>
<li><p>The deployment and management of Windows services</p></li>
<li><p>Message Queuing</p></li>
<li><p>Project Server administration</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Getting started with associated technologies](getting-started-with-associated-technologies.md)

  


