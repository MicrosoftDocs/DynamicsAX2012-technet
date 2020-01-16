---
title: State quarterly wage and tax preparation report (PayrollStateWageTaxPrepReport)
TOCTitle: State quarterly wage and tax preparation report (PayrollStateWageTaxPrepReport)
ms:assetid: 8f597826-49c4-4930-b6ff-d61f263a44de
ms:mtpsurl: https://technet.microsoft.com/library/Dn479040(v=AX.60)
ms:contentKeyID: 59632408
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# State quarterly wage and tax preparation report (PayrollStateWageTaxPrepReport) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **State quarterly wage and tax preparation** report provides information to help you prepare your quarterly wage and tax forms. These forms are used to report all wages that you have paid to employees and to calculate state unemployment taxes.


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
<td><p>The tax year that you are completing the state wage and tax form for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Quarter</strong></p></td>
<td><p>The tax quarter that you are completing the state wage and tax form for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>State</strong></p></td>
<td><p>The state that you are completing the wage and tax form for.</p></td>
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
<td><p>PayrollStateWageTaxPrepReport</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\PayrollStateWageTaxPrepReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PayrollStateWageTaxPrepReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll</strong> &gt; <strong>Reports</strong> &gt; <strong>Tax</strong> &gt; <strong>Quarterly reports</strong> &gt; <strong>State quarterly wage and tax preparation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PrlUSTaxTransactionHistoryGrouped view

  - HcmWorker table

  - DirPerson table

  - HcmPersonIdentificationNumber table

  - HcmPersonPrivateDetails table

  - PayrollTaxCode table

  - PayrollPayStatement table

  - PayrollPayPeriod table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


