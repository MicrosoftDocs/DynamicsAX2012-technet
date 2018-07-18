---
title: Sales tax report incl. corrections report (TaxReportInclAdjustment)
TOCTitle: Sales tax report incl. corrections report (TaxReportInclAdjustment)
ms:assetid: f50cd9ca-f501-497b-978d-06f6c3abf9e1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh781086(v=AX.60)
ms:contentKeyID: 43894494
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxReportInclAdjustment
---

# Sales tax report incl. corrections report (TaxReportInclAdjustment) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays sales tax payments, including corrections.


> [!NOTE]
> <P>To print this report, the <STRONG>Include corrections</STRONG> check box must be selected in the <STRONG>General ledger parameters</STRONG> form.</P>



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
<td><p><strong>Include details</strong></p></td>
<td><p>Select this check box to list the transactions that are included in the balances that are shown on the report.</p></td>
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
<td><p>TaxReportInclAdjustment</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxReportInclAdjustment</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReportInclAdjustment</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Sales tax payments</strong> &gt; <strong>Sales tax payments</strong>. Select appropriate values in the <strong>Settlement period</strong>, <strong>From date</strong>, and <strong>Transaction date</strong> fields.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxReportInclAdjustmentTmp table


> [!NOTE]
> <P>To find out where the data in the temp tables comes from, view the cross-references for the TaxReportInclAdjustmentDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


