---
title: Creating Reports Overview
TOCTitle: Creating Reports Overview
ms:assetid: 784dd771-693d-4c02-89b0-d4cc04c516e0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc557922(v=AX.60)
ms:contentKeyID: 28119383
ms.date: 03/12/2014
mtps_version: v=AX.60
f1_keywords:
- DynamicsReportingOverview
- Microsoft.Dynamics.Framework.Design.UI.DrillThroughReport
---

# Creating Reports Overview 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This section explains how to create reports using the Microsoft Visual Studio tools for Microsoft Dynamics AX.

[Considerations for Creating a Report](considerations-for-creating-a-report.md)

[Report Programming Guide](report-programming-guide.md)

[How to: Add or Delete a Report](how-to-add-or-delete-a-report.md)

[How to: Create an Auto Design for a Report](how-to-create-an-auto-design-for-a-report.md)

[How to: Create a Precision Design for a Report](how-to-create-a-precision-design-for-a-report.md)

[How to: Preview a Report Design](how-to-preview-a-report-design.md)

[How to: Change the Default Number of Records that Display in the Report Preview](how-to-change-the-default-number-of-records-that-display-in-the-report-preview.md)

Microsoft Dynamics AX provides a model-based approach to create reports by providing project templates and modeling tools that are incorporated into the Microsoft Visual Studio development environment. The reporting features provided by Microsoft Dynamics AX are based on a tight integration with SQL Server Reporting Services.

Using the Microsoft Visual Studio tools provided by Microsoft Dynamics AX has the following benefits:

  - You can create reports quickly using the auto design reporting feature. This feature automatically creates a report design based on the report data.

  - You can use SQL Report Designer for reports that require a very precise design. SQL Report Designer can be started directly from your reporting project.

  - You can create a consistent appearance and behavior for your reports using style templates. One style template can be applied to many reports. Style templates let you separate the style settings from the actual report definition.

  - You can preview reports at design time from the Microsoft Visual Studio development environment.

Reports created by using the Microsoft Visual Studio tools for Microsoft Dynamics AX can be integrated into Microsoft Dynamics AX. They can be displayed as menu items on menus and forms in the Microsoft Dynamics AX client and in Enterprise Portal Web parts. For more information, see [Report Integration and Customization Overview](report-integration-and-customization-overview.md).

## Creating Reports

