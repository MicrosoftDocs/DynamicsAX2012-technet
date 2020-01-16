---
title: Pay statements report (PayrollPayStatementReport)
TOCTitle: Pay statements report (PayrollPayStatementReport)
ms:assetid: 803456e6-b2ee-4784-87c1-c0205f060e78
ms:mtpsurl: https://technet.microsoft.com/library/JJ713637(v=AX.60)
ms:contentKeyID: 49643131
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- SSRS_Reports.Reports.PayrollPayStatementReport
- pay statement
---

# Pay statements report (PayrollPayStatementReport) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you generate the payroll payment journal, you can use this report to print pay statements to issue to workers. You can also use this report to reprint pay statements for workers.

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
<td><p><strong>Pay cycle</strong></p>
<p><strong>Pay period</strong></p></td>
<td><p>Select the pay cycle and pay period to print pay statements for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Disbursement format</strong></p></td>
<td><p>Select whether to print pay statements for check payments, electronic payments, or all payments.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Worker</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the workers to print pay statements for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment number</strong></p></td>
<td><p>To print specific pay statements, click <strong>Select</strong> to specify the pay statement numbers.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Batch number</strong></p></td>
<td><p>To print only pay statements created by specific pay statement generation runs, click <strong>Select</strong>, and then specify the batch numbers of the pay statements to print.</p></td>
</tr>
<tr class="even">
<td><p><strong>Pay statement status</strong></p></td>
<td><p>By default, pay statements are printed only after the worker payment has been issued. To specify a different pay statement status, click <strong>Select</strong> and modify the query.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Pay statement reversed</strong></p></td>
<td><p>By default, pay statements are not printed for pay statements that have been reversed. To print pay statements that have been reversed, click <strong>Select</strong> and modify the query.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment date</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the payment dates to print pay statements for.</p></td>
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
<td><p>PayrollPayStatementReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS\Reports\PayrollPayStatementReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PayrollPayStatementReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll</strong> &gt; <strong>Reports</strong> &gt; <strong>Pay statements</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PayrollPayStatement

  - PayrollPayStatementReportTmp

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


