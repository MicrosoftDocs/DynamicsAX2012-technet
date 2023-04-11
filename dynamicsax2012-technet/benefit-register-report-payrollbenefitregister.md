---
title: Benefit register report (PayrollBenefitRegister)
TOCTitle: Benefit register report (PayrollBenefitRegister)
ms:assetid: ba12a94a-0403-44f6-8665-ed49e5c90e5b
ms:mtpsurl: https://technet.microsoft.com/library/JJ713641(v=AX.60)
ms:contentKeyID: 49643135
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- report
- SSRS_Reports.Reports.PayrollBenefitRegister
- benefit
---

# Benefit register report (PayrollBenefitRegister) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this report each time you run payroll to validate the benefit amounts that were calculated during payroll processing.


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
<td><p><strong>Print court case number</strong></p></td>
<td><p>Mandatory deductions that are handled as benefits, such as garnishments, may have a court case number assigned to them. Select this check box to print any court case numbers on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Print earning basis detail</strong></p></td>
<td><p>Select this check box to show the earnings details of the benefits on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print in summary or detail</strong></p></td>
<td><p>Select <strong>Detail</strong> to show the individual transactions for each benefit on the report, or <strong>Summary</strong> to omit the transactions from the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Pay statement number</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the pay statement numbers to filter the report by. The report will include only benefits that were included on the specified pay statements.</p></td>
</tr>
<tr class="even">
<td><p><strong>Batch number</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the batch numbers to filter the report by. A batch number is assigned to each pay statement generation run. The report will include only benefits that were included on pay statements in the specified batches.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payment date</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the payment dates to filter the report by. The report will include only benefits that were included on pay statements with the specified payment dates.</p></td>
</tr>
<tr class="even">
<td><p><strong>Benefit</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the benefits to filter the report by. The report will include only the specified benefits.</p></td>
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
<td><p>PayrollBenefitRegister</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS\Reports\PayrollBenefitRegister</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PayrollBenefitRegister</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll</strong> &gt; <strong>Reports</strong> &gt; <strong>Benefit register</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DirPartyTable

  - HcmBenefit

  - HcmBenefitOption

  - HcmBenefitPlan

  - HCMWorker

  - PayrollBenefitRegisterTmp

  - PayrollPayStatement

  - PayrollPayStatementBenefitLine

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


