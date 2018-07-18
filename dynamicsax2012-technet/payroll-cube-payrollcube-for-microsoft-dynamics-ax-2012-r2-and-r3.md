---
title: Payroll cube (PayrollCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Payroll cube (PayrollCube)
ms:assetid: 502c2ffb-de77-43ba-92f5-e2857fe1e542
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn530764(v=AX.60)
ms:contentKeyID: 59683043
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Payroll cube (PayrollCube) for Microsoft Dynamics AX 2012 R2 and R3 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Payroll cube for Microsoft Dynamics AX is used to analyze data about earnings statements, pay statements, workers, positions, arrears, tax history, benefits, benefit accruals, and reversals. Analysis of payroll data is required for organizations to effectively manage payrolls and make decisions based on accurate information. This article provides details about the cube.


> [!NOTE]
> <P>This cube is available with cumulative update 7 for Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/JJ710380.TopicIcons_Reference(AX.60).png" title="Reference" alt="Reference" />
<p>Deployment</p>
<p>Configuration keys</p>
<p>Tables and views</p>
<p>Measures</p>
<p>Calculated measures</p>
<p>Key performance indicators</p>
<p>Security</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-r2-and-r3.md">Cube and KPI reference for Microsoft Dynamics AX 2012 R2 and R3</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md">Cube and KPI reference for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack</a></p></td>
</tr>
</tbody>
</table>


## Deployment

The Payroll cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Payroll cube:

  - Payroll (Payroll)

## Tables and views

The Payroll cube uses data from the following tables and views:

  - HcmBenefitOption table

  - HcmBenefitType table

  - HcmPositionWorkerAssignment table

  - HcmWorker table

  - PayrollEarningStatement table

  - PayrollEarningStatementLine table

  - PayrollPayCycle table

  - PayrollPayPeriod table

  - PayrollPayStatement table

  - PayrollPayStatementAccrualBalance table

  - PayrollPayStatementLine table

  - PayrollTaxCode table

  - PRLDeductionArrear table

  - PrlUSTaxTransactionHistory table

  - HcmBenefitCube view

  - HcmBenefitPlanCube view

  - HcmDepartmentCube view

  - HcmJobCube view

  - HcmUnionAgreementCube view

  - PayrollAccrualTransactionsView view

  - PayrollArrearsCube view

  - PayrollBenefitAccrualCube view

  - PayrollEarningCodeCube view

  - PayrollEarningStatementCube view

  - PayrollEmploymentCube view

  - PayrollPayStatementCube view

  - PayrollPositionDetailCube view

  - PayrollTaxRegionCube view

  - PayrollTaxTransHistoryCube view

  - PayrollWorkerEnrolledBenefitsCube view

## Measures

The Payroll cube includes the following measure groups.

## Worker arrears

This measure group is based on the PayrollArrearsCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Worker arrears count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
    <td rowspan="3"> <p>
   
	 Company
  </p> <p>
   
	 Worker arrears
  </p> <p>
   
	 Worker arrears table
  </p> <p>
   
	 Payroll pay statement
  </p> <p>
   
	 Worker slicer
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Payroll pay statement (payroll pay statement - pay statement number)
  </p> <p>
   
	 Date (transaction date arrear created)
  </p> <p>
   
	 Date (transaction date arrear recovered)
  </p> <p>
   
	 Date (pay period arrear created - start date)
  </p> <p>
   
	 Date (pay period arrear created - end date)
  </p> <p>
   
	 Date (pay period arrear recovered - start date)
  </p> <p>
   
	 Date (pay period arrear recovered - end date)
  </p> <p>
   
	 Payroll benefit plan
  </p> <p>
   
	 Benefit option
  </p> <p></p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sum of arrears - recovery in transaction currency
  </p> </td>
    <td> <p>
   
	 PayrollArrearsCube.DeductionArrearAmountAC
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the amount in the Transaction Currency field on the Arrearage Recovery and Adjustments grid of the Worker Arrears form.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sum of arrear - original amount
  </p> </td>
    <td> <p>
   
	 PayrollArrearsCube.DeductionArrearSumAC
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
</table>


## Worker earnings statement totals

This measure group is based on the PayrollEarningStatementCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Worker earnings statement totals count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
    <td rowspan="4"> <p>
   
	 Company
  </p> <p>
   
	 Jobs
  </p> <p>
   
	 Union agreement
  </p> <p>
   
	 Earning code
  </p> <p>
   
	 Earnings statement
  </p> <p>
   
	 Payroll positions
  </p> <p>
   
	 Tax region
  </p> <p>
   
	 Payroll earning statement
  </p> <p>
   
	 Earning statement detail
  </p> <p>
   
	 Pay cycle
  </p> <p>
   
	 Pay period
  </p> <p>
   
	 Worker slicer
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (earnings date)
  </p> <p>
   
	 Date (pay period end date)
  </p> <p>
   
	 Date (pay period start date)
  </p> <p>
   
	 Benefit (worker compensation benefit)
  </p> <p>
   
	 Benefit (worker general liability insurance benefit)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Workers total earning amount
  </p> </td>
    <td> <p>
   
	 PayrollEarningStatementCube.AccountingCurrencyAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Workers total earning quantity
  </p> </td>
    <td> <p>
   
	 PayrollEarningStatementCube.Quantity
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sum of earning rate
  </p> </td>
    <td> <p>
   
	 PayrollEarningStatementCube.EarningRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Earning statements count
  </p> </td>
    <td> <p>
   
	 PayrollEarningStatementCube.EarningStatement
  </p> </td>
    <td> <p>
   
	 Distinct count
  </p> </td>
    <td> <p>
   
	 The number of earning statements created in the system.
  </p> </td>
  </tr>
</table>


## Payroll workers

This measure group is based on the PayrollEmploymentCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Payroll workers count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Position worker assignments
  </p> <p>
   
	 Jobs
  </p> <p>
   
	 Departments
  </p> <p>
   
	 Union agreement
  </p> <p>
   
	 Payroll employment
  </p> <p>
   
	 Payroll positions
  </p> <p>
   
	 Worker slicer
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (employment start date)
  </p> <p>
   
	 Date (employment end date)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 IsEmployeeActive
  </p> </td>
    <td> <p>
   
	 PayrollEmploymentCube.IsEmployeeActive
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
</table>


## Pay statements

This measure group is based on the PayrollPayStatementCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Pay statements Count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of pay statements in the system.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Jobs
  </p> <p>
   
	 Union agreement
  </p> <p>
   
	 Benefit accrual plan
  </p> <p>
   
	 Earning code
  </p> <p>
   
	 Pay statements
  </p> <p>
   
	 Payroll positions
  </p> <p>
   
	 Tax region
  </p> <p>
   
	 Pay cycle
  </p> <p>
   
	 Pay period
  </p> <p>
   
	 Payroll pay statement
  </p> <p>
   
	 Payment benefit accrual balance
  </p> <p>
   
	 Pay statement lines
  </p> <p>
   
	 Tax code
  </p> <p>
   
	 Worker slicer
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (earnings date)
  </p> <p>
   
	 Date (pay period end date)
  </p> <p>
   
	 Date (pay period start date)
  </p> <p>
   
	 Payroll pay statement (payroll pay statement number 1)
  </p> <p>
   
	 Benefit (worker compensation benefit)
  </p> <p>
   
	 Benefit (worker general liability insurance benefit)
  </p> <p>
   
	 Date (accounting date)
  </p> <p>
   
	 Date (payment date)
  </p> <p>
   
	 Payroll benefit plan
  </p> <p>
   
	 Benefit option
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Amount in transaction currency
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.AccountingCurrencyAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Pay statement counts
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.PayStatement
  </p> </td>
    <td> <p>
   
	 Distinct count
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Gross pay
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.GrossAccountingCurrencyAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Net pay
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.NetAccountingCurrencyAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Pay statements amount in transaction currency
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.BaseTimeEarningBaseAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Quantity
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.BaseTimeEarningBaseHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Pay statements amount in transaction currency 0
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.PremiumEarningBaseAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Pay statements quantity
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.PremiumEarningBaseHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Rate
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.EarningRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Pay statements quantity 0
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.Quantity
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Benefit accrual plan
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.Accrual
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Amount accrued
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.AccruedHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Plan year accrued
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.TotalAccruedHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Available
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.TotalAvailableHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Plan year used
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.TotalUsedHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Amount used
  </p> </td>
    <td> <p>
   
	 PayrollPayStatementCube.UsedHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p></p> </td>
    <td> <p></p> </td>
    <td> <p></p> </td>
    <td> <p></p> </td>
  </tr>
</table>


## Payroll tax transaction history

This measure group is based on the PayrollTaxTransHistoryCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Payroll tax transaction history Count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
    <td rowspan="9"> <p>
   
	 Company
  </p> <p>
   
	 Jobs
  </p> <p>
   
	 Union agreement
  </p> <p>
   
	 Tax transaction date
  </p> <p>
   
	 Payroll positions
  </p> <p>
   
	 Payroll tax transaction history
  </p> <p>
   
	 Prl US tax transaction history
  </p> <p>
   
	 Tax code
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (tax transaction date)
  </p> <div><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/Dn530764.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 The Payroll positions and Payroll tax transaction history dimensions are associated with this measure only in Microsoft Dynamics AX 2012 R3.
  </p> </td></tr></table></div></td>
  </tr>
  <tr>
    <td> <p>
   
	 Calculated tax amount
  </p> </td>
    <td> <p>
   
	 PayrollTaxTransHistoryCube.CalculatedTaxAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Excess wages
  </p> </td>
    <td> <p>
   
	 PayrollTaxTransHistoryCube.ExcessWages
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Gross subject wages
  </p> </td>
    <td> <p>
   
	 PayrollTaxTransHistoryCube.GrossSubjectWages
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Gross wages
  </p> </td>
    <td> <p>
   
	 PayrollTaxTransHistoryCube.GrossWages
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Hours
  </p> </td>
    <td> <p>
   
	 PayrollTaxTransHistoryCube.Hours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Tax rate
  </p> </td>
    <td> <p>
   
	 PayrollTaxTransHistoryCube.Rate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Subject wages
  </p> </td>
    <td> <p>
   
	 PayrollTaxTransHistoryCube.SubjectWages
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Tax line amount
  </p> </td>
    <td> <p>
   
	 PayrollTaxTransHistoryCube.TaxLineAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
</table>


## Payroll worker enrolled benefits

This measure group is based on the PayrollWorkerEnrolledBenefitsCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Payroll worker enrolled benefits Count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
    <td rowspan="6"> <p>
   
	 Company
  </p> <p>
   
	 Benefit type
  </p> <p>
   
	 Jobs
  </p> <p>
   
	 Union agreement
  </p> <p>
   
	 Payroll positions
  </p> <p>
   
	 Payroll worker enrolled benefits
  </p> <p>
   
	 Worker slicer
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Payroll benefit plan
  </p> <p>
   
	 Benefit option
  </p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Contribution
  </p> </td>
    <td> <p>
   
	 PayrollWorkerEnrolledBenefitsCube.ContributionAmountCur
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Deduction
  </p> </td>
    <td> <p>
   
	 PayrollWorkerEnrolledBenefitsCube.DeductionAmountCur
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Amount
  </p> </td>
    <td> <p>
   
	 PayrollWorkerEnrolledBenefitsCube.DefaultContributionAccountingCurrencyAmt
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Payroll worker enrolled benefits amount
  </p> </td>
    <td> <p>
   
	 PayrollWorkerEnrolledBenefitsCube.DefaultDeductionAccountingCurrencyAmt
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Number of benefit enrollments
  </p> </td>
    <td> <p>
   
	 PayrollWorkerEnrolledBenefitsCube.HCMWorkerEnrolledBenefitRecID
  </p> </td>
    <td> <p>
   
	 Distinct count
  </p> </td>
    <td> <p>
   
	 Count or number of benefit enrollments.
  </p> </td>
  </tr>
</table>


## Benefit accruals

This measure group is based on the PayrollAccrualTransactionsView view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Benefit accruals Count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
    <td rowspan="6"> <p>
   
	 Company
  </p> <p>
   
	 Benefit accrual plan
  </p> <p>
   
	 Earning code
  </p> <p>
   
	 Payroll accrual transaction view
  </p> <p>
   
	 Worker
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Total accrued
  </p> </td>
    <td> <p>
   
	 PayrollAccrualTransactionsView.Accrued
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of benefit accrual plans that have been associated with workers.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Total carry-forward
  </p> </td>
    <td> <p>
   
	 PayrollAccrualTransactionsView.CarryOver
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The balance that was carried forward from the previous plan year, including any manual adjustments.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Total used
  </p> </td>
    <td> <p>
   
	 PayrollAccrualTransactionsView.Used
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total amount that has been used during the current plan year, including any manual adjustments.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Total pending usage
  </p> </td>
    <td> <p>
   
	 PayrollAccrualTransactionsView.PendingUsage
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The amount that has been released in earnings statement lines but that has not been submitted for payment.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Total available hours
  </p> </td>
    <td> <p>
   
	 PayrollAccrualTransactionsView.TotalAvailableHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of balance accruals that is available for workers to use. 
  </p> <p>
   
	 Available = Carry forward + Plan year accrued - Plan year used - Pending usage (Hours entered in earning statement line that are released).
  </p> </td>
  </tr>
</table>


## Calculated measures

The Payroll cube contains the following calculated measures.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated measure</p></th>
<th><p>Aggregation</p></th>
<th><p>Associated measure group</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Pay statement - average of net amount</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of net amounts on the pay statements, so it is the sum of net pay statements divided by the total number of pay statements.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement - average of gross amount</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of gross amounts on the pay statements, so it is the sum of gross pay statements divided by the total number of pay statements.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement - sum of gross amount</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of gross amounts on the pay statements, so it is the sum of gross pay statements divided by the total number of pay statements.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement - sum of net amount</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of net amounts on the pay statements, so it is the sum of net pay statements divided by the total number of pay statements.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement benefit lines - average of base earning amounts</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the amount from the base time portion of the applicable earnings.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement benefit lines - average of base earning hours</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the hours from the base time portion of the applicable earnings.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement benefit lines - average of premium earning amounts</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the amount from the premium time portion of the applicable earnings.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement benefit lines - average of premium earning hours</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the hours from the premium time portion of the applicable earnings.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement earning lines - average of earning rates</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the rate specified on the earning lines of the pay statement on the Earnings tab.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement earning lines - average of quantities</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the quantity specified on the earning lines of the pay statement on the Earnings tab.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement accrual balances - average of accrued hours</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the amount accrued on a pay statement’s Benefit Accrual Calculations tab.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement accrual balances - average of plan year accrued hours</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the plan year accrued on a pay statement’s Benefit Accrual Calculations tab.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement accrual balances - average of available hours</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the available hours on a pay statement’s Benefit Accrual Calculations tab.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement accrual balances - average of plan year used hours</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the plan year used on a pay statement’s Benefit Accrual Calculations tab.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement accrual balances - average of number of hours used</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the amount used on a pay statement’s Benefit Accrual Calculations tab.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement benefit lines - sum of base earning amounts</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the amount from the base time portion of the applicable earnings.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement benefit lines - sum of base earning hours</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the hours from the base time portion of the applicable earning.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement benefit lines - sum of premium earning amounts</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the amount from the premium time portion of the applicable earnings.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement benefit lines - sum of premium earning hours</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the hours from the premium time portion of the applicable earnings.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement earning lines - sum of quantities</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the quantity specified on the earning lines of the pay statement on the Earnings tab.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement accrual balances - sum of accrued hours</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the amount accrued on a pay statement’s Benefit Accrual Calculations tab.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement accrual balances - sum of plan year accrued hours</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the plan year accrued on a pay statement’s Benefit Accrual Calculations tab.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement accrual balances - sum of available hours</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the available hours on a pay statement’s Benefit Accrual Calculations tab.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement accrual balances - sum of plan year used hours</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the plan year used on a pay statement’s Benefit Accrual Calculations tab.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement accrual balances - sum of number of hours used</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>This calculated measure is hidden to end users. It is used in other calculations.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement lines count</p></td>
<td><p>Count</p></td>
<td><p>Pay statements</p></td>
<td><p>This calculated measure is hidden to end users. It is used in other calculations.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement earning lines count</p></td>
<td><p>Count</p></td>
<td><p>Pay statements</p></td>
<td><p>This calculated measure is hidden to end users. It is used in other calculations.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement benefit lines count</p></td>
<td><p>Count</p></td>
<td><p>Pay statements</p></td>
<td><p>This calculated measure is hidden to end users. It is used in other calculations.</p></td>
</tr>
<tr class="odd">
<td><p>Earnings statement lines - average of earning rates</p></td>
<td><p>Average</p></td>
<td><p>Worker earnings statement totals</p></td>
<td><p>The average of the Rate field for the earning statement line.</p></td>
</tr>
<tr class="even">
<td><p>Earnings statement lines - average of earning quantities</p></td>
<td><p>Average</p></td>
<td><p>Worker earnings statement totals</p></td>
<td><p>The average of the Quantity field for the earning statement line.</p></td>
</tr>
<tr class="odd">
<td><p>Earnings statement lines - average of line amounts</p></td>
<td><p>Average</p></td>
<td><p>Worker earnings statement totals</p></td>
<td><p>The average of the Amount field for the earning statement line.</p></td>
</tr>
<tr class="even">
<td><p>Earnings statement lines - sum of line amounts</p></td>
<td><p>Sum</p></td>
<td><p>Worker earnings statement totals</p></td>
<td><p>The sum of the Amount field for the earning statement line.</p></td>
</tr>
<tr class="odd">
<td><p>Earnings statement lines - sum of quantities</p></td>
<td><p>Sum</p></td>
<td><p>Worker earnings statement totals</p></td>
<td><p>The sum of the Quantity field for the earning statement line.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement tax lines count</p></td>
<td><p>Count</p></td>
<td><p>Pay statements</p></td>
<td><p>This calculated measure is hidden to end users. It is used in other calculations.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement lines - sum of earning lines amounts</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the amount specified on the earning line of the pay statement’s Earnings tab.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement lines - sum of benefit lines amounts</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the Deduction Amount + Contribution Amount on the Benefit Calculations tab of a pay statement. It looks best if sliced with the Payroll Benefit Plan dimension.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement lines - sum of tax lines amounts</p></td>
<td><p>Sum</p></td>
<td><p>Pay statements</p></td>
<td><p>The sum of the Deduction Amount + Contribution Amount specified on the Tax Calculations tab of a pay statement.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement lines - average of earning lines amounts</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the amount specified on the earning line of the pay statement’s Earnings tab.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement lines - average of benefit lines amounts</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the Deduction Amount + Contribution Amount on the Benefit Calculations tab of a pay statement. It looks best if sliced with the Payroll Benefit Plan dimension.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement lines - average of tax lines amounts</p></td>
<td><p>Average</p></td>
<td><p>Pay statements</p></td>
<td><p>The average of the Deduction Amount + Contribution Amount on the Tax Calculations tab of a pay statement. It looks best if sliced with the Tax Code dimension.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statement - sum of benefit accrual lines count</p></td>
<td><p>Count</p></td>
<td><p>Pay statements</p></td>
<td><p>This calculated measure is hidden to end users. It is used in other calculations.</p></td>
</tr>
<tr class="even">
<td><p>Sum of calculated tax amount</p></td>
<td><p>Sum</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The sum of the amount of tax calculated for the payment.</p></td>
</tr>
<tr class="odd">
<td><p>Sum of excess wages</p></td>
<td><p>Sum</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The sum of the portion of the current wages that exceed the unemployment wage base.</p></td>
</tr>
<tr class="even">
<td><p>Sum of gross subject wages</p></td>
<td><p>Sum</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The sum of the amount of gross wages subject to the tax.</p></td>
</tr>
<tr class="odd">
<td><p>Sum of gross wages</p></td>
<td><p>Sum</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The sum of the amount of gross wages used to calculate the tax.</p></td>
</tr>
<tr class="even">
<td><p>Sum of hours</p></td>
<td><p>Sum</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The sum of the hours from all earning codes used to calculate the gross wages.</p></td>
</tr>
<tr class="odd">
<td><p>Sum of subject wages</p></td>
<td><p>Sum</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The sum of the amount of wages subject to the tax.</p></td>
</tr>
<tr class="even">
<td><p>Average of subject wages</p></td>
<td><p>Average</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The average of the amount of wages subject to the tax.</p></td>
</tr>
<tr class="odd">
<td><p>Average of calculated tax amount</p></td>
<td><p>Average</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The average of the amount of tax calculated for the payment.</p></td>
</tr>
<tr class="even">
<td><p>Average of excess wages</p></td>
<td><p>Average</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The average of the portion of the current wages that exceed the unemployment wage base.</p></td>
</tr>
<tr class="odd">
<td><p>Average of gross subject wages</p></td>
<td><p>Average</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The average of the amount of gross wages subject to the tax.</p></td>
</tr>
<tr class="even">
<td><p>Average of gross wages</p></td>
<td><p>Average</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The average of the amount of gross wages used to calculate the tax.</p></td>
</tr>
<tr class="odd">
<td><p>Average of hours</p></td>
<td><p>Average</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The average of the hours from all earning codes used to calculate the gross wages.</p></td>
</tr>
<tr class="even">
<td><p>Prl tax transactions count</p></td>
<td><p>Count</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>This calculated measure is hidden to end users. It is used in other calculations.</p></td>
</tr>
<tr class="odd">
<td><p>Average of tax rate</p></td>
<td><p>Average</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The average of the tax rate.</p></td>
</tr>
<tr class="even">
<td><p>Sum of actual combined tax</p></td>
<td><p>Sum</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The sum of the actual tax amount for the combined tax transaction.</p></td>
</tr>
<tr class="odd">
<td><p>Average of actual combined tax</p></td>
<td><p>Average</p></td>
<td><p>Payroll tax transaction history</p></td>
<td><p>The average of actual tax amount for the combined tax transaction.</p></td>
</tr>
<tr class="even">
<td><p>Sum of arrears - original amount</p></td>
<td><p>Sum</p></td>
<td><p>Worker arrears</p></td>
<td><p>The sum of the original amount on the Worker Arrears form.</p></td>
</tr>
<tr class="odd">
<td><p>Sum of arrears - amount remaining</p></td>
<td><p>Sum</p></td>
<td><p>Worker arrears</p></td>
<td><p>The sum of the amount remaining on the Worker Arrears form.</p></td>
</tr>
<tr class="even">
<td><p>Number of workers</p></td>
<td><p>Count</p></td>
<td><p>Payroll workers</p></td>
<td><p>The number or count of workers.</p></td>
</tr>
<tr class="odd">
<td><p>Workers terminated count</p></td>
<td><p>Count</p></td>
<td><p>Payroll workers</p></td>
<td><p>The number of employees that are being terminated or employment end date is less than today.</p></td>
</tr>
<tr class="even">
<td><p>Number of position assignments</p></td>
<td><p>Count</p></td>
<td><p>Payroll workers</p></td>
<td><p>The number of positions assigned to a worker.</p></td>
</tr>
<tr class="odd">
<td><p>Sum of contribution amount</p></td>
<td><p>Sum</p></td>
<td><p>Payroll worker enrolled benefits</p></td>
<td><p>The sum of the amount of the employer contribution for the selected plan.</p></td>
</tr>
<tr class="even">
<td><p>Sum of deduction amount</p></td>
<td><p>Sum</p></td>
<td><p>Payroll worker enrolled benefits</p></td>
<td><p>The sum of the amount of the worker deduction for the selected plan.</p></td>
</tr>
<tr class="odd">
<td><p>Sum of default contribution amount</p></td>
<td><p>Sum</p></td>
<td><p>Payroll worker enrolled benefits</p></td>
<td><p>The sum of the default amount contributed each pay period until the contribution limit is reached.</p></td>
</tr>
<tr class="even">
<td><p>Sum of default deduction amount</p></td>
<td><p>Sum</p></td>
<td><p>Payroll worker enrolled benefits</p></td>
<td><p>The sum of the default amount deducted each pay period until the deduction limit is reached.</p></td>
</tr>
<tr class="odd">
<td><p>Number of employments</p></td>
<td><p>Count</p></td>
<td><p>Payroll workers</p></td>
<td><p>The number of employees.</p></td>
</tr>
<tr class="even">
<td><p>Pay statement count</p></td>
<td><p>Count</p></td>
<td><p>Pay statements</p></td>
<td><p>The number of pay statements in the system.</p></td>
</tr>
<tr class="odd">
<td><p>Earnings statement lines count</p></td>
<td><p>Count</p></td>
<td><p>Worker earnings statement totals</p></td>
<td><p>The number of lines on the earning statement.</p></td>
</tr>
<tr class="even">
<td><p>Number of workers paid by electronically</p></td>
<td><p>Count</p></td>
<td><p>Payroll workers</p></td>
<td><p>The number or count of employees paid electronically.</p></td>
</tr>
<tr class="odd">
<td><p>Number of workers paid by check</p></td>
<td><p>Count</p></td>
<td><p>Payroll workers</p></td>
<td><p>The number or count of employees paid by check.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The Payroll cube does not include any key performance indicators (KPIs).

## Security

The Payroll cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Human resource assistant

  - Payroll administrator

  - Payroll manager

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

