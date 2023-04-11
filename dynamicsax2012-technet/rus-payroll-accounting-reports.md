---
title: (RUS) Payroll accounting reports
TOCTitle: (RUS) Payroll accounting reports
ms:assetid: 095e5f9d-2d90-40f0-b82a-61624597a6ca
ms:mtpsurl: https://technet.microsoft.com/library/Dn452004(v=AX.60)
ms:contentKeyID: 56713175
author: tonyafehr
ms.date: 05/13/2014
mtps_version: v=AX.60
f1_keywords:
- Classes.RPayAlimonySheetReport
- Classes.RPayCalcPaySheetReport
- Classes.RpayEmplPayList
- Classes.RPayReportHeadCountOverWages
- Classes.RpaySheetBankPayment
- Classes.RPaySheetCalcReport
- Classes.RPaySheetCalcTotalReport
- Classes.RPaySheetReport
- Classes.RpayStandardDeductionBankPayment
- Classes.RPayT13Report
- payroll accounting
- payroll report
- payslip
- timesheet report
audience: Application User
ms.search.region: Russia
---

# (RUS) Payroll accounting reports 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic provides a list of payroll accounting reports that are specific to Russia. These reports are located in the Payroll (Russia) area of Microsoft Dynamics AX. The table in each section explains where to find the report in the Application Object Tree (AOT) and how to open the report in the Microsoft Dynamics AX client. For more information, see [Microsoft Dynamics AX reports](microsoft-dynamics-ax-reports.md).

## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Payroll (Form T-53)

Generate and print a report that displays the payroll pay sheet details for a specific payroll calculation period (statutory Form T-53) that is used to pay salary as cash payments after collecting the signatures of the respective employees.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPaySheetReport</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPaySheetReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPaySheetReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Salary payment</strong> &gt; <strong>Reports</strong> &gt; <strong>Payroll</strong>.</p></td>
</tr>
</tbody>
</table>


## Salary calculation sheet

Generate and print a report that displays the payroll summary details such as the accruals, deductions, net amounts, employee debts, employer’s debts, and the employees grouped by departments for a specific payroll calculation period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPaySheetCalcReport</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPaySheetCalcReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPaySheetCalcReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Salary payment</strong> &gt; <strong>Salary calculation sheet</strong>.</p></td>
</tr>
</tbody>
</table>


## Total payroll

Generate and print a report that displays the payroll pay sheet summary details such as the pay sheet status, net values payable by cash and bank, and the deposited salary grouped by departments.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPaySheetCalcTotalReport</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPaySheetCalcTotalReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPaySheetCalcTotalReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Salary payment</strong> &gt; <strong>Total payroll</strong>.</p></td>
</tr>
</tbody>
</table>


## Alimony payroll (T-53)

Generate and print a report that displays the alimony pay sheet (statutory Form T-53), which is used to pay the deducted alimony in cash after collecting the signatures of the respective employees.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayAlimonySheetReport</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayAlimonySheetReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayAlimonySheetReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Standard deductions</strong> &gt; <strong>Alimony payroll</strong>.</p></td>
</tr>
</tbody>
</table>


## Mail order list

Generate and print a report that displays a list of alimony payments that are deducted from the salary of the employees. These payments are made to the recipients by postal service.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayPostalTransferList</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayPostalTransferList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayPostalTransferList</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Standard deductions</strong> &gt; <strong>Mail order list</strong>.</p></td>
</tr>
</tbody>
</table>


## List for transferring to bank

Generate and print a report that displays a list of salary payments that are transferred to the bank accounts of employees.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RpaySheetBankPayment</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RpaySheetBankPayment</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPaySheetBankPaymentReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Salary payment</strong> &gt; <strong>Reports</strong> &gt; <strong>List for transferring to bank</strong>.</p></td>
</tr>
</tbody>
</table>


## Standard bank deductions

Generate and print a report that displays the standard deductions withheld from employees’ payroll during a specific payroll calculation period. The deductions are transferred to the recipients through banks.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RpayStandardDeductionBankPayment</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RpayStandardDeductionBankPayment</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RpayStandardDeductionBankPayment</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Standard deductions</strong> &gt; <strong>Standard bank deductions</strong>.</p></td>
</tr>
</tbody>
</table>


## Timesheet (T-13)

Generate and print the employees’ timesheets reporting form (statutory Form T-13 of working time accounting) for a selected department.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayT13Report</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayT13Report</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayT13Report</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Printing of sick list calculation protocol</strong>. Click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Calculation payment sheet (T-49)

