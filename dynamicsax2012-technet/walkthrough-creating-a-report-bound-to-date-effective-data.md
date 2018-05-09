---
title: 'Walkthrough: Creating a Report Bound to Date Effective Data'
TOCTitle: 'Walkthrough: Creating a Report Bound to Date Effective Data'
ms:assetid: 7221183a-0386-4e0d-b1f9-66e12fc8b71e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731939(v=AX.60)
ms:contentKeyID: 35132873
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Walkthrough: Creating a Report Bound to Date Effective Data 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In this walkthrough, you will create a report that is bound to date effective data. Date effective data is valid time state data for which changes must be tracked at different points in time. On a table in the AOT, you can set the ValidTimeStateFieldType property to make it a valid time state table. Setting this property causes the system to automatically add the ValidFrom and ValidTo columns which track a date range for each row. Reports that are bound to valid time state data will provide a parameter for the date range or a specific date on the parameter form when you run the report. For this example you will create a report that lists employees that were on leave during a date range or on a specific date.


> [!NOTE]
> <P>The data that displays in your report will vary depending upon the sample data that is available to you.</P>



This walkthrough illustrates the following tasks:

  - Creating a reporting project

  - Adding a dataset

  - Designing and Previewing a report

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data
    

    > [!NOTE]
    > <P>This walkthrough uses the HcmEmploymentLeave table. To view data in the report, this table must be populated with data.</P>



  - Microsoft Visual Studio 2010

  - Microsoft Visual Studio tools for Microsoft Dynamics AX

## Creating a Reporting Project

In this section, you will create a reporting project in Microsoft Visual Studio. In this walkthrough, you will use the Report Model template.

### To create a reporting project

1.  Open Microsoft Visual Studio.

2.  On the **File** menu, point to **New**, and then click **Project**. The **New Project** dialog box displays.

3.  In the **Installed Templates** pane, click **Microsoft Dynamics AX**. In the **Templates** pane, click **Report Model**.

4.  In the **Name** box, type SampleLeaveReport. In the **Location** box, type a location.

5.  Click **OK**.

## Adding a Dataset

Now that you have created a reporting project, you are ready to add a dataset to the report design that will bind the report to specific data. In this example, you will bind the report to a query. You will use the HCMEmployeeLeave query because it has the HCMEmployment table as a data source, and that table supports valid time state. Valid time state is supported when the ValidTimeStateFieldType property for the table is set to **Date** or **UtcDateTime**. The following procedure explains how to add a dataset to a report that is bound to a Microsoft Dynamics AX query.

### To add a dataset

1.  In Solution Explorer, right-click the **SampleLeaveReport** project, point to **Add**, and then click **Report**.

2.  In Model Editor, right-click the new report and then click **Rename**. Type LeaveReport as the name.

3.  Right-click the **Datasets** node and then click **Add Dataset**.

4.  Select the node for the dataset.

5.  In the **Properties** window, specify the following values.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Data Source</strong></p></td>
    <td><p><strong>Dynamics AX</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Source Type</strong></p></td>
    <td><p><strong>Query</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default Layout</strong></p></td>
    <td><p><strong>Table</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>EmployeesOnLeave</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (…). A dialog box displays that you can use to select a query that is defined in the AOT and identify the fields that you want to use.</p>
    <ol>
    <li><p>Select the <strong>HcmEmployeeLeave</strong> query and then click <strong>Next</strong>.</p></li>
    <li><p>Under the <strong>HcmWorker</strong> node, expand the <strong>All Fields</strong> node and select <strong>PersonnelNumber</strong> and <strong>Person [DirPartyTable.3.AutoIdentification]</strong>.</p></li>
    <li><p>Expand the <strong>HcmEmployment</strong> node. Expand the <strong>HcmEmploymentLeave</strong> node, expand the <strong>All Fields</strong> node, and then select <strong>StartDate</strong> and <strong>EndDate</strong>.</p></li>
    <li><p>Expand the <strong>HcmLeaveType</strong> node, expand the <strong>All Fields</strong> node, and then select <strong>description</strong>.</p></li>
    <li><p>Click <strong>OK</strong>.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


## Design and Preview a Report

Next, you will add an auto design report. You will specify layout and style templates for the report, and then preview the report in Visual Studio. A layout template is used to define the placement of the headers and footers in a report. Style templates are used to adjust the style settings for the data regions that are displayed in a report, such as the size of the text, borders, and background color. Layout and style templates are useful for defining reusable layout and style settings. A template can be applied to many reports to maintain consistent appearance for all of the reports.

The following procedures explain how to add an auto design report, how to apply a layout template and a style template, and how to preview the report.

### To add an auto design report

  - In Model Editor, select the **EmployeesOnLeave** node and drag it onto the **Designs** node. An auto design named **AutoDesign1** is created for the report.

### To apply layout and style templates

1.  In Model Editor, select the **AutoDesign1** node.

2.  In the **Properties** window, set the **Layout Template** property to **ReportLayoutStyleTemplate**. Also, type Employees on leave for the **Title** property.

3.  In Model Editor, expand the **AutoDesign1** node, and then select the node for the EmployeesOnLeaveTable data region.

4.  In the **Properties** window, set the **Style Template** property to **TableStyleTemplate**.

### To preview the report

1.  In Model Editor, select the **AutoDesign1** node.

2.  From the Model Editor toolbar, click **Preview**.

3.  In the preview window, click the **Select** button. Enter a date range during which some employees were on leave. Click **OK**.

4.  In the preview window, select the report tab to view the report. The report displays the workers that were on leave for the date or dates you entered.

5.  Close the **Preview** window.

To us the report in Microsoft Dynamics AX, you would add it to the AOT by right-clicking the **SampleLeaveReport** project and then clicking **Add SampleLeaveReport to AOT**. For information about how to integrate new reports into Microsoft Dynamics AX, see [Walkthrough: Integrating New Reports into Microsoft Dynamics AX](walkthrough-integrating-new-reports-into-microsoft-dynamics-ax.md).

## See also

[Creating Reports Overview](creating-reports-overview.md)

