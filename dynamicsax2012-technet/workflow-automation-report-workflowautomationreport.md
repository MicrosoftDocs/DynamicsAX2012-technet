---
title: Workflow automation report (WorkflowAutomationReport)
TOCTitle: Workflow automation report (WorkflowAutomationReport)
ms:assetid: 7aa8a52f-d67c-478c-9235-5633a80673cc
ms:mtpsurl: https://technet.microsoft.com/library/Hh334493(v=AX.60)
ms:contentKeyID: 36676480
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.WorkflowAutomationReport
- Menu_Items.Output.WorkflowAutomationReport
---

# Workflow automation report (WorkflowAutomationReport) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Workflow automation** report shows the percentage of workflow elements that were completed automatically and the percentage of workflow elements that were completed manually by users for workflows of a specific type. This report will help you identify which workflows require more human interaction so that you can possibly automate more steps of the workflow.

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
<td><p><strong>Maindata_AssociationType</strong></p></td>
<td><p>Select one of the following options:</p>
<ul>
<li><p><strong>Company</strong> – Filter the report to display workflows that are associated with a specific company account.</p></li>
<li><p><strong>Global</strong> – Filter the report to display workflows that are associated with your whole organization.</p></li>
<li><p><strong>Other</strong> – Filter the report to display workflows that are associated with a specific organization, such as a legal entity.</p></li>
<li><p><strong>All</strong> – Do not filter the report based on workflow association.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Maindata_EndDate</strong></p></td>
<td><p>Select an end date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maindata_Module</strong></p></td>
<td><p>Select a module.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maindata_StartDate</strong></p></td>
<td><p>Select a start date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maindata_Templatename</strong></p></td>
<td><p>Select a workflow type.</p></td>
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
<td><p>WorkflowAutomationReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\WorkflowAutomationReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>WorkflowAutomationReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Organization administration</strong> &gt; <strong>Reports</strong> &gt; <strong>Workflow</strong> &gt; <strong>Workflow automation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - Workflow cube

  - BIDATEDIM\_DATE table

  - WORKFLOWCUBEELEMENTLOOKUP table

  - WORKFLOWCUBELOOKUP table

  - WORKFLOWCUBETRANSACTION table

  - WORKFLOWCUBETRANSACTION\_DIM table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


