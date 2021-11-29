---
title: Report Integration and Customization Overview
TOCTitle: Report Integration and Customization Overview
ms:assetid: 0ea16ac7-1d4d-4af4-b9e0-078bd992f403
ms:mtpsurl: https://technet.microsoft.com/library/Cc519490(v=AX.60)
ms:contentKeyID: 28119307
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Report Integration and Customization Overview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Reports that are created with the reporting tools in Microsoft Visual Studio can be integrated into Microsoft Dynamics AX and then later customized. This topic provides a description of key concepts involved in integrating and customizing reports.

## Integrating and Customizing Reports

Reporting projects can be customized, upgraded, and patched using the built-in layering support in Microsoft Dynamics AX. You can add Visual Studio reporting projects to the AOT. Reports are stored in the AOT when they are added to a Microsoft Dynamics AX reporting project.

In Microsoft Visual Studio, when you right-click a reporting project in Solution Explorer, the **Add \<ReportName\> to AOT** option displays on the context menu. When you select this option, a node for the reporting project displays below the **Visual Studio Projects** \> **Dynamics AX Model Projects** node in the AOT and in Application Explorer. You can also access the single report in the AOT or the Application Explorer under the **SSRS Reports** \> **Reports** node. For more information, see [How to: Add Reports to Microsoft Dynamics AX](how-to-add-reports-to-microsoft-dynamics-ax.md).

Once a report project is added to the AOT, when you save the changes, the changes are saved at the metadata level and updated in the AOT.

## Displaying Reports in Microsoft Dynamics AX

After you have added reports to a Microsoft Dynamics AX reporting project, you can create output menu items for the reports so that they can be displayed within the application. Reports can display from menus and forms in the Microsoft Dynamics AX client and in Enterprise Portal Web parts. For more information about creating a menu item, see [How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md). For information about reports and Enterprise Portal, see [How to: Add SSRS Reports to Pages](https://technet.microsoft.com/library/cc553120\(v=ax.60\)). You can define menu items for the reports as soon as they are added to a reporting project. The reports do not need to be deployed to the report server until the reports need to be viewed.

For an end-to-end example of how to display a report on a menu in Microsoft Dynamics AX, see [Walkthrough: Integrating New Reports into Microsoft Dynamics AX](walkthrough-integrating-new-reports-into-microsoft-dynamics-ax.md).

## See also

[How to: Add Reports to Microsoft Dynamics AX](how-to-add-reports-to-microsoft-dynamics-ax.md)

[How to: Deploy Reports to a Report Server](how-to-deploy-reports-to-a-report-server.md)

[How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md)

[How to: Customize a Report](how-to-customize-a-report.md)

[Walkthrough: Integrating New Reports into Microsoft Dynamics AX](walkthrough-integrating-new-reports-into-microsoft-dynamics-ax.md)

[Walkthrough: Customizing Existing Microsoft Dynamics AX Reports](walkthrough-customizing-existing-microsoft-dynamics-ax-reports.md)

