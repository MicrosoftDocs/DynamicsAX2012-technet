---
title: New, Changed, and Deprecated Features for AX 2012 overview
TOCTitle: New, Changed, and Deprecated Features for AX 2012
ms:assetid: af686153-4c0a-458e-b288-60627d5a41d0
ms:mtpsurl: https://technet.microsoft.com/library/Dn527205(v=AX.60)
ms:contentKeyID: 59623334
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install the Test Data Transfer Tool (beta)


[!INCLUDE[archive-banner](includes/archive-banner.md)]


This topic describes how to install the Microsoft Dynamics AX 2012 Test Data Transfer Tool (beta). Only advanced users should use this tool. 

You must be a database administrator or a developer who has experience using Microsoft SQL Server. You must also have permission to read from or write directly to the Microsoft Dynamics AX 2012 database that you are working with, and to execute applications directly on the computer that is hosting the database. Before you begin, your environment must include the following components:

-   An Microsoft Dynamics AX 2012 database that has been configured for your business.
-   The SQL Server client tools installed on the local computer, and on the database server that you are transferring data to, so that the SQL Server bulk copy tool (bcp) is in the command-prompt path.

During export, the tool creates three files for each table. Make sure that there is enough hard disk space for all the tables that are exported.

## Install the Test Data Transfer Tool (beta)
1.  Get the tool from the Downloadable tools section of [Microsoft Dynamics Lifecycle Services](https://go.microsoft.com/fwlink/?LinkId=228148), and extract it to a local folder.
2.  Right-click **AX2012TestDataTransferTool.msi**, and then click **Run as administrator**.
3.  In the **Setup** **Wizard**, accept the license terms, and then select the location in which to install the binaries and files for the tool. By default, the tool is installed to %Program Files%/Microsoft Dynamics AX 2012 Test Data Transfer Tool (Beta).

