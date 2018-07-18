---
title: Worker payment register report (PayrollWorkerPaymentRegister)
TOCTitle: Worker payment register report (PayrollWorkerPaymentRegister)
ms:assetid: 17ccfa7d-fae4-4498-8a88-07beb758abce
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ713632(v=AX.60)
ms:contentKeyID: 49643128
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- SSRS_Reports.Reports.PayrollWorkerPaymentRegister
---

# Worker payment register report (PayrollWorkerPaymentRegister) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To comply with auditing best practices, use this payroll report each pay period to validate data and to sign off on pay runs.


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
<td><p><strong>Pay cycle</strong></p></td>
<td><p>Select the pay cycle to generate the report for.</p></td>
</tr>
<tr class="even">
<td><p><strong>From pay period</strong></p>
<p><strong>To pay period</strong></p></td>
<td><p>Select the first and last pay period in the range of pay periods to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Print social security number</strong></p></td>
<td><p>Select this check box to print the workers’ Social Security Numbers on the report.</p>
<p>We recommend that you avoid printing Social Security Numbers whenever possible.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment run type</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the payment run types to filter the report by. The report will include only payments that were created from pay statements with the specified payment run type.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Batch number</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the batch numbers to filter the report by. A batch number is assigned to each pay statement generation run. The report will include only payments that created from pay statements in the specified batches.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment date</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the payment dates to filter the report by. The report will include only payments that were created from pay statements with the specified payment dates.</p></td>
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
<td><p>PayrollWorkerPaymentRegister</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS\Reports\PayrollWorkerPaymentRegister</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PayrollWorkerPaymentRegister</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll</strong> &gt; <strong>Reports</strong> &gt; <strong>Worker payment register</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DirPartyTable

  - HCMWorker

  - PayrollPayStatement

  - PayrollWorkerPaymentRegisterTmp

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


