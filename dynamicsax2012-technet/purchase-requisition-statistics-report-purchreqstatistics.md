---
title: Purchase requisition statistics report (PurchReqStatistics)
TOCTitle: Purchase requisition statistics report (PurchReqStatistics)
ms:assetid: 9d9518c5-e754-447e-8709-21fc4df4f891
ms:mtpsurl: https://technet.microsoft.com/library/Hh335162(v=AX.60)
ms:contentKeyID: 36687374
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.PurchReqStatistics
---

# Purchase requisition statistics report (PurchReqStatistics) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Purchase requisition statistics** report to view a list of purchase requisitions. You can select parameters to filter the report to include only the purchase requisitions that you want to view. The report includes the header and line details for the purchase requisitions. It also includes the summarized total amounts for each purchase requisition.


> [!NOTE]
> <P>The <STRONG>Purchase requisition statistics</STRONG> report does not include any purchase requisitions that have a status of <STRONG>Draft</STRONG>, even if you select that status as a filter on the <STRONG>Purchase requisition statistics</STRONG> form.</P>



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
<td><p><strong>All</strong></p></td>
<td><p>Select this check box to include all purchase requisitions in the report. If you clear this check box, you can select which purchase requisitions to include in the report.</p>
<ul>
<li><p><strong>Requested for me</strong> – Purchase requisitions that include items that were requested for you.</p></li>
<li><p><strong>Assigned to me</strong> – Purchase requisitions that are assigned to you to complete or approve.</p></li>
<li><p><strong>Prepared by me</strong> – Purchase requisitions that you entered for yourself or on behalf of other users.</p></li>
<li><p><strong>My direct reports</strong> – Purchase requisitions that include items that were requested by users who report to you directly.</p></li>
<li><p><strong>All my reports</strong> – Purchase requisitions that include items that were requested by users who report to you, either directly or indirectly.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Enter the earliest date for the purchase requisitions that you want to include in the report. This is the date on which the purchase requisitions were submitted for review.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the latest date for the purchase requisitions that you want to include in the report. This is the date on which the purchase requisitions were submitted for review.</p></td>
</tr>
<tr class="even">
<td><p><strong>Status</strong></p></td>
<td><p>Select the status for the purchase requisitions that you want to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Grouping</strong></p></td>
<td><p>Select how to group the information in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Details</strong></p></td>
<td><p>Select this check box to include details, such as item number, item name, and quantity, for all purchase requisition lines. If you clear this check box, only the purchase requisition names and totals are included in the report.</p></td>
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
<td><p>PurchReqStatistics</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\PurchReqStatistics</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PurchReqStatisticsSSRS</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Purchase requisition statistics</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PurchReqStatisticsTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the PurchReqStatisticsDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md)

  


