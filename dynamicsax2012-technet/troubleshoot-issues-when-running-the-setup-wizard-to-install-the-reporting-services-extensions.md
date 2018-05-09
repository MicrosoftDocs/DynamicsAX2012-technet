---
title: Troubleshoot issues when running the Setup wizard to install the Reporting Services extensions
TOCTitle: Troubleshoot issues when running the Setup wizard to install the Reporting Services extensions
ms:assetid: df0437d7-d50e-4acf-9354-e6c8f68af661
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh496434(v=AX.60)
ms:contentKeyID: 37072016
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Troubleshoot issues when running the Setup wizard to install the Reporting Services extensions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information that can help you troubleshoot issues that you may encounter when you use the Microsoft Dynamics AX Setup wizard to install the Microsoft SQL Server Reporting Services extensions.

## Setup log files

If you receive an error when you install the Reporting Services extensions, review the log files that are created by the Setup wizard. By default, the log files are saved in the following location: \\Program Files\\Microsoft Dynamics AX\\60\\Setup Logs\\\[Date\].

## Error: The operation failed with error code 1055

The Setup wizard cannot install the Reporting Services extensions if the Reporting Services service is not running. In this scenario, you may see the following error in a Setup log file:

*The operation failed with error code 1055.*

To resolve this issue, you may have to use the following procedure.

1.  Verify that the Reporting Services service is running in the Services management console (**Start** \> **Administrative Tools** \> **Services**).

2.  Wait a few minutes and then try to run the Setup wizard again.

## Error: The report server cannot open a connection to the report server database

The Setup wizard cannot install the Reporting Services extensions if it cannot connect to the Reporting Services database. In this scenario, you may see the following error in a Setup log file:

*The report server cannot open a connection to the report server database. A connection to the database is required for all requests and processing.*

To resolve this issue, you may have to use the following procedure.

1.  Verify that the Reporting Services service is running in the Services management console (**Start** \> **Administrative Tools** \> **Services**).

2.  Verify that you can connect to the Reporting Services database by using SQL Server Management Studio (**Start** \> **All Programs** \> **Microsoft SQL Server 2008** \> **SQL Server Management Studio**).

3.  Verify that the Reporting Services Configuration Manager is closed.

4.  Wait a few minutes and then try to run the Setup wizard again.

## Error: Reporting Services Extension was not configured

The Setup wizard cannot connect the Reporting Services instance to the specified Microsoft Dynamics AX Application Object Server (AOS) instance when:

  - Reporting Services is running in SharePoint integrated mode.

  - The Reporting Services instance and the AOS instance exist in different domains.

When the above conditions are true, the following error is displayed in the DynamicsSetupLog.txt file:

*Reporting Services Extension was not configured. An unknown issue occurred. Please contact your administrator.*

To resolve this issue, create a record in the **Report servers** form. For more information about how to use this form, see [Report servers (form)](https://technet.microsoft.com/en-us/library/aa548504\(v=ax.60\)).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

