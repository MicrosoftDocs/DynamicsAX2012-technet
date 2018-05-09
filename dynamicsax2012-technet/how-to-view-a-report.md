---
title: 'How to: View a Report'
TOCTitle: 'How to: View a Report'
ms:assetid: c86c58a9-d93b-4ee6-a6ec-13fe1864ad97
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg724116(v=AX.60)
ms:contentKeyID: 35133476
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: View a Report 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to view a report in Microsoft Dynamics AX, Microsoft Visual Studio, and Report Manager.

## Viewing a Report in Microsoft Dynamics AX

You can view the report in Microsoft Dynamics AX after the report has been deployed to the report server. For more information, see [How to: Deploy Reports to a Report Server](how-to-deploy-reports-to-a-report-server.md). To view the report in Microsoft Dynamics AX, one of the following conditions must have been met:

1.  The report has been added to a menu item. For more information, see [How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md).

2.  The report is displayed in a role center. To do this, [determine which Role Center page you want to modify](https://technet.microsoft.com/en-us/library/cc558235\(v=ax.60\)). Then, [add the report to that page](https://technet.microsoft.com/en-us/library/cc553120\(v=ax.60\)).

### To view a report in Microsoft Dynamics AX

1.  Deploy the report and create a menu item for the report.

2.  In the Microsoft Dynamics AX client, navigate to the menu item and double-click the report. The report is displayed.
    
    \--or--
    
    In the AOT, right-click the menu item and then click **Open**. The report is displayed.

## Viewing a Report in Visual Studio Preview

The Microsoft Dynamics AX report development environment is fully integrated into Microsoft Visual Studio. As you create or update the design of your report, you can preview your changes in the preview window.

### To view a report in Visual Studio Preview

1.  In Visual Studio, from the **View** menu, click **Application Explorer**.

2.  Expand the **SSRS Reports** node, find the report to work on, right-click the report and then click **Edit**. This opens the report in Model Editor.

3.  Expand the **Designs** node for the report.

4.  Right-click the design that you want to preview, and then click **Preview**.
    
    The **Preview** window has two tabs: a **Parameters** tab and a **Report** tab. The **Parameters** tab lists any parameters that have been defined for the report. For more information about parameters, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md). Click the **Report** tab to display the report. Errors are displayed in the **Error List** window.
    
    For information about how to use Model Editor to modify the report, see [Creating Reports Overview](creating-reports-overview.md) and [Defining Report Data](defining-report-data.md).

## Viewing a Report in Report Manager

Reports run on the Reporting Services platform. Report Manager is a component of SQL Server Reporting Services. It is a Web application tool that is used to access and manage the contents of a report server database.

### To view a report in Report Manager

1.  In Solution Explorer, right-click the reporting project that contains the reports that you want to deploy, and then click **Deploy**.

2.  View the report in Report Manager using the URL: http://\[ServerName\]:\[PortNumber\]/Reports.
    

    > [!NOTE]
    > <P>If you install SQL Server 2008 R2 Reporting Services on a 64-bit platform, the default port for Reporting Services URLs is port 80.</P>



## See also

[How to: Access a Report for Edit](how-to-access-a-report-for-edit.md)

[Working with Reporting Projects](working-with-reporting-projects.md)

