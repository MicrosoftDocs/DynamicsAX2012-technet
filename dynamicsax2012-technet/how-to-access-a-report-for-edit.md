---
title: 'How to: Access a Report for Edit'
TOCTitle: 'How to: Access a Report for Edit'
ms:assetid: 1c4fa46f-60bb-43b6-a1e5-6a9d6d714ec8
ms:mtpsurl: https://technet.microsoft.com/library/Ee873247(v=AX.60)
ms:contentKeyID: 28119315
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Access a Report for Edit 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to access reports to edit from Microsoft Dynamics AX and Microsoft Visual Studio. This includes the default reports that were provided with Microsoft Dynamics AX and reports that you define.

## Determining a Report Name

If you want to know the name of a report that you see in the Microsoft Dynamics AX client, the menu item indicates the report name. The following procedure describes how to determine the report name.

### To determine a report name

1.  In the AOT or in Application Explorer, expand the **Menus** node and find the menu that contains the report. For example, click **Menus** \> **InventoryAndWarehouseManagement** \> **Reports** \> **BaseData** \> **Quantity setup** to see the properties for the **Quantity setup** menu.

2.  In the Properties window, the **MenuItemName** property indicates the menu item. The menu item for **Quantity setup** is **InventTableQuantity**.

3.  In the AOT or in Application Explorer, click **Menu Items** \> **Output** and then find the menu item name that contains the report. For example, find the **InventTableQuantity** menu item.
    
    The **Object** property indicates the report name. The report that is displayed for **Quantity setup** is **InventTableQuantity**.

## Accessing a Report Project for Edit

The naming convention for the reporting project that contains the report is \<ReportName\>Report. For example, **InventTableQuantityReport**. For a list of the reporting projects and the reports that they contain, see [List of Reporting Projects](list-of-reporting-projects.md).


> [!NOTE]
> <P>You should open the report for edit at the Visual Studio project level. The project solution will contain any necessary dependencies for the report to build. For example, report drill-throughs require both the source and target report to be loaded in the solution to build successfully.</P>



The following procedures describe how to use Application Explorer and the AOT to access a report for edit in a project.

### To access a report project for edit from Application Explorer

1.  In Visual Studio, from the **View** menu, click **Application Explorer**.

2.  In Application Explorer, expand the node for **Visual Studio Projects**, and then expand the node for **Dynamics AX Model Projects**.

3.  Find the project to work on, right-click the project and then click **Edit**. This opens the project in Visual Studio.

4.  In the Solution Explorer, find the report to work on, double-click the report. This opens the report to edit in Model Editor.

### To access a report project for edit from the AOT

1.  In the AOT, expand the node for **Visual Studio Projects**, and then expand the node for **Dynamics AX Model Projects**.

2.  Find the project to work on, right-click the project and then click **Edit**. This opens the project in Visual Studio.

3.  In the Solution Explorer, find the report to work on, double-click the report. This opens the report to edit in Model Editor.

## Accessing a Report for Edit from Application Explorer

The following procedure describes how to use Application Explorer to access a single report for edit.

### To access a report for edit from Application Explorer

1.  In Visual Studio, from the **View** menu, click **Application Explorer**.

2.  Expand the **SSRS Reports** node, find the report to work on, right-click the report and then click **Edit**. This opens the report in Model Editor in the current project.

## Previewing a Report

You can preview a report in Model Editor after you have it open for edit. The following procedure describes how to preview a report in Model Editor.

### To preview a report in Model Editor

1.  In Model Editor, expand the **Designs** node for the report.

2.  Right-click the design that you want to preview, and then click **Preview**.
    
    The **Preview** window has two tabs: a **Parameters** tab and a **Report** tab. The **Parameters** tab lists any parameters that have been defined for the report. For more information about parameters, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md). The **Report** tab displays the report. Any errors that are encountered are displayed in the **Error List** window.
    
    For information about how to use Model Editor to edit the report, see [Creating Reports Overview](creating-reports-overview.md) and [Defining Report Data](defining-report-data.md).

## See also

[Install business intelligence components](install-business-intelligence-components.md)

[Creating Reports Overview](creating-reports-overview.md)

[How to: View a Report](how-to-view-a-report.md)

[Working with Reporting Projects](working-with-reporting-projects.md)

[Defining Report Data](defining-report-data.md)

[Creating Reports Overview](creating-reports-overview.md)