The first step in creating your reports is to create a reporting project in Microsoft Visual Studio by selecting the Report Model project template. After you have created a reporting project, you can define a report in the model that is provided. You can add, remove, and modify report items using the context menus that appear when you right-click the nodes in the model. For example, you can right-click the **Images** node for a report, and then click **Add Image** to add an embedded image to a report. You can also move or create new elements in a model by using drag-and-drop functionality. For example, when you drag a report dataset onto the **Designs** node, an auto design is created for the report. For more information about the elements in a model, see [Model Editor Overview](https://technet.microsoft.com/en-us/library/cc643142\(v=ax.60\)). The following illustration shows an example of a report in a model.

![Model file](images/Cc557922.ModelFile(AX.60).gif "Model file")

Microsoft Dynamics AX provides two tools, Model Editor and Application Explorer, to edit and view models. If you double-click a report in Solution Explorer, the report opens in Model Editor. For more information about the modeling tools, see [Model Editor Overview](https://technet.microsoft.com/en-us/library/cc643142\(v=ax.60\)) and [Application Explorer](https://technet.microsoft.com/en-us/library/cc637855\(v=ax.60\)).

## Defining Report Data

When you create a report, you must define the data that will display in the report. To do this, you must first identify the data sources that will be used. A data source represents a source of data for one or more reports. A report can display data from more than one data source. You can use an AOS data source called *Dynamics AX*, which connects to the Microsoft Dynamics AX application database. When you use this data source, you can use queries or report data provider classes that have been defined in the Application Object Tree (AOT) within Microsoft Dynamics AX or you can write data methods in the reporting project to retrieve data for your reports. If you have want to use an enum field as a parameter on the report, you will create a second dataset and define the parameter using the **AX Enum Provider** data source type. To connect to Microsoft Dynamics AX OLAP data, use the data source called *DynamicsAXOLAP*. If you want to connect to a legacy system or an external database, you must define a new data source and specify connection information. There are two provider types that can be used when you define a new data source: SQL and OLAP.

After you define data sources, you must define one or more datasets. A dataset identifies data that is displayed in a report. When you define a dataset, you must specify the data source and the means used to retrieve the data, such as a query, data method, or stored procedure. Data sources and datasets are defined in the model alongside your reports. For more information about data sources and datasets, see [Report Data Overview](report-data-overview.md).

## Report Layout and Design

A report design represents a particular layout of a report. A report can have multiple designs. The following table provides a description of the types of report designs that you can create.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Auto design</p></td>
<td><p>An auto design is a report design that is automatically generated based on the report data. It is created by using Model Editor. The auto design functionality provides an efficient way to create the most common types of reports, such as a customer list or a list of inventory items.</p></td>
</tr>
<tr class="even">
<td><p>Precision design</p></td>
<td><p>A precision design is a report design that is created by using SQL Report Designer. Precision designs are typically used when a report requires a very precise layout, such as invoices or bank checks. SQL Report Designer lets you manually drag-and-drop fields onto a report and put them exactly where they should be.</p></td>
</tr>
</tbody>
</table>


## Auto Design Layout

An auto design follows a particular layout. It has a header, a body that contains one or more data regions, and a footer, as shown in the following illustration.

![Auto design report layout](images/Cc557922.AutoDesignReportlayout(AX.60).gif "Auto design report layout")

You control the content that is displayed in each area in an auto design. For example, you can include a report title and the date in the header and display the page number in the footer. Or, you may not want to display anything in the header and footer.

The data regions that display in an auto design depend on the datasets that you created when you defined the data for the report. When you define a dataset, you can specify the type of data region that will be used to render the data whenever the dataset is used in an auto design. Data can be displayed in table, list, matrix, or chart formats. For more information about data regions, see [Report Data Region Overview](report-data-region-overview.md). One way to create an auto design is to drag a dataset onto the node for the auto design in the model.

## Precision Design Layout

A precision design is free-form where you define the layout using SQL Report Designer. Therefore, the format of a precision design can vary depending on the layout that is required.

## Adding Interactive Report Features

There are several features that you can add to your reports to let users interact with and control the data that they see in a report. For example, you can expand and collapse data on the report using the drill down and drill up features. You can display a document map in a report that lets users easily move to different areas in the report by clicking an item in the document map. A document map is useful when a report displays lots of data. You can add data groupings and drill-down features that let users expand or collapse areas in a report. You can create drillthrough reports and add URL drill through actions. You can also create parameters and filters that let users select or filter the data that they see in a report. For more information, see [Adding Interactive Features to Reports](adding-interactive-features-to-reports.md).

## Localizing Reports

Use AX labels in your reports that can be dynamically resolved at runtime. Only one report definition per report is needed. For more information, see [Localizing Reports](localizing-reports.md).

## Modifying the Appearance of a Report

Style templates are used to modify the appearance of a report. Style templates contain properties that control the visual elements of a report, such as the size of the text or the background color of a data region. There are several predefined style templates that you can use to keep your reports consistent with existing reports in Microsoft Dynamics AX. You can also create your own style templates and apply them to a set of reports. Style templates ensure consistency and uniformity throughout your reports. For more information, see [Using Report Layout and Style Templates](using-report-layout-and-style-templates.md).

You can display images in reports. Images can be embedded directly in a report, or they can be referenced from a database table. Embedded images are typically used when the set of images to display is constant, as in key performance indicator (KPI) reports. Images from a database table are typically used when you want to provide images for a set of items listed in a report, which is common in product listings. For more information, see [Report Images Overview](report-images-overview.md).

## See also

[Reporting in Microsoft Dynamics AX](reporting-in-microsoft-dynamics-ax.md)

[Reports](https://technet.microsoft.com/en-us/library/cc601396\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

