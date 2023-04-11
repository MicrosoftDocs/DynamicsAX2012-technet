---
title: 'Deprecated: Unsupported platforms for Microsoft Dynamics AX 2012'
TOCTitle: Unsupported platforms for Microsoft Dynamics AX 2012
ms:assetid: e14258a1-fc96-424f-af18-92d82fadfeab
ms:mtpsurl: https://technet.microsoft.com/library/Dn527252(v=AX.60)
ms:contentKeyID: 59623380
author: tonyafehr
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# Deprecated: Unsupported platforms for Microsoft Dynamics AX 2012 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX 2009 supports several operating systems and tools. Microsoft Dynamics AX 2012 does not support some operating systems and tools that were previously supported.


> [!NOTE]
> <P>For AX 2012, no server components can be installed on 32-bit server operating systems.</P>



## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reason for deprecation</p></td>
<td><p>Microsoft Dynamics AX cannot run correctly when these operating systems or tools are used.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. AX 2012 supports several newer operating systems and tools.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>This change might affect application upgrade, depending on the features that are currently used in your environment.</p></td>
</tr>
</tbody>
</table>


## Database

The database server is the computer where the Microsoft SQL Server software is installed and Microsoft Dynamics AX data is stored. In AX 2012, the database server hosts the AX 2012 database, the SharePoint databases, and the databases that are used for reporting and analytics. AX 2012 does not support the following platforms:

  - Microsoft SQL Server 2005

  - Microsoft SQL Server 2008 (x86)

## Server operating system

AX 2012 no longer supports use of the following operating systems to host server or database components:

  - Windows Server 2003

  - Windows Server 2008 R2 (x86)

## Client operating system

AX 2012 no longer supports use of the following operating system to host the Microsoft Dynamics AX client:

  - Windows XP

## Client software

AX 2012 does not support the following software for the Microsoft Dynamics AX client:

  - Internet Explorer 6

  - Windows Internet Explorer 7.0

  - Firefox 2.0

  - Firefox 3.0

  - Apple Safari (all versions)

## Retail: Head-office database server

The head-office database server is the computer where the SQL Server software is installed and Microsoft Dynamics AX data is stored. Microsoft Dynamics AX 2012 R2 does not support the following operating system:

  - Windows Server 2008 (x68 or x64)

## Retail: Head-office and store communications servers

The head-office and store communications servers are the computers where the SQL Server software is installed, and where Microsoft Dynamics AX data is exchanged between the head office and the store. AX 2012 R2 does not support the following operating systems:

  - Windows Server 2003

  - Windows Server 2008 (x68 or x64)

  - Windows Vista (x68 or x64)

  - Windows XP SP3 (x86)

## Retail: Store database computer

The store database computer is the computer where the store data is installed and Microsoft Dynamics AX data is stored. AX 2012 R2 does not support the following operating systems:

  - Windows Vista (x68 or x64)

  - Windows XP SP3 (x86)

## Retail: Point of sale register (with or without data)

The point of sale (POS) register is the computer where individual POS transactions occur. AX 2012 R2 does not support the following operating systems:

  - Windows Vista (x68 or x64)

  - Windows XP SP3 (x86)

  - Windows Embedded POS Ready 2009

## Enterprise Portal for Microsoft Dynamics AX server

The Enterprise Portal server, which is also known as the Dynamics AX Web Server in Microsoft Dynamics AX 4.0, provides intranet, extranet, and Internet access to the Microsoft Dynamics AX system through a web browser. Enterprise Portal can be hosted on all server operating systems that are supported. However, AX 2012 does not support use of the following components together with Enterprise Portal:

  - Windows SharePoint Services 3.0

  - Microsoft Office SharePoint Server 2007

## Synchronization proxy and synchronization service for Microsoft Project Server

The synchronization proxy coordinates data updates between a Microsoft Project database and the synchronization service. The synchronization service is a Microsoft Dynamics AX server component. The synchronization proxy and the synchronization service do not support the following component:

  - Microsoft Project Server 2007

## Microsoft Visual Studio Tools

The Visual Studio Tools for Microsoft Dynamics AX combine all the developer tools, such as Enterprise Portal development tools, reporting tools, and modeling tools. The Visual Studio Tools let developers customize various Microsoft Dynamics AX artifacts by using Visual Studio. In earlier versions of Microsoft Dynamics AX, these tools were split into Enterprise Portal development tools and reporting tools. The Visual Studio Tools do not support the following component:

  - Microsoft Visual Studio 2008

## See also

[Microsoft Dynamics AX 2012 System Requirements](https://www.microsoft.com/en-us/download/details.aspx?id=11094)

  