Generate and print a report that displays details of the payroll calculation and pay sheet (statutory Form T-49 of the calculation and pay sheet), which is used to pay salary in cash after collecting the signatures of the respective employees.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayCalcPaySheetReport</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayCalcPaySheetReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayCalcPaySheet</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Salary payment</strong> &gt; <strong>Pay-sheets</strong> . In the <strong>Payroll type</strong> field, select <strong>Payroll</strong>, and then click <strong>Calculation payment sheet</strong>.</p></td>
</tr>
</tbody>
</table>


## Pay slips

Generate and print pay slips for employees that display the details of individual employee payroll for the specific calculation period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RpayEmplPayList</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RpayEmplPayList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RpayEmplPayList</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Payment slips</strong>.</p></td>
</tr>
</tbody>
</table>


## Head count distributed over wages

Generate and print a report that displays the number of employees in the company for different levels of salaries (statutory Form N 1 of the statistical observation) for a specific period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayReportHeadCountOverWages</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayReportHeadCountOverWages</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayReportHeadCountOverWages</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistical observation forms</strong> &gt; <strong>Head count distributed over wages</strong>.</p></td>
</tr>
</tbody>
</table>


## Payroll groups

Generate and print a report that displays the details of the employees or workers who are assigned to payroll groups. Employees and workers are assigned to payroll groups based on characteristics such as date of birth, gender, marital status, or parental status. You can use payroll groups to define parameters that are specific to workers, calculate salaries and taxes, and to generate reports such as the number of female employees or the number of people with a disability who are employed by the company.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayReport_PayGroup</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayReport_PayGroup</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayReport_PayGroup</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Setup</strong> &gt; <strong>Payroll groups</strong>.</p></td>
</tr>
</tbody>
</table>


## Salary report

Generate and print a report that shows the monthly earnings for the selected employee within a period that you select.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayReport_EmplMonthIncome</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayReport_EmplMonthIncome</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayReport_EmplMonthIncome</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Salary Report</strong>.</p></td>
</tr>
</tbody>
</table>


## Book of deposited payroll

Generate and print a report that displays the details about deposited payroll amounts, including incoming balances, paid deposits, and outgoing balances.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayReport_DepositJournal</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayReport_DepositJournal</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayReport_DepositJournal</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Salary payment</strong> &gt; <strong>Reports</strong> &gt; <strong>Book of deposited payroll</strong>.</p></td>
</tr>
</tbody>
</table>


## Registry of deposited amounts

Generate and print a register of deposited amounts for the selected period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPaySheetListReport</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPaySheetListReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPaySheetListReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Salary payment</strong> &gt; <strong>Reports</strong> &gt; <strong>Registry of deposited amounts</strong>.</p></td>
</tr>
</tbody>
</table>


## Income sheet

Generate and print a report that shows employee payments aggregated by payment type for a calculation period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayReport_ChargeType</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayReport_ChargeType</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayChargeTypeReportAddSum</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Income sheet</strong>.</p></td>
</tr>
</tbody>
</table>


## Retention sheet

Generate and print a report that shows deductions from employees’ gross salaries aggregated by deduction type for a calculation period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayReport_ChargeType</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayReport_ChargeType</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayChargeTypeReportDeduction</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Retention sheet</strong>.</p></td>
</tr>
</tbody>
</table>


## Rates

Generate and print a report that contains a list of rates and their corresponding values for a selected category. This report can be printed for a department, group, worker, or employee. For more information, see "Set up rates based on value type" in [(RUS) Set up parameters for the payroll process](rus-set-up-parameters-for-the-payroll-process.md).

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayReport_Rate</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayReport_Rate</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayRatesReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Rates</strong>.</p></td>
</tr>
</tbody>
</table>


## Payroll journal

Generate and print a report that contains a list of the incentive payments that are made to employees who are registered in the selected journal.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayReport_PayJournal</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayReport_PayJournal</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayJournal</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Calculation procedures</strong> &gt; <strong>Payroll journal</strong> &gt; <strong>Payroll journal</strong>. Click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Statistics statement

Generate and print user-defined reports that have a flexible structure and can display various types of information such as payroll transaction amounts, rate values, counter values, and text fields.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayBalanceSheetPrint</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayBalanceSheetPrint</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayBalanceSheetPrint</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics statement</strong>.</p></td>
</tr>
</tbody>
</table>


## Print Act

Generate and print a document that confirms that a particular stage of a civil contract is complete. Payment is made to an employee based on a signed act.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>RPayCivilContractActReport</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Classes\RPayCivilContractActReport</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RPayCivilContractActReportt</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll (Russia)</strong> &gt; <strong>Calculation procedures</strong> &gt; <strong>Civil contracts</strong> &gt; <strong>Civil contracts</strong>. Select a contract, then select an act belonging to the selected contract. Click <strong>Print act</strong>.</p></td>
</tr>
</tbody>
</table>

  


