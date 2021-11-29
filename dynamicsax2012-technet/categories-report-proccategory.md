---
title: Categories report (ProcCategory)
TOCTitle: Categories report (ProcCategory)
ms:assetid: 508775c1-4c0f-4495-9269-aacf9fa55b05
ms:mtpsurl: https://technet.microsoft.com/library/Hh433492(v=AX.60)
ms:contentKeyID: 36941253
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProcCategory
---

# Categories report (ProcCategory) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Categories** report displays the name, friendly name, description, and status of the procurement categories that are defined for the legal entities in your organization.

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
<td><p><strong>Legal entity</strong></p></td>
<td><p>Select one or more legal entities. Only the procurement categories that are defined for those legal entities are displayed. This list also contains the statuses for the procurement categories. Select <strong>All</strong> to view a list of all procurement categories that are defined for your organization.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Enter the earliest date for the procurement categories that you want to include in the report. This is the date on which the procurement categories were created.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the latest date for the procurement categories that you want to include in the report. This is the date on which the procurement categories were created.</p></td>
</tr>
<tr class="even">
<td><p><strong>Printer</strong></p></td>
<td><p>The printer that is currently selected. To select a different printer, click <strong>Destinations ...</strong>.</p>
<p>This field is blank if <strong>Screen</strong> is selected in the <strong>Print destination</strong> field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Print destination</strong></p></td>
<td><p>The destination where the report will be produced. Click <strong>Destinations ...</strong> to change the destination for the report.</p></td>
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
<td><p>ProcCategory</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProcCategory</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProcCategorySRS</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Categories</strong> &gt; <strong>Categories</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProcCategoryTmpAllowedCategory table

  - ProcCategoryDP.processReport


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the ProcCategoryDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md)

  


