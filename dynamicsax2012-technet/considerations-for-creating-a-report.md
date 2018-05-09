---
title: Considerations for Creating a Report
TOCTitle: Considerations for Creating a Report
ms:assetid: 5b402bc4-2d57-41f9-84dd-bb73c818ba75
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731927(v=AX.60)
ms:contentKeyID: 35132856
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Considerations for Creating a Report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

How the report accesses data, the controls for passing parameters to the report, the layout and design of the report, and where the report will be used are all things to consider when you create reports using the Microsoft Visual Studio tools for Microsoft Dynamics AX.

## Data Access

You must consider how complex the data access is for the report. The following table describes various levels of complexity when you access data:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Data access complexity</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Simple</p></td>
<td><p>A report dataset identifies data that is displayed in a report. A dataset lets you retrieve data by using a query created in the AOT, a data method, or a report data provider class to access X++ logic.</p></td>
</tr>
<tr class="even">
<td><p>Complex</p></td>
<td><p>When a dataset does not provide the complexity needs of your report, you can use the default <a href="https://technet.microsoft.com/en-us/library/gg940296(v=ax.60)">SrsReportRunController</a> class. A controller class runs the report by creating the user interface (UI), calling SQL Server Reporting Services, and pre-processing the parameters for the report. The following list describes scenarios that require that you extend the <a href="https://technet.microsoft.com/en-us/library/gg940296(v=ax.60)">SrsReportRunController</a> class to create a custom controller for the report.</p>
<ul>
<li><p>Report requires input data to be pre-processed.</p></li>
<li><p>Report requires input data to be manipulated or modified.</p></li>
<li><p>Multiple reports should be run from the same dialog box.</p></li>
<li><p>Report requires that it be run from a form.</p></li>
</ul></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>Reports that use a controller class cannot be used for Enterprise Portal.</P>



## Parameters

Parameters are used to specify the data to use in a report, connect related reports together, and control report presentation. You must determine which type of parameter is best suited for your report. For a list that describes how parameters are created, how that affects a report, and any special considerations, see [Parameters Overview](parameters-overview.md).

## Choosing auto design or precision design based on report layout

You must consider whether the report is a simple list of data or if it requires precise formatting. The following table describes various degrees of control when you define the layout of your report:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Layout level of control</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Simple</p></td>
<td><p>Drag a dataset onto the <strong>Designs</strong> node to create an auto design for the report. The layout is generated based on the data for the report. For more information, see <a href="how-to-create-an-auto-design-for-a-report.md">How to: Create an Auto Design for a Report</a>.</p></td>
</tr>
<tr class="even">
<td><p>Complex</p></td>
<td><p>Add a precision design for a report that requires a very precise layout, such as an invoice or a bank check. SQL Report Designer is used to create and edit a precision design for a report. Before you use SQL Report Designer to create a report design, the report must be available in the model, and datasets must be added to the report so that the data is available in SQL Report Designer. For more information, see <a href="how-to-create-a-precision-design-for-a-report.md">How to: Create a Precision Design for a Report</a>.</p></td>
</tr>
</tbody>
</table>


## Where the Report will be Used

You must consider whether the report will be used in the Microsoft Dynamics AX client, in Enterprise Portal, or in both locations. The following list describes considerations when the report will be accessed from Enterprise Portal:

  - Reports that are accessed from Enterprise Portal cannot use SysQuery parameters.

  - Reports that are accessed from Enterprise Portal cannot use the Controller class.

  - Consider the page on which the report will be displayed. If the report is included on a page with limited space, the existing design for the report may not be usable. Consider adding a separate design for the report that can be used specifically when the report is displayed in Enterprise Portal.

  - Consider providing default values for the report parameters whenever possible. This makes it much easier for the user to add the report to an Enterprise Portal page, because the report will run without requiring parameters to be set. The user can adjust the parameters as necessary after the report has been added to the page.

## See also

[Planning and architecture of reporting](planning-and-architecture-of-reporting.md)

[Report Programming Guide](report-programming-guide.md)

[Reports](https://technet.microsoft.com/en-us/library/cc601396\(v=ax.60\))

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

