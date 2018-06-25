---
title: 'How to: Add or Delete a Report'
TOCTitle: 'How to: Add or Delete a Report'
ms:assetid: acffb262-5973-41ef-bb90-5f63072d4699
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc616953(v=AX.60)
ms:contentKeyID: 28119559
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.ReportDefinition
---

# How to: Add or Delete a Report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to add a Microsoft Dynamics AX report in Visual Studio.

SQL Server Reporting Services is the primary reporting platform for Microsoft Dynamics AX. Reporting Services is a server-based reporting platform that includes a complete set of tools to create, manage, and deliver reports, and APIs that enable you to integrate or extend data and report processing in custom applications. Reporting Services tools work within the Microsoft Visual Studio environment and are fully integrated with SQL Server tools and components.

In a Visual Studio [reporting project](how-to-create-a-reporting-project.md) for Microsoft Dynamics AX, you can define a report in a report model. A report consists of a collection of items, such as datasets, parameters, images, and report designs. A model can contain more than one report.

### To add a report

  - In Solution Explorer, right-click the reporting project that you want to add a report to, point to **Add**, and then click **Report**. The report model displays in Model Editor, and the node for the report appears expanded in Model Editor.
    

    > [!WARNING]
    > <P>A report must have at least one <A href="how-to-define-a-report-dataset.md">dataset</A> and at least one design. <A href="how-to-create-an-auto-design-for-a-report.md">Auto design</A> and <A href="how-to-create-a-precision-design-for-a-report.md">precision design</A> reports are supported. If not, you will get warnings when you build the reporting project.</P>



The next steps are to define the elements that make up the report. The following list provides links to topics that describe how to define the report elements using the Visual Studio tools for Microsoft Dynamics AX.

1.  Add detail to the report. You can work with [data regions](working-with-data-regions.md), display an [image](displaying-images-in-reports.md), and add a [report or style template](using-report-layout-and-style-templates.md).

2.  Add interactive features like the following:
    
      - [Drill down and drill up actions](how-to-add-drill-down-and-drill-up-actions.md)
    
      - [Document map](how-to-display-a-document-map.md)
    
      - [Report parameters](working-with-parameters.md)
    
      - [Dynamic filters](how-to-define-a-report-with-dynamic-filters.md)
    
      - [Report filters](how-to-define-a-report-filter.md)
    
      - [Link to another report](how-to-add-a-report-drill-through-action-on-a-report.md)
    
      - [Link to a URL or a form](how-to-add-a-url-drill-through-action-on-a-report.md)
    
      - [Specify a chart axis value](how-to-specify-a-chart-axis-start-value.md)

3.  Localize the report by [using labels](how-to-use-a-label-in-a-report.md) for localizable text.

4.  [Deploy the report](how-to-deploy-reports-to-a-report-server.md) to the report server.

5.  View the report in Report Manager using the URL: http://\[MachineName\]/reports

6.  View the report in Microsoft Dynamics AX by [creating a menu item](how-to-create-a-menu-item-for-a-report.md) for the report.

### To delete a report

  - In Solution Explorer or Model Editor, right-click the report that you want to delete, and then click **Delete**.

## See also

[How to: Add an Existing Report to a Reporting Project](how-to-add-an-existing-report-to-a-reporting-project.md)

[How to: Define a Report Dataset](how-to-define-a-report-dataset.md)

[How to: Create an Auto Design for a Report](how-to-create-an-auto-design-for-a-report.md)

[How to: Create a Precision Design for a Report](how-to-create-a-precision-design-for-a-report.md)

[Walkthrough: Creating an Auto Design Report](walkthrough-creating-an-auto-design-report.md)

[Walkthrough: Referencing a Report Parameter from Multiple Datasets in a Precision Design Report](walkthrough-referencing-a-report-parameter-from-multiple-datasets-in-a-precision-design-report.md)

