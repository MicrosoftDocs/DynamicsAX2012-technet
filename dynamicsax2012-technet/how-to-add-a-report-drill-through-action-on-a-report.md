---
title: 'How to: Add a Report Drill Through Action on a Report'
TOCTitle: 'How to: Add a Report Drill Through Action on a Report'
ms:assetid: ec81f32a-df05-4e3c-bac8-5b3a2bcd8c09
ms:mtpsurl: https://technet.microsoft.com/library/Cc653599(v=AX.60)
ms:contentKeyID: 28119611
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Add a Report Drill Through Action on a Report 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A *report drill through action* lets you create links to other reports. A drillthrough report is a report that a user opens by clicking a link within another report. It lets users drill through to additional data. When defining a report drill through action, there are two reports involved: the top-level report and the drillthrough report. A report drill through action is defined on the top-level report. The drillthrough report typically displays additional information about the item that the user clicked in the top-level report. Parameters can be used to pass data from the top-level report to the drillthrough report. It is not required that you pass data to a drillthrough report.

A drillthrough report serves a different purpose than a subreport. A subreport is processed as part of the main report. For example, if a subreport that displays order detail information is added to a table cell in the detail row, the subreport is processed one time per row of the table and rendered as part of the main report. A drillthrough report is only processed and rendered when the user clicks the drillthrough link in the top-level report. For more information, see [Adding Subreports](http://go.microsoft.com/fwlink/?linkid=234243%26clcid=0x409).


> [!NOTE]
> <P>Before adding a report drill through action, both the top-level report and the drillthrough report must be created and open in Visual Studio. We recommended that you add both reports to the same modeling project and store the project in the AOT.</P>



If you plan to use parameters to pass values from the top-level report to the drillthrough report, we recommended that these parameters are defined in the drillthrough report before you define the drill through action. For more information about parameters, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md).

You can define a hierarchy of drillthrough reports. The top-level report is different at each level in a hierarchy. This allows a drillthrough report to be a top-level report for another drillthrough report in the hierarchy.

When you add a report drill through action in an auto design, you will set properties in Model Editor to link to another report. When you add a report drill through action in a precision design, you will use Visual Studio Report Designer to link to another report. The auto design report displays information about the parameters for a dataset. When you use parameters in a precision design report, you must type the name of the parameter directly. Therefore, we recommend that you create the report drill through action in an auto design report and then create a precision design from the auto design report that contains the drill through. The following procedures explain how to add a report drill through action in an auto design report and in a precision design report.

### To add a report drill through action (auto design)

1.  In Visual Studio, open the reporting project.

2.  In Model Editor, expand the node for the top-level report.

3.  Expand the node for the auto design that you want to add the report drill through action to, and then expand the node for the data region that contains the field or image that you want to use as the link the user will click.
    
    You can use a field or image located below the **Data** node, or you can use a field that has been used to define a grouping for the data region.

4.  Right-click the field or image, point to **Add**, and then click **Report Drill Through Action**.

5.  Select the node created for the report drill through action.

6.  In the **Properties** window, specify the following properties.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>The name of the report drill through action.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ReportDesign</strong></p></td>
    <td><p>The design for the drillthrough report that will display when a user clicks the linked item.</p>
    <p>Click the ellipsis (…) button. A dialog box displays in which you can select a design for a report from the current model. After you select a design, the parameters for the drillthrough report display below the node for the report drill through action.</p></td>
    </tr>
    </tbody>
    </table>
    
    If you plan to use parameters to pass data from the top-level report to the drillthrough report, continue with the following procedure. You can delete any parameters that you do not want to use from the list that appears below the node for the drill through action. For more information, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md).

### To use parameters to pass data to a drillthrough report (auto design)

1.  Select the parameter from below the drill through action that you just defined.

2.  In the **Properties** window, specify the following properties.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>The name of the parameter. The name that you specify will not change the name of the parameter in the drillthrough report.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Value</strong></p></td>
    <td><p>The expression whose value is passed to the drillthrough report. For example, to use company as a parameter, select the AX_CompanyName parameter and set the <strong>Value</strong> property to =Parameters!AX_CompanyName.Value.</p></td>
    </tr>
    </tbody>
    </table>


3.  Repeat the previous two steps for each parameter that you want to use to pass data to the drillthrough report. You can access the linked item from the report when you run the report in the Microsoft Dynamics AX client or in Enterprise Portal.
    
    Next you can modify the drillthrough report so that it uses the values that are passed through the parameters. For example, you can define a filter that will filter the data in the drillthrough report based on the values passed from the top-level report. For more information about filters, see [How to: Define a Report Filter](how-to-define-a-report-filter.md). For the complete steps to use a parameter in a report drill through action, see [Walkthrough: Creating a Drillthrough Report](walkthrough-creating-a-drillthrough-report.md).

### To add a report drill through action (precision design)

  - In Visual Studio, open the reporting project.

  - In Model Editor, expand the node for the report that you want to work with.

  - Expand the **Designs** node for the report.

  - Right-click the precision design that you want to modify, and then click **Edit Using Designer...**
    
    You can add a report drill through action to a textbox or image.

  - Select the text box or image in the report layout. In the Properties window, click the **Action** ellipses button (…).

  - Click **Go to report** and then click the **Specify a report** Expression (**fx**) button to open the Expression dialog box.

  - Specify a report for the report drill through, like ReportProjectName.ReportDesignName.

  - To pass data to the drillthrough report, use the parameters that are listed in the **Use these parameters to run the report** section. Click the **Value** Expression (**fx**) button to open the Expression dialog box. Write an expression that conforms to Visual Basic syntax for the parameter value. For example, to use company as a parameter, set the Name field to AX\_CompanyName and set the **Value** property to =Parameters\!AX\_CompanyName.Value and click **OK**.

For more information, see [How to: Add a Drillthrough Report Link (SQL Report Designer)](http://go.microsoft.com/fwlink/?linkid=106185).

## See also

[How to: Add a URL Drill Through Action on a Report](how-to-add-a-url-drill-through-action-on-a-report.md)

[Walkthrough: Creating a Drillthrough Report](walkthrough-creating-a-drillthrough-report.md)

[Adding Links to a Report](adding-links-to-a-report.md)

