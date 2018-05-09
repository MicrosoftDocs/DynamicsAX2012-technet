---
title: Ledger posting setup report (ProjListProjPosting)
TOCTitle: Ledger posting setup report (ProjListProjPosting)
ms:assetid: 53e037c9-3839-45e4-9b0b-7a68762b0beb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa582885(v=AX.60)
ms:contentKeyID: 36941255
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProjListProjPosting
---

# Ledger posting setup report (ProjListProjPosting) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view ledger postings by project category, and the setup criteria for posting to ledger accounts by category relation. You can select whether to include direct, indirect, and unspecified project category relations on the report. For more information about ledger posting setup by category relation, see [Ledger posting setup (form)](https://technet.microsoft.com/en-us/library/aa599270\(v=ax.60\)).

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
<td><p><strong>Direct</strong></p></td>
<td><p>Select whether to include ledger postings that are specifically assigned to a project.</p></td>
</tr>
<tr class="even">
<td><p><strong>Indirect</strong></p></td>
<td><p>Select whether to include ledger postings that are indirectly assigned to a project.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Missing</strong></p></td>
<td><p>Select whether to include ledger postings to a project that are not specifically assigned to a project category.</p></td>
</tr>
<tr class="even">
<td><p><strong>Cost price</strong></p></td>
<td><p>Select the cost transaction postings that you want the report to display.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales price</strong></p></td>
<td><p>Select the sales transaction postings that you want the report to display.</p></td>
</tr>
<tr class="even">
<td><p><strong>Project ID</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Ledger posting setup</strong> form, select a project to include on the report. To add more than one project ID, click <strong>Add</strong>. If you do not select a project ID, all projects are displayed on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Category</strong></p></td>
<td><p>Click <strong>Select</strong>. In the <strong>Ledger posting setup</strong> form, select the project category to include on the report. To add more than one category, click <strong>Add</strong>. If you do not select a project category, all categories are displayed on the report.</p></td>
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
<td><p>ProjListProjPosting</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProjListProjPosting</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProjListProjPosting</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Setup</strong> &gt; <strong>Ledger posting setup</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProjListProjPostingDP.processReport

  - ProjCategory table

  - ProjListProjPostingTmp table

  - ProjTable


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the ProjListProjPostingDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

