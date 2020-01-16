---
title: Answers per person report (KMAnswersByPerson)
TOCTitle: Answers per person report (KMAnswersByPerson)
ms:assetid: fdb84d46-cb5a-49d3-adec-0b56d6350838
ms:mtpsurl: https://technet.microsoft.com/library/Hh538468(v=AX.60)
ms:contentKeyID: 39508899
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.KMAnswersByPerson
---

# Answers per person report (KMAnswersByPerson) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Answers per person** report to view an overview of questionnaire results for each respondent.

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
<td><p><strong>Result groups</strong></p></td>
<td><p>Select this check box to print a summary for each result group for each questionnaire. The summary includes the number of points and percentage rating for the result group.</p></td>
</tr>
<tr class="even">
<td><p><strong>Answer</strong></p></td>
<td><p>Select this check box to print both the question and answer text, along with the number of points for each answer. Clear this check box to print only the status of the answer session.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p>Select a worker, contact, or applicant whose responses you want to print.</p></td>
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
<td><p>KMAnswersByPerson</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\KMAnswersByPerson</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>KMKnowledgeCollectorResultByVirNetId</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Home</strong> &gt; <strong>Reports</strong> &gt; <strong>Questionnaires</strong> &gt; <strong>Answers</strong> &gt; <strong>Answers per person</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DirPartyTable table

  - DirPerson table

  - KMQuestionResultGroup table

  - KMVirtualNetworkAnswerGroup table

  - KMVirtualNetworkAnswerLine table

  - KMVirtualNetworkAnswerTable table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


