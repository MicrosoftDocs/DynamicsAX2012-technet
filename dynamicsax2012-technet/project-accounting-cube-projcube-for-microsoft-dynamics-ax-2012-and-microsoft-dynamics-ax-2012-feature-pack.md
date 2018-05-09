---
title: Project accounting cube (ProjCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack
TOCTitle: Project accounting cube (ProjCube)
ms:assetid: 2fb11049-e523-4b38-862e-29ecb5621867
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh781067(v=AX.60)
ms:contentKeyID: 43894466
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Project accounting cube (ProjCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the Project accounting cube to report on project profitability, committed cost, employee utilization, and cash flow for one or multiple projects in a company.

## Configuration keys

The following configuration keys are required to use all features of the Project accounting cube:

  - Project I (ProjBasic)

  - Project II (ProjAdvanced)

## Tables and views

The Project accounting cube uses data from the following tables and views:

  - CustGroup table

  - ForecastModel table

  - ProjCategory table

  - ProjFundingSource table

  - ProjGroup table

  - ProjInvoiceTable table

  - ProjPeriodEmpl table

  - CostControlTransCommittedCostCube view

  - InventTableExpanded view

  - ProjBIEmplTrans view

  - ProjBIForecastEmpl view

  - ProjTableCube view

  - ProjTransBudgetCube view

  - ProjTransPostingCube view

  - smmActivitesCube view

## Measures

The Project accounting cube includes the following measure groups.

## Actual hour utilization

This measure group is based on the ProjBIEmplTrans view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th> <p>
   
	 Aggregation
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 Actual hour utilization count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of actual hour transactions.
  </p> </td>
    <td rowspan="8"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Projects
  </p> <p>
   
	 Activity
  </p> <p>
   
	 Project category
  </p> <p>
   
	 Project contracts
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (ledger date)
  </p> <p>
   
	 Date (project transaction date)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual efficiency burden hours
  </p> </td>
    <td> <p>
   
	 ProjBIEmplTrans.ActualBurdenEfficiencyRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of burden hours using the efficiency calculation method.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual efficiency utilized hours
  </p> </td>
    <td> <p>
   
	 ProjBIEmplTrans.ActualUtilizationEfficiencyRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of utilized hours logged using the efficiency calculation method.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual billable utilized hours
  </p> </td>
    <td> <p>
   
	 ProjBIEmplTrans.ActualUtilizationBillableRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of utilized hours logged using the billable calculation method.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual billable burden hours
  </p> </td>
    <td> <p>
   
	 ProjBIEmplTrans.ActualBurdenBillableRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of burden hours logged using the billable calculation method.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual efficiency overtime hours
  </p> </td>
    <td> <p>
   
	 ProjBIEmplTrans.ActualOvertimeHoursEfficiencyRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of overtime hours logged using the efficiency calculation method.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual billable overtime hours
  </p> </td>
    <td> <p>
   
	 ProjBIEmplTrans.ActualOvertimeHoursBillableRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of overtime hours logged using the billable calculation method.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Hours quantity
  </p> </td>
    <td> <p>
   
	 ProjBIEmplTrans.Qty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of hours logged.
  </p> </td>
  </tr>
</table>


## Forecast hour utilization

This measure group is based on the ProjBIForecastEmpl view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th> <p>
   
	 Aggregation
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 Forecast hour utilization count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of forecast hour transactions.
  </p> </td>
    <td rowspan="9"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Projects
  </p> <p>
   
	 Activity
  </p> <p>
   
	 Model
  </p> <p>
   
	 Project category
  </p> <p>
   
	 Project contracts
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (ledger date)
  </p> <p>
   
	 Date (project transaction date)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Hour forecast quantity
  </p> </td>
    <td> <p>
   
	 ProjBIForecastEmpl.Qty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total forecast hours.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget efficiency utilized hours
  </p> </td>
    <td> <p>
   
	 ProjBIForecastEmpl.BudgetUtilizationEfficiencyRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of utilized hours forecast using the efficiency calculation method.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget efficiency burden hours
  </p> </td>
    <td> <p>
   
	 ProjBIForecastEmpl.BudgetBurdenEfficiencyRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of burden hours forecast using the efficiency calculation method.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Hour forecast cost price
  </p> </td>
    <td> <p>
   
	 ProjBIForecastEmpl.CostPrice
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of costs for forecasted hours.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget billable utilized hours
  </p> </td>
    <td> <p>
   
	 ProjBIForecastEmpl.BudgetUtilizationBillableRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of utilized hours forecast using the billable calculation method.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget billable burden hours
  </p> </td>
    <td> <p>
   
	 ProjBIForecastEmpl.BudgetBurdenBillableRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of burden hours forecast using the billable calculation method.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget billable overtime hours
  </p> </td>
    <td> <p>
   
	 ProjBIForecastEmpl.BudgetOvertimeHoursBillableRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of overtime hours forecast using the billable calculation method.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget efficiency overtime hours
  </p> </td>
    <td> <p>
   
	 ProjBIForecastEmpl.BudgetOvertimeHoursEfficiencyRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of overtime hours forecast using the efficiency calculation method.
  </p> </td>
  </tr>
</table>


## Committed costs

This measure group is based on the CostControlTransCommittedCostCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th> <p>
   
	 Aggregation
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 Committed costs count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of committed cost transactions.
  </p> </td>
    <td rowspan="6"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Vendor
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Projects
  </p> <p>
   
	 Activity
  </p> <p>
   
	 Project category
  </p> <p>
   
	 Project contracts
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Committed costs
  </p> <p>
   
	 Date (committed date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Committed cost
  </p> </td>
    <td> <p>
   
	 CostControlTransCommittedCostCube.CommittedCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total value of committed cost transactions, in the accounting currency.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Committed amount
  </p> </td>
    <td> <p>
   
	 CostControlTransCommittedCostCube.AmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total value of committed cost transactions, in the accounting currency.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Committed cost updates quantity
  </p> </td>
    <td> <p>
   
	 CostControlTransCommittedCostCube.Qty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the quantity for committed item cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Committed hour cost
  </p> </td>
    <td> <p>
   
	 CostControlTransCommittedCostCube.CommittedHourCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of committed hours costs, in the accounting currency.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Committed item cost
  </p> </td>
    <td> <p>
   
	 CostControlTransCommittedCostCube.CommittedItemCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of committed item costs, in the accounting currency.
  </p> </td>
  </tr>
</table>


## Forecasts

This measure group is based on the ProjTransBudgetCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Measures
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th> <p>
   
	 Aggregation
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 Forecasts count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of forecast transactions.
  </p> </td>
    <td rowspan="17"> <p>
   
	 Company
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Projects
  </p> <p>
   
	 Activity
  </p> <p>
   
	 Forecast models
  </p> <p>
   
	 Project funding source
  </p> <p>
   
	 Project category
  </p> <p>
   
	 Project contracts
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Forecasts
  </p> <p>
   
	 Date (ledger date)
  </p> <p>
   
	 Date (project transaction date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget updates quantity
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.Qty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of quantities for forecast item transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget invoiced revenue
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetInvoiceRevenue
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast invoiced revenue transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget updates amount
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.AmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget accrued revenue
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetAccruedRevenue
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast accrued revenue transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget revenue
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetRevenue
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast revenue transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget cost hour
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetCostHour
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast hours cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget cost expense
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetCostExpense
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast T&amp;E cost transactions
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget cost item
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetCostItem
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast item cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget cost
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget WIP cost
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetWIPCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast work in progress cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget WIP sales
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetWIPSales
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast work in progress sales transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget hours
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast hour transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget consumption cost hours
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetConsumptionCostHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast hour consumption cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget consumption cost expense
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetConsumptionCostExpense
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast T&amp;E consumption cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget consumption cost item
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetConsumptionCostItem
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast item consumption cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget consumption
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetConsumption
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast consumption cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget payroll allocation
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetPayrollAllocation
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast payroll allocation transactions.
  </p> </td>
    <td rowspan="13"> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget invoiced on account
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetInvoicedOnAccount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast on account transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Total budget cost
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.TotalBudgetCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Remaining budget cost
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.RemainingBudgetCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast remaining cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Original budget cost
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.OriginalBudgetCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast original budget transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget gross WIP cost
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetGrossWIPCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast work in progress cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget gross margin
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetGrossMargin
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast revenue less forecast cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget net WIP
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetNetWIP
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast work in progress revenue less forecast work in progress cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Remaining budget deviation
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.RemainingBudgetDeviation
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast budget deviation transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget cash inflow
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetCashInflow
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast income transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget cash outflow
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetCashOutflow
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast outlay transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget net cash flow
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetNetCashflow
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast inflow less forecast outflow transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Budget WIP invoiced on account
  </p> </td>
    <td> <p>
   
	 ProjTransBudgetCube.BudgetWIPInvoicedOnAccount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of forecast work in progress on account transactions.
  </p> </td>
  </tr>
</table>


## Actuals

This measure group is based on the ProjTransPostingCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th> <p>
   
	 Aggregation
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 Actuals count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of project transactions.
  </p> </td>
    <td rowspan="25"> <p>
   
	 Company
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Projects
  </p> <p>
   
	 Activity
  </p> <p>
   
	 Project funding source
  </p> <p>
   
	 Project category
  </p> <p>
   
	 Project contracts
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Actuals
  </p> <p>
   
	 Date (ledger date)
  </p> <p>
   
	 Date (project transaction date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Amount
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.AmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual accrued loss
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualAccruedLoss
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project accrued loss transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual accrued revenue
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualAccruedRevenue
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project accrued revenue transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual cash inflow
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualCashInflow
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project income transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual cash outflow
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualCashOutflow
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project outlay transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual consumption
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualConsumption
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project consumption transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual consumption cost expense
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualConsumptionCostExpense
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project consumption T&amp;E cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual consumption cost hours
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualConsumptionCostHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project consumption hours cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual consumption cost item
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualConsumptionCostItem
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project item cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual cost
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual cost committed
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualCostCommitted
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project committed cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual cost expense
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualCostExpense
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project T&amp;E cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual cost hour
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualCostHour
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project hours cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual cost item
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualCostItem
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project item costs transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual gross margin
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualGrossMargin
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project revenue less project cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual gross WIP cost
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualGrossWIPCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project work in progress revenue less project work in progress cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual hours
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualHours
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the hours logged against projects.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual invoiced on account
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualInvoicedOnAccount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project invoiced on account revenue transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual invoiced revenue
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualInvoicedRevenue
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project invoiced revenue transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual net cash flow
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualNetCashflow
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project cash inflow less project cash outflow transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual net WIP
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualNetWIP
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project work in progress revenue less project work in progress cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual payroll allocation
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualPayrollAllocation
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project payroll allocation transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual revenue
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualRevenue
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project revenue transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual WIP cost
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualWIPCost
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project work in progress cost transactions.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual WIP invoiced on account
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualWIPInvoicedOnAccount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project invoiced work in progress on account transactions.
  </p> </td>
    <td rowspan="2"> <p></p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Actual WIP sales
  </p> </td>
    <td> <p>
   
	 ProjTransPostingCube.ActualWIPSales
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the value, in the accounting currency, of project work in progress sales transactions.
  </p> </td>
  </tr>
</table>


## Project periods - employee

This measure group is based on the ProjPeriodEmpl table and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th> <p>
   
	 Aggregation
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 Project periods – employee count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of project period records.
  </p> </td>
    <td rowspan="3"> <p>
   
	 Company
  </p> <p>
   
	 Project periods - employee
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (ledger date)
  </p> <p>
   
	 Date (project transaction date)
  </p> <p>
   
	 Date (start date – date)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Norm billable
  </p> </td>
    <td> <p>
   
	 ProjPeriodEmpl.NormBillable
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the number of hours that is billable.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Norm efficiency
  </p> </td>
    <td> <p>
   
	 ProjPeriodEmpl.NormEfficiency
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of the number of hours that is utilizable.
  </p> </td>
  </tr>
</table>


## Exchange rates by day

This measure group is based on the BIExchangeRateView view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Exchange rate</p></td>
<td><p>BIExchangeRateView.CrossRate</p></td>
<td><p>Max</p></td>
<td><p>The exchange rate.</p></td>
<td><p>Currency</p>
<p>Date (exchange rate date)</p>
<p>Analysis currency</p></td>
</tr>
</tbody>
</table>


## Calculated measures

The Project accounting cube contains the following calculated measures.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated measure</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Invoiced revenue deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual invoiced revenue.</p></td>
</tr>
<tr class="even">
<td><p>Accrued revenue deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual accrued revenue.</p></td>
</tr>
<tr class="odd">
<td><p>Revenue deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual revenue.</p></td>
</tr>
<tr class="even">
<td><p>Cost deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual costs.</p></td>
</tr>
<tr class="odd">
<td><p>Cost hour deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual hours costs.</p></td>
</tr>
<tr class="even">
<td><p>Cost expense deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual T&amp;E costs.</p></td>
</tr>
<tr class="odd">
<td><p>Cost item deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual item costs.</p></td>
</tr>
<tr class="even">
<td><p>Gross margin deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual gross margin.</p></td>
</tr>
<tr class="odd">
<td><p>WIP cost deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual work in progress costs.</p></td>
</tr>
<tr class="even">
<td><p>WIP sales deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual work in progress sales.</p></td>
</tr>
<tr class="odd">
<td><p>Gross WIP cost deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual gross work in progress costs.</p></td>
</tr>
<tr class="even">
<td><p>WIP invoiced on account deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual work in progress on account.</p></td>
</tr>
<tr class="odd">
<td><p>Net WIP deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual net work in progress.</p></td>
</tr>
<tr class="even">
<td><p>Hours deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual hours.</p></td>
</tr>
<tr class="odd">
<td><p>Consumption deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual consumption costs.</p></td>
</tr>
<tr class="even">
<td><p>Consumption cost hours deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual consumption hours costs.</p></td>
</tr>
<tr class="odd">
<td><p>Consumption cost expense deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual consumption T&amp;E costs.</p></td>
</tr>
<tr class="even">
<td><p>Consumption cost item deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual consumption item costs.</p></td>
</tr>
<tr class="odd">
<td><p>Payroll allocation deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual payroll allocation.</p></td>
</tr>
<tr class="even">
<td><p>Total cost total budget</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual costs.</p></td>
</tr>
<tr class="odd">
<td><p>Deviation total budget</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual revenue.</p></td>
</tr>
<tr class="even">
<td><p>Remaining budget cost1</p></td>
<td><p>Sum</p></td>
<td><p>The remaining forecast costs.</p></td>
</tr>
<tr class="odd">
<td><p>Cash inflow deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual cash inflow.</p></td>
</tr>
<tr class="even">
<td><p>Cash outflow deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual cash outflow.</p></td>
</tr>
<tr class="odd">
<td><p>Net cash flow deviation</p></td>
<td><p>Sum</p></td>
<td><p>The difference between forecast and actual net cash flow.</p></td>
</tr>
<tr class="even">
<td><p>Actual billable utilization</p></td>
<td><p>Sum</p></td>
<td><p>The utilization of employees using the billable calculation method.</p></td>
</tr>
<tr class="odd">
<td><p>Actual efficiency utilization</p></td>
<td><p>Sum</p></td>
<td><p>The utilization of employees using the efficiency calculation method.</p></td>
</tr>
<tr class="even">
<td><p>Budget billable utilization</p></td>
<td><p>Sum</p></td>
<td><p>The forecast utilization of employees using the billable calculation method.</p></td>
</tr>
<tr class="odd">
<td><p>Budget efficiency utilization</p></td>
<td><p>Sum</p></td>
<td><p>The forecast utilization of employees using the efficiency calculation method.</p></td>
</tr>
<tr class="even">
<td><p>Actual efficiency hours ratio</p></td>
<td><p>Sum</p></td>
<td><p>The ratio between actual hours and burden hours using the efficiency calculation method.</p></td>
</tr>
<tr class="odd">
<td><p>Actual billable hours ratio</p></td>
<td><p>Sum</p></td>
<td><p>The ratio between actual hours and burden hours using the billable calculation method.</p></td>
</tr>
<tr class="even">
<td><p>Budget efficiency hours ratio</p></td>
<td><p>Sum</p></td>
<td><p>The ratio between forecast hours and burden hours using the efficiency calculation method.</p></td>
</tr>
<tr class="odd">
<td><p>Budget billable hours ratio</p></td>
<td><p>Sum</p></td>
<td><p>The ratio between forecast hours and burden hours using the efficiency calculation method.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The following sections describe the key performance indicators (KPIs) in the Project accounting cube.

## KPI calculations

The following table lists the KPIs that are associated with the Project accounting cube. You can use the information in the following table to help verify the information in your KPIs.

The KPIs in the Project accounting cube depend on ledger posting types. Ledger posting types specify the ledger accounts to which project transactions are posted.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>KPI</p></th>
<th><p>Calculation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Revenue deviation</p></td>
<td><p>The difference between actual and forecast revenue.</p></td>
</tr>
<tr class="even">
<td><p>Gross margin deviation</p></td>
<td><p>The difference between actual and forecast gross margin.</p></td>
</tr>
<tr class="odd">
<td><p>Net WIP deviation</p></td>
<td><p>The difference between actual and forecast net work in progress.</p></td>
</tr>
<tr class="even">
<td><p>Cash inflow devation</p></td>
<td><p>The difference between actual and forecast cash inflow.</p></td>
</tr>
<tr class="odd">
<td><p>Cash outflow deviation</p></td>
<td><p>The difference between actual and forecast cash outflow.</p></td>
</tr>
<tr class="even">
<td><p>Net cashflow deviation</p></td>
<td><p>The difference between actual and forecast cash inflow less cash outflow.</p></td>
</tr>
</tbody>
</table>


## Role Centers

The following table lists the Role Centers and web parts that display the KPIs associated with the Project accounting cube.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Role Center</p></th>
<th><p>Web parts KPIs</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Project manager</p></td>
<td><p>KPI for project manager:</p>
<ul>
<li><p>Revenue deviation</p></li>
<li><p>Gross margin deviation</p></li>
<li><p>Net WIP deviation</p></li>
<li><p>Cash inflow deviation</p></li>
<li><p>Cash outflow deviation</p></li>
<li><p>Net cash flow deviation</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Security

The Project accounting cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Chief executive officer

  - Chief financial officer

  - Project manager

  - Project supervisor

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

