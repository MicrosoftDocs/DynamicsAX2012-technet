---
title: Guidance when Upgrading Reports
TOCTitle: Guidance when Upgrading Reports
ms:assetid: bf2a41b1-8a3a-41d8-a0c4-8af1e1956ae1
ms:mtpsurl: https://technet.microsoft.com/library/Gg724106(v=AX.60)
ms:contentKeyID: 35133466
author: Khairunj
ms.date: 03/12/2014
mtps_version: v=AX.60
---

# Guidance when Upgrading Reports 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Reports are not upgraded automatically during the upgrade process. Microsoft Dynamics AX provides hundreds of default, out-of-the-box reports that you can deploy and customize. To upgrade MorphX reports, we recommend that you customize a default report. The default reports run on SQL Server Reporting Services. Reporting Services is a server-based reporting platform that provides comprehensive reporting functionality for a variety of data sources.

When upgrading to Microsoft Dynamics AX 2012, existing Reporting Services reports and reports based on the MorphX reporting framework are copied to the Microsoft Dynamics AX 2012system. However, they will not be upgraded.

This topic describes additional options to determine the best approach to upgrade a MorphX report when you need to customize a default report.

## Determining the Best Upgrade Approach

For each report, there are considerations to determine the best upgrade approach. If, after you customize a default report, it does not meet your needs, the following list contains other options for upgrading a MorphX report.

  - Define a new Reporting Services report

  - Convert the report to a Reporting Services report

This section provides the steps for each of these options to understand the best approach to upgrade your MorphX reports.

## Define a New Reporting Services Report

Reporting Services is the primary reporting platform for Microsoft Dynamics AX. The following list provides the steps to define a report when using the Visual Studio tools for Microsoft Dynamics AX.

1.  [Define the data source](how-to-define-a-report-data-source.md) for the report. The Microsoft Dynamics AX data source options are DynamicsAX or DynamicsAXOLAP.

2.  [Define the report data source type](defining-report-data.md) for the report. The Microsoft Dynamics AX data source options are Query, Report Data Provider, Business Logic, or AX Enum Provider.

3.  [Define the report](creating-reports-overview.md) by using the Visual Studio tools for Microsoft Dynamics AX. In Visual Studio, you will [add a report](how-to-add-or-delete-a-report.md), create the design, [auto](how-to-create-an-auto-design-for-a-report.md) or [precision](how-to-create-a-precision-design-for-a-report.md), and [preview](how-to-preview-a-report-design.md) the report to get started.

4.  Add detail to the report. You can work with [data regions](working-with-data-regions.md), display an [image](displaying-images-in-reports.md), and add a [report or style template](using-report-layout-and-style-templates.md).

5.  Add interactive features such as the following:
    
      - [Drill down and drill up actions](how-to-add-drill-down-and-drill-up-actions.md)
    
      - [Document map](how-to-display-a-document-map.md)
    
      - [Report parameters](how-to-define-a-report-parameter.md)
    
      - [Dynamic filters](how-to-define-a-report-with-dynamic-filters.md)
    
      - [Report filters](how-to-define-a-report-filter.md)
    
      - [Link to another report](how-to-add-a-report-drill-through-action-on-a-report.md)
    
      - [Link to a URL](how-to-add-a-url-drill-through-action-on-a-report.md)
    
      - [Specify a chart axis value](how-to-specify-a-chart-axis-start-value.md)

6.  Localize the report by [using labels](how-to-use-a-label-in-a-report.md) for localizable text.

7.  [Preview the report](how-to-preview-a-report-design.md) in Visual Studio.

8.  [Deploy the report](how-to-deploy-reports-to-a-report-server.md) to the report server.

9.  View the report in Report Manager using the URL: http://\[MachineName\]/reports

10. View the report in Microsoft Dynamics AX by [creating a menu item](how-to-create-a-menu-item-for-a-report.md) for the report.

