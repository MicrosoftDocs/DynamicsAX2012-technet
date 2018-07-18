---
title: Resource assignments report (PSAResourceAssignments)
TOCTitle: Resource assignments report (PSAResourceAssignments)
ms:assetid: d898a75a-679f-4222-b102-fa365a3d98a1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh334502(v=AX.60)
ms:contentKeyID: 36676491
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reports
- project add-in
- resource assignments
- SSRS_Reports.Reports.PSAResourceAssignments
- worker assignments
- resource assignments reports
- worker assignment conflicts
---

# Resource assignments report (PSAResourceAssignments) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Resource assignments** report to view worker assignments based on criteria that you select. For example, you can select project types and worker commitment types in a date range. You can sort the information on the report by project or project contract. You can also select criteria to include only conflicts in worker assignments on the report.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Include project types</strong></p></td>
<td><p>Select the check boxes for the project types to include on the report. You must select at least one project type.</p>
<ul>
<li><p><strong>Time and material</strong></p></li>
<li><p><strong>Fixed-price</strong></p></li>
<li><p><strong>Investment</strong></p></li>
<li><p><strong>Internal and cost</strong></p></li>
<li><p><strong>Time</strong></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Include commitment types</strong></p></td>
<td><p>Select the check boxes for the types of worker commitments to include on the report. You must select at least one commitment type.</p>
<ul>
<li><p><strong>Hard</strong></p></li>
<li><p><strong>Soft</strong></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong></p></td>
<td><p>Enter the starting date of the date range for which to view worker assignments.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the ending date of the date range.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Conflict only</strong></p></td>
<td><p>Select this check box to view only conflicts in worker assignments.</p></td>
</tr>
<tr class="even">
<td><p><strong>SSRS report view</strong></p></td>
<td><p>In the <strong>Layout – rows</strong> section, select how you want to organize the information on the report.</p>
<ul>
<li><p><strong>Project</strong></p></li>
<li><p><strong>Project contract</strong></p></li>
<li><p><strong>Project manager</strong></p></li>
<li><p><strong>Employee</strong></p></li>
<li><p><strong>Supervisor</strong></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Show descriptions</strong></p></td>
<td><p>In the <strong>Layout – columns</strong> section, select the columns to include on the report.</p>
<ul>
<li><p><strong>Descriptions only</strong></p></li>
<li><p><strong>IDs only</strong></p></li>
<li><p><strong>IDs and descriptions</strong></p></li>
</ul></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>PSAResourceAssignments</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\PSAResourceAssignments</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>Resource assignments</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Resource scheduling</strong> &gt; <strong>Resource assignments</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PSAResourceAssignmentsDP.PROCESSREPORT

  - PSARESOURCEASSIGNMENTSTMP table
    

    > [!NOTE]
    > <P>To determine where the data in the temp table comes from, view the cross-references for the RFQSendDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


