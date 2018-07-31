---
title: Questionnaire report (KMKnowledgeCollector)
TOCTitle: Questionnaire report (KMKnowledgeCollector)
ms:assetid: 39d07822-c202-4b32-b7f5-36b8e90ccf0a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa575031(v=AX.60)
ms:contentKeyID: 39508872
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.KMKnowledgeCollector
---

# Questionnaire report (KMKnowledgeCollector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view questionnaire answers or planned answer sessions. Depending on the menu item that you use to access this report, the information on the report will vary as follows:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Menu item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Answers</strong></p></td>
<td><p>The report displays an overview of all answers selected on completed questionnaires.</p>
<p>You can use the options in the <strong>Print</strong> field group to include the following:</p>
<ul>
<li><p><strong>Result groups</strong> – Information about results at the result group level for each questionnaire.</p></li>
<li><p><strong>Answer</strong> – Both the question and the answer text.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Planned answer session</strong></p></td>
<td><p>The report displays an overview of all planned answer sessions.</p></td>
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
<td><p>KMKnowledgeCollector</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\KMKnowledgeCollector</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>KMKnowledgeCollectorPlanning</p>
<p>KMKnowledgeCollectorResult</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Home</strong> &gt; <strong>Reports</strong> &gt; <strong>Questionnaires</strong> &gt; <strong>Plans</strong> &gt; <strong>Planned answer session</strong>.</p>
<p>Click <strong>Home</strong> &gt; <strong>Reports</strong> &gt; <strong>Questionnaires</strong> &gt; <strong>Answers</strong> &gt; <strong>Answers</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DirPartyTable table

  - KMQuestionResultGroup table

  - KMVirtualNetworkAnswerGroup table

  - KMVirtualNetworkAnswerLine table

  - KMVirtualNetworkAnswerTable table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