11. After you upgrade the report you must manually delete the old report. For more information, see [How to Delete a SQL Reporting Services Report](https://go.microsoft.com/fwlink/?linkid=219164)


> [!NOTE]
> <P>There is no need to reference another reporting project. You can access all model elements in the AOT without using a reference.</P>



## Convert the Report to a Reporting Services Report

To convert a report from MorphX to Reporting Services you must migrate business logic to development concepts used for Reporting Services reports. Determine which advanced Reporting Services development concepts are required to define the same reporting solution as the MorphX report.

Use the following steps to convert a MorphX report to Reporting Services.

1.  Examine the MorphX report.
    
    1.  In the AOT, expand the **Reports** node, and then expand the node for the MorphX report that you want to convert.
    
    2.  Determine the data source used for the report. This includes the relationships between tables and the fields that are used to display data for the report.
    
    3.  Apply Microsoft Dynamics AX database schema changes.
        
        Fix compilation issues in the MorphX report related to database schema changes. The following list describes some of the schema changes that affect legacy reports.
        
          - [Dimensions](prepare-financial-dimension-framework-for-upgrade.md)
        
          - Primary Key and Surrogate Foreign Key References
    
    4.  In the AOT, expand the **MenuItems** node, expand the **Output** node, and then double-click the report name with **Old** appended to it, for example, **AXSalesReportOld**.
        
        This opens the parameter dialog.
    
    5.  Enter data in the parameter dialog form and then click **OK** to print the report.

2.  Define the report data source.
    
    Determine which type of data source is appropriate for your Reporting Services report. To do this you must understand the structure of the report data source. The following table describes when to use a query or a Report Data Provider (RDP) class.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Data source</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Query based report</p></td>
    <td><p>Data for a report can be fulfilled by using a combination of table relations and table display methods.</p></td>
    </tr>
    <tr class="even">
    <td><p>RDP based report</p></td>
    <td><p>Data for a report requires custom X++ business logic.</p></td>
    </tr>
    </tbody>
    </table>
    
    Take into account items in the following list when you review the report dataset.
    
      - Source of the data contained in the report dataset.
    
      - Elements of the report that are from report business logic.
    
      - Calculated columns based on Microsoft Dynamics AX data.
    
      - Extended Data Types (EDTs) that are used to format data.
    
      - Data that does not display on the report but which is used to navigate to Microsoft Dynamics AX forms.

3.  When custom business logic is needed, [create a Report Data Provider (RDP) class](how-to-use-a-report-data-provider-class-in-a-report.md).
    
    An RDP class is the data access layer that contains the X++ custom business logic used to produce the report dataset. Refactor the existing X++ code into an RDP class and then separate the business logic from the report that renders logic.

4.  [TempDB temporary tables](https://technet.microsoft.com/library/bb314749\(v=ax.60\)) are used to store the report dataset generated by the RDP class.

5.  In the AOT, [create a temporary table](https://technet.microsoft.com/library/aa882181\(v=ax.60\)) to store the report dataset and then [define the table schema](https://technet.microsoft.com/library/aa861546\(v=ax.60\)) based on the dataset that is needed to generate the report.

6.  Consider if you should use the report execution sequence. Create a report controller class that extends the SysOperationController class for MorphX report execution. The following list describes the reasons to override the controller class.
    
      - Change the query based on input parameters.
    
      - React to form control events.
    
      - Add contextual input validation that is not part of the contract.
    
      - Select the report design based on the user input.
    
      - Modify organization or culture information.

7.  [Define a report in Visual Studio and bind it to the RDP class](walkthrough-creating-a-report-bound-to-a-report-data-provider-class-x-business-logic.md).

8.  If necessary, convert the basic design into a [precision design](how-to-create-a-precision-design-for-a-report.md) to achieve the desired report layout.

9.  Deploy the report to the Reporting Server. In Visual Studio, from the **Build** menu, click **Deploy Solution** to [Deploy the report](how-to-deploy-reports-to-a-report-server.md).

10. From the **File** menu, click **Save All** and close Visual Studio. You are prompted to add the local project to the AOT.

11. View the report in Report Manager by using the URL: http://\[MachineName\]/reports

12. View the report in Microsoft Dynamics AX by [creating a menu item](how-to-create-a-menu-item-for-a-report.md) for the report.

13. After you convert the report you must manually delete the old report. For more information, see [How to Delete a SQL Reporting Services Report](https://go.microsoft.com/fwlink/?linkid=219164)


> [!NOTE]
> <P>There is no need to reference another reporting project. You can access all model elements in the AOT without using a reference.</P>



## See also

[Report Integration and Customization Overview](report-integration-and-customization-overview.md)

[How to: Add Validation to a Data Contract Class](how-to-add-validation-to-a-data-contract-class.md)

  


