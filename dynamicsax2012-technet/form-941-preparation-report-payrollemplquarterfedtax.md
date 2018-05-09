---
title: Form 941 preparation report (PayrollEmplQuarterFedTax)
TOCTitle: Form 941 preparation report (PayrollEmplQuarterFedTax)
ms:assetid: fa504738-15a7-4ce0-bae1-7098b2c22a1c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn479041(v=AX.60)
ms:contentKeyID: 59632409
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Form 941 preparation report (PayrollEmplQuarterFedTax) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Form 941 is used by employers to report payroll taxes to the IRS. The report must be filed at the end of each quarter. The **Form 941 preparation** report in Microsoft Dynamics AX provides information to help you prepare the required tax form.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



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
<td><p>The tax year for the Form 941 that you are completing.</p></td>
</tr>
<tr class="even">
<td><p><strong>Quarter</strong></p></td>
<td><p>The tax quarter for the Form 941 that you are completing.</p></td>
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
<td><p>PayrollEmplQuarterFedTax</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>Menu Items\Output\PayrollEmplQuarterFedTax</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PayrollEmplQuarterFedTax</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll</strong> &gt; <strong>Reports</strong> &gt; <strong>Tax</strong> &gt; <strong>Quarterly reports</strong> &gt; <strong>Form 941 preparation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PayrollTaxTransactionHistoryUnionQuery query

  - PayrollPayStatementLine table

  - PayrollPayStatementTaxLine table

  - PayrollPayStatement table

  - HcmWorker table

  - PrlUSTaxTransactionHistory table

  - PayrollPayStatementTaxLinesManual view

  - PayrollPayStatementTaxLinesManualGrouped view

  - PayrollTaxTransactionHistoryUnion view

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

