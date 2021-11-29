---
title: MorphX Reporting Tools Overview
TOCTitle: MorphX Reporting Tools Overview
ms:assetid: 0a0b6d19-aa25-49e8-8889-0786633579f1
ms:mtpsurl: https://technet.microsoft.com/library/Cc967358(v=AX.60)
ms:contentKeyID: 35290294
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# MorphX Reporting Tools Overview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create reports in Microsoft Dynamics AX by using Microsoft Dynamics AX reporting tools for Visual Studio or by using MorphX reporting tools. This section deals with creating reports using MorphX reporting tools.

## AOT reports

You can create a new report under the **Reports** node of the AOT.

### Create a report

To create a new report, right-click the **Reports** node in the AOT and then click **New Report**. For more information, see [Walkthrough: Creating Reports in the AOT (MorphX Reporting Tools)](walkthrough-creating-reports-in-the-aot-morphx-reporting-tools.md).

### Create a query

After you create a report, you can specify the information that the report contains by creating a query. A Data Source node is nested under the report node, and the Query node is nested below that Data Source node. For more information, see [How to: Create Queries by using the AOT](https://technet.microsoft.com/library/bb314753\(v=ax.60\)), [How to: Create Queries by Using X++](https://technet.microsoft.com/library/aa638454\(v=ax.60\)), and [Walkthrough: Creating Reports in the AOT (MorphX Reporting Tools)](walkthrough-creating-reports-in-the-aot-morphx-reporting-tools.md).

### Create a report design

After you create the query for the report, you can specify the layout of the data in the report by generating a report design. For more information, see [Report Designs (MorphX Reporting Tools)](report-designs-morphx-reporting-tools.md), [How to: Specify a Report Design by Using X++ (MorphX Reporting Tools)](how-to-specify-a-report-design-by-using-x-morphx-reporting-tools.md), and [Walkthrough: Creating Reports in the AOT (MorphX Reporting Tools)](walkthrough-creating-reports-in-the-aot-morphx-reporting-tools.md).

### Import or compile a MorphX report

When you import or compile a MorphX report, the permissions that are associated with the objects in the report are not automatically created. If you expand the permissions node of the report, permissions will be shown, but they will not be persisted by default. To persist the permissions, you must expand the permissions node and explicitly save the report.

## See also

[MorphX Reporting Tools](morphx-reporting-tools.md)

