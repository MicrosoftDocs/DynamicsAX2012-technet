---
title: Deploying Reports
TOCTitle: Deploying Reports
ms:assetid: 2011d94c-19b5-47c1-b76f-0f7b2d93b69a
ms:mtpsurl: https://technet.microsoft.com/library/Hh297077(v=AX.60)
ms:contentKeyID: 36287622
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Deploying Reports 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can deploy reports in Visual Studio, from the AOT, or in Windows PowerShell.

## In This Section

The following list describes what occurs when a report is deployed:

  - The Report Definition Language (RDL) is uploaded to Reporting Services.

  - The business logic assemblies are copied to the Reporting Services server.

  - The referenced report and business logic assemblies are verified to be present.


> [!NOTE]
> <P>You must have administrative access rights to deploy reports to the SQL Server Reporting Services server. Your Windows domain account must be a member of the Administrators group on the server that is running Reporting Services and you must be assigned to the System Administrator role on the Report Manager website.</P>



The following topics explain how to deploy reports:

[How to: Deploy Reports to a Report Server](how-to-deploy-reports-to-a-report-server.md)

[Checklist: Install the Reporting Services extensions and deploy reports](checklist-install-the-reporting-services-extensions-and-deploy-reports.md)

[Troubleshoot Report Deployment Issues](troubleshoot-report-deployment-issues.md)

