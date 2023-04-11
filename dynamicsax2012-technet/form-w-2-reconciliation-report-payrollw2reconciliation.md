---
title: Form W-2 reconciliation report (PayrollW2Reconciliation)
TOCTitle: Form W-2 reconciliation report (PayrollW2Reconciliation)
ms:assetid: 73691cd0-d5ee-4871-abdb-d1ac2b9e20d2
ms:mtpsurl: https://technet.microsoft.com/library/JJ713636(v=AX.60)
ms:contentKeyID: 49643134
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- reconcile
- SSRS_Reports.Reports.PayrollW2Reconciliation
- Form W-2
- Form W2
- W2
- W-2
---

# Form W-2 reconciliation report (PayrollW2Reconciliation) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this report to balance Form W-2s and to run validation before you issue Form W-2s to workers.


> [!NOTE]
> <P>This topic describes functionality that is available only if Payroll for Microsoft Dynamics AX 2012 is installed.</P>



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
<td><p><strong>Tax year</strong></p></td>
<td><p>Enter the tax year to reconcile Form W-2s for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print social security number</strong></p></td>
<td><p>Select this check box to print the workers’ Social Security Numbers on the report.</p>
<p>We recommend that you avoid printing Social Security Numbers whenever possible.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Personnel number</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the worker personnel numbers to filter the report by.</p></td>
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
<td><p>PayrollW2Reconciliation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS\Reports\PayrollW2Reconciliation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PayrollW2Reconciliation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll</strong> &gt; <strong>Reports</strong> &gt; <strong>Tax</strong> &gt; <strong>Annual reports</strong> &gt; <strong>Form W-2 reconciliation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DirPartyTable

  - DirPersonName

  - HCMWorker

  - PayrollTaxCode

  - PayrollW2ReconciliationTmp

  - PRLUSTaxTransactionHistory

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Form W-2 report (PayrollW2Report)](form-w-2-report-payrollw2report.md)

  


