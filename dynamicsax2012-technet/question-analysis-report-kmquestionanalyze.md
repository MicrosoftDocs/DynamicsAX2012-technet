---
title: Question analysis report (KMQuestionAnalyze)
TOCTitle: Question analysis report (KMQuestionAnalyze)
ms:assetid: 318d6f80-7ec9-422e-8bf9-151c71282da1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa501288(v=AX.60)
ms:contentKeyID: 39508870
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.KMQuestionAnalyze
---

# Question analysis report (KMQuestionAnalyze) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print information related to questions that have been answered on questionnaires. Results are sorted by questionnaire.

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
<td><p>KMQuestionAnalyze</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\KMQuestionAnalyze</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>KMQuestionAnalyze</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Home</strong> &gt; <strong>Reports</strong> &gt; <strong>Questionnaires</strong> &gt; <strong>Designs</strong> &gt; <strong>Question analysis</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - KMCollection table

  - KMCollectionQuestion table

  - KMQuestion table

  - KMQuestionAnalyzeTmp table


> [!NOTE]
> <P>To find out where the data in the temp tables comes from, view the cross-references for the KMQuestionAnalyzeDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

