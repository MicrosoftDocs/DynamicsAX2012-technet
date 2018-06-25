---
title: Form W-2 report (PayrollW2Report)
TOCTitle: Form W-2 report (PayrollW2Report)
ms:assetid: 6d339292-d251-432f-a6fe-47c212814e95
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ713635(v=AX.60)
ms:contentKeyID: 49643132
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- SSRS_Reports.Reports.PayrollW2Report
- Form W2
- form W-2
- W2
- W-2
---

# Form W-2 report (PayrollW2Report) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this report to create Form W-2s to issue to workers.


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
<td><p>Enter the tax year to create Form W-2s for.</p></td>
</tr>
<tr class="even">
<td><p><strong>Worker</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the workers to create Form W-2s for.</p></td>
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
<td><p>PayrollW2Report</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS\Reports\PayrollW2Report</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PayrollW2Report</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll</strong> &gt; <strong>Reports</strong> &gt; <strong>Tax</strong> &gt; <strong>Annual reports</strong> &gt; <strong>Form W-2</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LogisticsPostalAddress

  - DirPerson

  - HcmPersonIdentificationNumber

  - HcmEmployment

  - HCMWorker

  - PayrollTaxCode

  - PRLUSTaxTransactionHistory

  - PayrollTaxCodeDetail

  - PayrollPayStatement

  - PayrollPayStatementLine

  - PayrollPayStatementBenefitLine

  - PayrollPayStatementTaxLine

  - PayrollPayStatementEarningLine

  - PayrollFormW2BoxReportingAdjustment

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Form W-2 reconciliation report (PayrollW2Reconciliation)](form-w-2-reconciliation-report-payrollw2reconciliation.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

