---
title: Vendors by category report (ProcCategoryVendor)
TOCTitle: Vendors by category report (ProcCategoryVendor)
ms:assetid: c400e993-33dc-4786-8f99-0da49b6d57bd
ms:mtpsurl: https://technet.microsoft.com/library/Hh433518(v=AX.60)
ms:contentKeyID: 36941300
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ProcCategoryVendor
- vendors by category report
---

# Vendors by category report (ProcCategoryVendor) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Vendors by category** report to view the vendors that are authorized to supply products for a selected procurement category in a legal entity. The report displays the vendor account, vendor name, and vendor status for the legal entity and procurement category that you select.

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
<td><p>Select a legal entity. Only vendors who are authorized to do business with the selected legal entity are displayed in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Category</strong></p></td>
<td><p>Select a procurement category. Only vendors who are authorized to do business in the selected category are displayed in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Printer</strong></p></td>
<td><p>The printer that is currently selected. To select a different printer, click <strong>Destinations ...</strong>.</p>
<p>This field is blank if <strong>Screen</strong> is selected in the <strong>Print destination</strong> field.</p></td>
</tr>
<tr class="even">
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
<td><p>ProcCategoryVendor</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProcCategoryVendor</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProcCategoryVendor</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Categories</strong> &gt; <strong>Vendors by category</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProcCategoryTmpVendor


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the ProcCategoryVendorsDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md)

  


