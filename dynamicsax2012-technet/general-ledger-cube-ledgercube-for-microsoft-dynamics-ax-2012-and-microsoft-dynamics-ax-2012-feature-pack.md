---
title: General ledger cube (LedgerCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack
TOCTitle: General ledger cube (LedgerCube)
ms:assetid: 6f4656d7-84fe-49de-9234-e50ef10c7775
ms:mtpsurl: https://technet.microsoft.com/library/Hh781070(v=AX.60)
ms:contentKeyID: 43894469
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# General ledger cube (LedgerCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the General ledger cube to report on ledger accounts and bank accounts.

## Configuration keys

The following configuration keys are required to use all features of the General ledger cube:

  - Bank (Bank)

  - Check (BankCheque)

  - Reporting currency (CurrencySecondaryCurrency)l

  - General ledger (LedgerBasic)

## Tables and views

The General ledger cube uses data from the following tables and views:

  - BankAccountTable table

  - BankAccountTrans table

  - BankChequePaymTrans table

  - BankTransType table

  - BudgetModel table

  - CustTransOpen table

  - VendTransOpen table

  - BudgetTransactionCube view

  - DimensionFocusBalanceCube view

  - GeneralJournalCube view

  - LedgerDerivedFinAttrValueCombinations (This view is used in Microsoft Dynamics AX 2012 Feature Pack.)

  - LedgerDerivedFinHierarchyCategory (This view is used in Microsoft Dynamics AX 2012 Feature Pack.)

  - LedgerDerivedFinHierarchyResults (This view is used in Microsoft Dynamics AX 2012 Feature Pack.)

  - MainAccountCube view

## Measures

The General ledger cube includes the following measure groups.

## Ledger derived financial hierarchy results

This measure group is based on the LedgerDerivedFinHierarchyResults view and includes the following measures.


> [!NOTE]
> <P>This measure group is available in Microsoft Dynamics AX 2012 Feature Pack.</P>



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
<td><p>Ledger derived financial hierarchy results count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of ledger hierarchy results.</p></td>
<td><p>Ledger derived financial attribute value combinations</p>
<p>Derived financial category hierarchy</p>
<p>Ledger derived financial hierarchy results</p>
<p>Company</p></td>
</tr>
</tbody>
</table>


## Open customer transactions

This measure group is based on the CustTransOpen table and includes the following measures.

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
<td><p>Accounts receivable open amount – accounting currency</p></td>
<td><p>CustTransOpen.AmountMST</p></td>
<td><p>Sum</p></td>
<td><p>Accounts receivable open amount, in accounting currency.</p></td>
<td><p>Company</p>
<p>Customer</p>
<p>Date (last interest date)</p>
<p>Date (due date)</p>
<p>Date (cash discount date)</p>
<p>Date (transaction date)</p>
<p>Date (exchange rate date)</p>
<p>Fiscal period date (transaction date – fiscal calendar)</p>
<p>Fiscal period date (due date – fiscal calendar)</p>
<p>Fiscal period date (cash discount date – fiscal date)</p>
<p>Fiscal period date (last interest date – fiscal calendar)</p></td>
</tr>
</tbody>
</table>


## Open vendor transactions

This measure group is based on the VendTransOpen table and includes the following measures.

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
<td><p>Accounts payable open amount – accounting currency</p></td>
<td><p>VendTransOpen.AmountMST</p></td>
<td><p>Sum</p></td>
<td><p>Accounts payable open amount, in accounting currency.</p></td>
<td><p>Company</p>
<p>Date (due date)</p>
<p>Date (cash discount date)</p>
<p>Date (transaction date)</p>
<p>Date (exchange rate date)</p>
<p>Fiscal period date (transaction date – fiscal calendar)</p>
<p>Fiscal period date (due date –fiscal calendar)</p>
<p>Fiscal period date (cash discount date – fiscal date)</p></td>
</tr>
</tbody>
</table>


## Ledger transactions

This measure group is based on the GeneralJournalCube view and includes the following measures.

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
   
	 General ledger amount - accounting currency
  </p> </td>
    <td colspan="1"> <p>
   
	 GeneralJournalCube.AccountingCurrencyAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 General ledger amount, in accounting currency.
  </p> </td>
    <td rowspan="3"> <p>
   
	 Currency
  </p> <p>
   
	 Ledger derived financial attribute value combinations
  </p> <p>
   
	 Derived financial category hierarchy
  </p> <p>
   
	 Company
  </p> <p>
   
	 Chart of accounts
  </p> <p>
   
	 Ledger transaction
  </p> <p>
   
	 Date (transaction date)
  </p> <p>
   
	 Date (acknowledgement date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Fiscal period date (transaction date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (acknowledgement date – fiscal calendar)
  </p> <p>
   
	 Date (document date)
  </p> <p>
   
	 Fiscal period date (document date – fiscal calendar)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 General ledger amount - transaction currency
  </p> </td>
    <td colspan="1"> <p>
   
	 GeneralJournalCube.TransactionCurrencyAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 General ledger amount, in transaction currency.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 General ledger amount - reporting currency
  </p> </td>
    <td colspan="1"> <p>
   
	 GeneralJournalCube.ReportingCurrencyAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 General ledger amount, in reporting currency.
  </p> </td>
  </tr>
</table>


## Ledger budgets

This measure group is based on the BudgetTransactionCube view and includes the following measures.

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
   
	 General ledger budget amount - transaction currency
  </p> </td>
    <td colspan="1"> <p>
   
	 BudgetTransactionCube.TransactionCurrencyAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 General ledger budget amount, in transaction currency.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Currency
  </p> <p>
   
	 Ledger derived financial attribute value combinations
  </p> <p>
   
	 Company
  </p> <p>
   
	 Chart of accounts
  </p> <p>
   
	 Ledger budget model
  </p> <p>
   
	 Ledger budget
  </p> <p>
   
	 Date (transaction date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Fiscal period date (transaction date – fiscal calendar)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 General ledger budget amount - accounting currency
  </p> </td>
    <td colspan="1"> <p>
   
	 BudgetTransactionCube.AccountingCurrencyAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 General ledger budget amount, in accounting currency.
  </p> </td>
  </tr>
</table>


## Ledger balances

This measure group is based on the DimensionFocusBalanceCube view and includes the following measures.

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
   
	 Main account credit amount - reporting currency
  </p> </td>
    <td colspan="1"> <p>
   
	 DimensionFocusBalanceCube.CreditReportingCurrencyAmount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 Main account credit amount, in reporting currency.
  </p> </td>
    <td rowspan="4"> <p>
   
	 Ledger derived financial attribute value combinations
  </p> <p>
   
	 Company
  </p> <p>
   
	 Chart of accounts
  </p> <p>
   
	 Ledger balance
  </p> <p>
   
	 Date (transaction date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Fiscal period date (transaction date – fiscal calendar)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Main account debit amount - accounting currency
  </p> </td>
    <td> <p>
   
	 DimensionFocusBalanceCube.DebitAccountingCurrencyAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Main account debit amount, in accounting currency.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Main account debit amount - reporting currency
  </p> </td>
    <td> <p>
   
	 DimensionFocusBalanceCube.DebitReportingCurrencyAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Main account debit amount, in reporting currency.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Main account credit amount - accounting currency
  </p> </td>
    <td> <p>
   
	 DimensionFocusBalanceCube.CreditAccountingCurrencyAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Main account credit amount, in accounting currency.
  </p> </td>
  </tr>
</table>


## Bank transactions

This measure group is based on the BankAccountTrans table and includes the following measures.

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
   
	 Bank amount - bank currency
  </p> </td>
    <td colspan="1"> <p>
   
	 BankAccountTrans.BankTransAmountCur
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 Total bank transaction amount, in bank currency.
  </p> </td>
    <td rowspan="3"> <p>
   
	 Currency
  </p> <p>
   
	 Ledger derived financial attribute value combinations
  </p> <p>
   
	 Company
  </p> <p>
   
	 Bank account description
  </p> <p>
   
	 Bank transaction type
  </p> <p>
   
	 Bank transaction
  </p> <p>
   
	 Currency (currency – registration currency)
  </p> <p>
   
	 Date (transaction date)
  </p> <p>
   
	 Date (bank statement date)
  </p> <p>
   
	 Date (acknowledgement date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Fiscal period date (transaction date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (bank statement date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (acknowledgement date – fiscal calendar)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Bank amount - transaction currency
  </p> </td>
    <td colspan="1"> <p>
   
	 BankAccountTrans.AmountCur
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 Total bank transaction amount, in transaction currency.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Bank amount - accounting currency
  </p> </td>
    <td colspan="1"> <p>
   
	 BankAccountTrans.AmountMst
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 Total bank transaction amount, in accounting currency.
  </p> </td>
  </tr>
</table>


## Bank payment transactions

This measure group is based on the BankChequePaymTrans table and includes the following measures.

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
<td><p>Bank payment amount - transaction currency</p></td>
<td><p>BankChequePaymTrans.PaymentAmountCur</p></td>
<td><p>Sum</p></td>
<td><p>Bank payment amount, in transaction currency.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Bank account description</p>
<p>Date (transaction date)</p>
<p>Date (invoice transaction date)</p>
<p>Date (invoice date)</p>
<p>Fiscal period date (transaction date – fiscal calendar)</p>
<p>Fiscal period date (invoice date – fiscal calendar)</p>
<p>Fiscal period date (invoice transaction date – fiscal calendar)</p></td>
</tr>
</tbody>
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

The General ledger cube contains the following calculated measures.

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
<td><p>General ledger sales - accounting currency</p></td>
<td><p>No accumulation</p></td>
<td><p>Sales for your organization in accounting currency.</p></td>
</tr>
<tr class="even">
<td><p>General ledger sales returns and discounts - accounting currency</p></td>
<td><p>No accumulation</p></td>
<td><p>Sales, returns, and discounts for your organization in accounting currency.</p></td>
</tr>
<tr class="odd">
<td><p>General ledger actuals total - accounting currency</p></td>
<td><p>No accumulation</p></td>
<td><p>Total actuals for your organization.</p></td>
</tr>
<tr class="even">
<td><p>General ledger sales total - accounting currency</p></td>
<td><p>No accumulation</p></td>
<td><p>Total sales for your organization in accounting currency.</p></td>
</tr>
<tr class="odd">
<td><p>General ledger budget total - accounting currency</p></td>
<td><p>No accumulation</p></td>
<td><p>Total budget amounts for your organization in accounting currency.</p></td>
</tr>
<tr class="even">
<td><p>General ledger cost of goods sold - accounting currency</p></td>
<td><p>No accumulation</p></td>
<td><p>Cost of goods sold for your organization in accounting currency.</p></td>
</tr>
<tr class="odd">
<td><p>General ledger gross profit - accounting currency</p></td>
<td><p>No accumulation</p></td>
<td><p>Gross profit for your organization in accounting currency.</p></td>
</tr>
<tr class="even">
<td><p>General ledger accounts receivable - accounting currency</p></td>
<td><p>Sum</p></td>
<td><p>The accounts receivable balance for the organization.</p></td>
</tr>
<tr class="odd">
<td><p>General ledger accounts payable - accounting currency</p></td>
<td><p>Sum</p></td>
<td><p>The accounts payable balance for the organization.</p></td>
</tr>
<tr class="even">
<td><p>Main account net amount - accounting currency</p></td>
<td><p>No accumulation</p></td>
<td><p>Ledger balance net amount for your organization in accounting currency.</p></td>
</tr>
<tr class="odd">
<td><p>Main account net amount - reporting currency</p></td>
<td><p>No accumulation</p></td>
<td><p>Ledger balance net amount for your organization in reporting currency.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The following sections describe the key performance indicators (KPIs) in the General ledger cube.

## KPI calculations

The KPIs in the General ledger cube depend on account categories. For information about account categories, see [Main account categories and analysis cubes](main-account-categories-and-analysis-cubes.md).

An asterisk (\*) indicates that the KPI calculations use accumulated amounts. Accumulated amounts, such as some period-to-date amounts, are not stored in the Microsoft Dynamics AX database. For example, to calculate a period-to-date amount, all the transactions from the beginning of the fiscal calendar to the end of the previous period are totaled. Then all the amounts from the beginning of the fiscal calendar to the current date are totaled. The difference between these two amounts is the period-to-date amount.

You can use the information in the following table to help verify the information in your KPIs. Export your chart of accounts to Office Excel and verify that the accounts that should be included in the KPIs are assigned to the correct ledger account category.

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
<td><p>Accounts payable turnover *</p></td>
<td><p>[Cost of Goods Sold (Reference ID = 35) + (Ending Inventory (Reference ID = 5) for period - Beginning Inventory (Reference ID = 5) for period)] / [Beginning Accounts Payable (Reference ID = 15) + Ending Accounts Payable (Reference ID = 15) / 2]</p>
<div class="alert">

> [!NOTE]
> <P>* Only the Inventory and Accounts Payable parts of this KPI are accumulated.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Accounts receivable turnover *</p></td>
<td><p>[Sales (Reference ID = 33) *-1] - Sales Returns and Discounts (Reference ID = 34) / [Beginning Accounts Receivable (Reference ID = 4) + Ending Accounts Receivable (Reference ID = 4) / 2]</p>
<div class="alert">

> [!NOTE]
> <P>* Only the Accounts Receivable part of this KPI is accumulated.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Average days to pay *</p></td>
<td><p>Ending Accounts Payable (Reference ID = 15) balance for the period / [Cost of Goods Sold (Reference ID = 35) + (Ending Inventory (Reference ID = 5) for the period - Beginning Inventory (Reference ID=5) for the period)] * Number of days in the period</p>
<div class="alert">

> [!NOTE]
> <P>* Only the Accounts Payable and Inventory parts of this KPI are accumulated.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Average collection period *</p></td>
<td><p>Accounts Receivable (Reference ID = 4) / Average Daily Sales (Average Daily Sales = Total Sales for the year to date (Reference ID = 33) *-1 / Number of days in fiscal year to date)</p>
<div class="alert">

> [!NOTE]
> <P>* Only the Accounts Receivable part of this KPI is accumulated.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Cash position *</p></td>
<td><p>Cash (Reference ID = 1) + Cash Equivalents (Reference ID = 2)</p>
<div class="alert">

> [!NOTE]
> <P>* Accumulation applies to all calculations.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Cash ratio *</p></td>
<td><p>Cash Equivalents (Reference ID = 2) + Cash (Reference ID = 1) / (Accounts Payable (Reference ID = 15) + Notes Payable (Reference ID = 16) + Current Maturities on Long Term Debt (Reference ID = 17) + Taxes Payable (Reference ID = 18) + Interest Payable (Reference ID = 19) + Dividends Payable (Reference ID = 20) + Leases Payable (Current) (Reference ID = 21) + Sinking Fund Payable (Current) (Reference ID = 22) + Other Current Liabilities (Reference ID = 23))</p>
<div class="alert">

> [!NOTE]
> <P>* Accumulation applies to all calculations.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Cost of goods sold</p></td>
<td><p>Cost of Goods Sold (Reference ID = 35)</p></td>
</tr>
<tr class="even">
<td><p>Current ratio *</p></td>
<td><p>[Cash (Reference ID = 1) + Cash Equivalents (Reference ID = 2) + Short Term Investments (Reference ID = 3) + Accounts Receivable (Reference ID = 4) + Inventory (Reference ID = 5) + Notes Receivables (Reference ID = 6) + Work in Process (Reference ID = 7) + Prepaid Expenses (Reference ID = 8) + Other Current Assets (Reference ID = 9) + Inventory (Reference ID = 5)] / [Accounts Payable (Reference ID = 15) + Notes Payable (Reference ID = 16) + Current Maturities on Long Term Debt (Reference ID = 17) + Taxes Payable (Reference ID = 18) + Interest Payable (Reference ID = 19) + Dividends Payable (Reference ID = 20) + Leases Payable (Current) (Reference ID = 21) + Sinking Fund Payable (Current) (Reference ID = 22) + Other Current Liabilities (Reference ID = 23)]</p>
<div class="alert">

> [!NOTE]
> <P>* Accumulation applies to all calculations.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Debt to equity *</p></td>
<td><p>Accounts Payable (Reference ID = 15) + Notes Payable (Reference ID = 16) + Current Maturities on Long Term Debt (Reference ID = 17) + Taxes Payable (Reference ID = 18) + Interest Payable (Reference ID = 19) + Dividends Payable (Reference ID = 20) + Leases Payable (Current) (Reference ID = 21) + Sinking Fund Payable (Current) (Reference ID = 22) + Other Current Liabilities (Reference ID = 23) + Long Term Debt (Reference ID = 24) / Common Stock (Reference ID = 25) + Preferred Stock (Reference ID = 26) + Additional Paid in Capital: Common (Reference ID = 27) + Additional Paid in Capital: Preferred (Reference ID = 28) + Retained Earnings (Reference ID = 29) + Treasury Stock (Reference ID = 30)</p>
<div class="alert">

> [!NOTE]
> <P>* Accumulation applies to all calculations.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Debt to total assets *</p></td>
<td><p>[Accounts Payable (Reference ID = 15) + Notes Payable (Reference ID = 16) + Current Maturities on Long Term Debt (Reference ID = 17) + Taxes Payable (Reference ID = 18) + Interest Payable (Reference ID = 19) + Dividends Payable (Reference ID = 20) + Leases Payable (Current) (Reference ID = 21) + Sinking Fund Payable (Current) (Reference ID = 22) + Other Current Liabilities (Reference ID = 23) + Long Term Debt (Reference ID = 24)] / [Cash (Reference ID = 1) + Cash Equivalents (Reference ID = 2) + Short Term Investments (Reference ID = 3) + Accounts Receivable (Reference ID = 4) + Inventory (Reference ID = 5) + Notes Receivables (Reference ID = 6) + Work in Process (Reference ID = 7) + Prepaid Expenses (Reference ID = 8) + Other Current Assets (Reference ID = 9) + Long Term Investments (Reference ID = 10) + Property Plant and Equipment (Reference ID = 11) + Accumulated Depreciation (Reference ID = 12) + Intangible Assets (Reference ID = 13) + Other Assets (Reference ID = 14)]</p>
<div class="alert">

> [!NOTE]
> <P>* Accumulation applies to all calculations.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Gross profit</p></td>
<td><p>[Sales (Reference ID = 33) *-1] - Sales Returns and Discounts Reference ID = 34) - Cost of Goods Sold (Reference ID = 35)</p>
<div class="alert">

> [!NOTE]
> <P>The Sales account category is multiplied by -1 to reflect the sales amount as a positive value.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Gross profit margin</p></td>
<td><p>[Sales (Reference ID = 33) *-1] - Sales Returns and Discounts (Reference ID = 34) - Cost of Goods Sold (Reference ID = 35) / [Sales (Reference ID = 33) *-1] - Sales Returns and Discounts (Reference ID = 34))</p></td>
</tr>
<tr class="odd">
<td><p>Inventory turnover *</p></td>
<td><p>Cost of Goods Sold (Reference ID = 35) / [Beginning Inventory (Reference ID = 5) + Ending Inventory (Reference = 5) / 2]</p>
<div class="alert">

> [!NOTE]
> <P>* Only the Inventory part of this KPI is accumulated.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Net income</p></td>
<td><p>Result A - Result B</p>
<p>Result A = [Sales (Reference ID = 33) + Other Income (Reference ID = 48) + Sales Returns and Discounts (Reference ID = 34)] *-1</p>
<p>Result B = Cost of Goods Sold (Reference ID = 35) + Selling Expense (Reference ID = 36) + Administrative Expense (Reference ID = 37) + Manufacturing Expense (Reference ID = 38) + Travel and Entertainment Expenses (Reference ID = 39) + Project Operation Expenses (Reference ID = 40) + Salaries Expense (Reference ID = 41 ) + Other Employee Expenses (Reference ID = 42) + Interest Expense (Reference ID = 43) + Tax Expense (Reference ID = 44) + Depreciation Expense (Reference ID = 45) + Income Tax Expense (Reference ID = 46) + Other Expenses (Reference ID = 47)</p></td>
</tr>
<tr class="odd">
<td><p>Quick ratio *</p></td>
<td><p>[Cash (Reference ID =1) + Cash Equivalents (Reference ID = 2) + Short Term Investments (Reference ID = 3) + Accounts Receivable (Reference ID = 4) + Notes Receivables (Reference ID = 6)] / (Accounts Payable (Reference ID = 15) + Notes Payable (Reference ID = 16) + Current Maturities on Long Term Debt (Reference ID = 17) + Taxes Payable (Reference ID = 18) + Interest Payable (Reference ID=19) + Dividends Payable (Reference ID = 20) + Leases Payable (Current) (Reference ID=21) + Sinking Fund Payable (Current) (Reference ID = 22) + Other Current Liabilities (Reference ID = 23)</p>
<div class="alert">

> [!NOTE]
> <P>* Accumulation applies to all calculations.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Return on total assets *</p></td>
<td><p>[Sales (Reference ID = 33) + Other Income (Reference ID = 48) + Gain or Loss on Asset Disposal (Reference ID = 51) *-1] - Sales Returns and Discounts (Reference ID = 34) - Cost of Goods Sold (Reference ID = 35) - Selling Expense (Reference ID = 36) - Administrative Expense (Reference ID = 37) - Manufacturing Expense (Reference ID = 38) - Travel and Entertainment Expenses (Reference ID = 39 ) - Project Operation Expense (Reference ID = 40) - Salaries Expense (Reference ID = 41) - Other Employee Expenses (Reference ID = 42) - Depreciation Expense (Reference ID = 45) - Other Expenses (Reference ID = 47) - Amortization of Intangible Assets (Reference ID = 52) / Cash (Reference ID = 1) + Cash Equivalents (Reference ID = 2) + Short Term Investments (Reference ID = 3) + Accounts Receivable (Reference ID = 4) + Inventory (Reference ID = 5) + Notes Receivables (Reference ID = 6) + Work in Process (Reference ID = 7) + Prepaid Expenses (Reference ID = 8) + Other Current Assets (Reference ID = 9) + Long Term Investments (Reference ID = 10) + Property Plant and Equipment (Reference ID = 11) + Accumulated Depreciation (Reference ID = 12) + Intangible Assets (Reference ID = 13) + Other Assets (Reference ID = 14)</p>
<div class="alert">

> [!NOTE]
> <P>Reference ID 51 is included only if the balance of the accounts in that account category is negative. Otherwise it is excluded. * Only the total assets (Reference ID 1 through 14) part of this KPI is accumulated.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Revenue budget variance</p></td>
<td><p>Sum of budget amounts for the period selected for the accounts / Sum of actual balances for revenue accounts for the same time period = Variance. The result is displayed as a percentage. The following ledger account categories are included in the sum of the budget amounts and in the sum of the actual amounts: Sales (Reference ID = 33) + Other Income (Reference ID = 48) + Sales Returns and Discounts (Reference ID = 34) + Gain/Loss on Asset Disposal (Reference ID = 51)</p>
<div class="alert">

> [!NOTE]
> <P>If necessary, the amounts for each account category are summed by dimension combination to compare the budget versus actual amounts by department, cost center, and so on. Reference ID 51 is included only if the balance of the accounts in that account category is negative. Otherwise it is excluded.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Times interest earned</p></td>
<td><p>[Sales (Reference ID = 33) + Other Income (Reference ID = 48) + Gain/Loss on Asset Disposal (Reference ID = 51)) *-1] - Sales Returns and Discounts (Reference ID = 34) - Cost of Goods Sold (Reference ID = 35) - Selling Expense (Reference ID = 36) - Administrative Expense (Reference ID - 37) - Manufacturing Expense (Reference ID - 38) - Travel and Entertainment Expenses (Reference ID - 39 ) - Project Operation Expense (Reference ID = 40) - Salaries Expense (Reference ID = 41) - Other Employee Expenses (Reference ID - 42) - Depreciation Expense (Reference ID = 45) - Other Expenses (Reference ID = 47) - Amortization of Intangible Assets (Reference ID = 52) / Interest Expense (Reference ID = 43)</p>
<div class="alert">

> [!NOTE]
> <P>Reference ID 51 is included only if the balance of the accounts in that account category is negative. Otherwise it is excluded.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Total expenses</p></td>
<td><p>Cost of Goods Sold (Reference ID = 35) + Selling Expense (Reference ID = 36) + Administrative Expense (Reference ID = 37) + Manufacturing Expense (Reference ID = 38) + Travel and Entertainment Expense (Reference ID = 39) + Project Operation Expenses (Reference ID = 40) + Salaries Expense (Reference ID = 41 ) + Other Employee Expense (Reference ID = 42) + Interest Expense (Reference ID = 43) + Tax Expense (Reference ID = 44) + Depreciation Expense (Reference ID = 45) + Income Tax Expense (Reference ID = 46) + Other Expenses (Reference ID = 47) + Amortization of Intangible Assets (Reference ID = 52) + Gain/Loss on Asset Disposal (Reference ID = 51)</p>
<div class="alert">

> [!NOTE]
> <P>Reference ID 51 is included only if the balance of the accounts in that account category is positive. Otherwise it is excluded.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Total revenue</p></td>
<td><p>[Sales (Reference ID = 33) + Other Income (Reference ID = 48) + Sales Returns and Discounts (Reference ID = 34) + Gain/Loss on Asset Disposal (Reference ID = 51)] *-1</p>
<div class="alert">

> [!NOTE]
> <P>Reference ID 51 is included only if the balance of the accounts in that account category is negative. Otherwise it is excluded.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Earnings before income tax</p></td>
<td><p>(Sales (Reference ID = 33) + Other Income (Reference ID = 48) + Sales Returns and Discounts (Reference ID = 34)) *-1 ) - (COGS (Reference ID = 35) + Selling Expense (Reference ID = 36) + Admin Expense (Reference ID = 37) + Manuf Expense (Reference ID = 38) + T&amp;E Expense (Reference ID = 39) + Project and Operation Expense (Reference ID = 40) + Saleries Expense (Reference ID = 41) + Other Employee Expenses (Reference ID = 42) + Interst Expense (Reference ID = 43) + Tax Expense (Reference ID = 44) + Depreciation Expense (Reference ID = 45) + Income Tax Expense (Reference ID = 46) + Other Expenses (Reference ID = 47) )</p></td>
</tr>
<tr class="even">
<td><p>Expense budget variance</p></td>
<td><p>Sum budget amounts for the period selected for the accounts that have the following AccountCategoryRef: Cost of Goods Sold (Reference ID = 35) + Selling Expense (Reference ID = 36) + Admin Expense (Reference ID = 37) + Manuf Expense (Reference ID = 38) + Travel and Enter Expense (Reference ID = 39) + Project Expense (Reference ID = 40) + Salaries Expense (Reference ID = 41 ) + Other Employee Expenses (Reference ID = 42) + Interest Expense (Reference ID = 43) + Tax Expense (Reference ID = 44) + Depr Expense (Reference ID = 45) + Income Tax Expene (Reference ID = 46) + Other Expenses (Reference ID = 47) + Amortization of Intangible Assets (Reference ID = 52) + Gain/Loss on Asset Disposal (Reference ID = 51) / Sum of actual balances for expense accounts for the same time period: Cost of Goods Sold (Reference ID = 35) + Selling Expense (Reference ID = 36) + Admin Expense (Reference ID = 37) + Manu Expense (Reference ID = 38) + Travel and Enter Expense (Reference ID = 39) + Project Expenses (Reference ID = 40) + Salaries Expense (Reference ID = 41 ) + Other Employee Expenses (Reference ID = 42) + Interest Expense (Reference ID = 43) + Tax Expense (Reference ID = 44) + Depr Expense (Reference ID = 45) + Income Tax Expense (Reference ID = 46) + Other Expenses (Reference ID = 47) + Amortization of Intangible Assets (Reference ID = 52) + Gain/Loss on Asset Disposal (Reference ID = 51)</p>
<div class="alert">

> [!NOTE]
> <P>Reference ID 51 is included only if the balance of the accounts in that account category is positive. Otherwise it is excluded.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Accounts payable</p></td>
<td><p>Accounts Payable (Reference ID = 15)</p></td>
</tr>
<tr class="even">
<td><p>Notes payable</p></td>
<td><p>Notes Payable (Reference ID = 16)</p></td>
</tr>
<tr class="odd">
<td><p>Interest payable</p></td>
<td><p>Interest Payable (Reference ID = 19)</p></td>
</tr>
<tr class="even">
<td><p>Other liabilities</p></td>
<td><p>Current Maturities on Long Term Debt (Reference ID = 17) + Taxes Payable (Reference ID = 18) + Leases Payable (Current) (Reference ID = 21) + Sinking Fund Payable (Current) (Reference ID = 22) + Other Current Liabilities (Reference ID = 23) + Dividends Payable (Reference ID = 20)</p></td>
</tr>
<tr class="odd">
<td><p>Long-term debt</p></td>
<td><p>Long Term Debt (Reference ID = 24)</p></td>
</tr>
<tr class="even">
<td><p>Cash and cash equivalents</p></td>
<td><p>Cash (Reference ID = 1) + Cash Equivalents (Reference ID = 2)</p></td>
</tr>
<tr class="odd">
<td><p>Short-term investment</p></td>
<td><p>Short Term Investments (Reference ID = 3)</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable</p></td>
<td><p>Accounts Receivable (Reference ID = 4)</p></td>
</tr>
<tr class="odd">
<td><p>Notes receivable</p></td>
<td><p>Notes Receivable (Reference ID = 6)</p></td>
</tr>
<tr class="even">
<td><p>Long-term investment</p></td>
<td><p>Long Term Investments (Reference ID = 10)</p></td>
</tr>
<tr class="odd">
<td><p>Inventory and WIP</p></td>
<td><p>Inventory (Reference ID = 5) + Work in progress (Reference ID = 7)</p></td>
</tr>
<tr class="even">
<td><p>Other org assets</p></td>
<td><p>Prepaid Expenses (Reference ID = 8) + Other Current Assets (Reference ID = 9) + Property Plant and Equipment (Reference ID = 11) + Accumulated Depreciation (Reference ID = 12) + Intangible Assets (Reference ID = 13) + Other Assets (Reference ID = 14)</p></td>
</tr>
<tr class="odd">
<td><p>Net assets</p></td>
<td><p>(Sales (Reference ID = 33) + Other Income (Reference ID = 48) + Sales Returns and Discounts (Reference ID = 34) + Gain/loss on asset disposal (Reference ID = 51)) *-1 — (COGS (Reference ID = 35) + Selling Expense (Reference ID = 36) + Admin Expense (Reference ID = 37) + Manuf Expense (Reference ID = 38) + T&amp;E Expense (Reference ID = 39) + Project and Operation Expense (Reference ID = 40) + Salaries Expense (Reference ID = 41) + Other Employee Expenses (Reference ID = 42) + Interest Expense (Reference ID = 43) + Tax Expense (Reference ID = 44) + Depreciation Expense (Reference ID = 45) + Income Tax Expense (Reference ID = 46) + Other Expenses (Reference ID = 47) + Amortization of intangible assets (Reference ID = 52) Gain/loss on asset disposal (Reference ID = 51))</p>
<div class="alert">

> [!NOTE]
> <P>Reference ID 51 is included only if the balance of the accounts in that account category is negative. Otherwise it is excluded.</P>


</div>
<div class="alert">

> [!NOTE]
> <P>This KPI is available in Microsoft Dynamics AX 2012 Feature Pack.</P>


</div></td>
</tr>
</tbody>
</table>


## Role Centers

The following table lists the Role Centers and web parts that display the KPIs associated with the General ledger cube.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Role Center</p></th>
<th><p>Web parts and KPIs</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Credit and collections manager</p></td>
<td><p>Operational efficiency (displayed by default):</p>
<ul>
<li><p>Average collection period</p></li>
<li><p>Accounts receivable turnover</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Controller</p></td>
<td><p>Profitability analysis (displayed by default):</p>
<ul>
<li><p>Revenue</p></li>
<li><p>Expenses</p></li>
<li><p>Cost of goods sold</p></li>
<li><p>Gross profit</p></li>
<li><p>Gross profit margin</p></li>
<li><p>Net income</p></li>
</ul>
<p>Investment analysis:</p>
<ul>
<li><p>Return on total assets</p></li>
</ul>
<p>Short-term solvency:</p>
<ul>
<li><p>Cash ratio</p></li>
<li><p>Cash position</p></li>
<li><p>Current ratio</p></li>
<li><p>Quick ratio</p></li>
</ul>
<p>Operational efficiency:</p>
<ul>
<li><p>Accounts receivable turnover</p></li>
<li><p>Average days to pay</p></li>
<li><p>Accounts payable turnover</p></li>
<li><p>Revenue budget variance</p></li>
<li><p>Expense budget variance</p></li>
<li><p>Inventory turnover</p></li>
</ul>
<p>Revised long term solvency:</p>
<ul>
<li><p>Debt to equity</p></li>
<li><p>Debt to total assets</p></li>
<li><p>Times interest earned</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>CFO</p></td>
<td><p>Profitability analysis (displayed by default):</p>
<ul>
<li><p>Revenue</p></li>
<li><p>Expenses</p></li>
<li><p>Cost of goods sold</p></li>
<li><p>Gross profit</p></li>
<li><p>Gross profit margin</p></li>
<li><p>Net income</p></li>
</ul>
<p>Investment analysis:</p>
<ul>
<li><p>Return on total assets</p></li>
</ul>
<p>Short-term solvency:</p>
<ul>
<li><p>Cash ratio</p></li>
<li><p>Cash position</p></li>
<li><p>Current ratio</p></li>
<li><p>Quick ratio</p></li>
</ul>
<p>Operational efficiency:</p>
<ul>
<li><p>Accounts receivable turnover</p></li>
<li><p>Average days to pay</p></li>
<li><p>Accounts payable turnover</p></li>
<li><p>Revenue budget variance</p></li>
<li><p>Expense budget variance</p></li>
<li><p>Inventory turnover</p></li>
</ul>
<p>Long-term solvency:</p>
<ul>
<li><p>Debt to equity</p></li>
<li><p>Debt to total assets</p></li>
<li><p>Times interest earned</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Account manager</p></td>
<td><p>Profitability analysis (displayed by default):</p>
<ul>
<li><p>Revenue</p></li>
<li><p>Expenses</p></li>
<li><p>Cost of goods sold</p></li>
<li><p>Gross profit</p></li>
<li><p>Gross profit margin</p></li>
<li><p>Net income</p></li>
</ul>
<p>Investment analysis:</p>
<ul>
<li><p>Return on total assets</p></li>
</ul>
<p>Short-term solvency:</p>
<ul>
<li><p>Cash ratio</p></li>
<li><p>Cash position</p></li>
<li><p>Current ratio</p></li>
<li><p>Quick ratio</p></li>
</ul>
<p>Operational efficiency:</p>
<ul>
<li><p>Accounts receivable turnover</p></li>
<li><p>Average days to pay</p></li>
<li><p>Accounts payable turnover</p></li>
<li><p>Inventory turnover</p></li>
<li><p>Revenue budget variance</p></li>
<li><p>Expense budget variance</p></li>
</ul>
<p>Long-term solvency:</p>
<ul>
<li><p>Debt to equity</p></li>
<li><p>Debt to total assets</p></li>
<li><p>Times interest earned</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Accountant</p></td>
<td><p>Operational efficiency (displayed by default):</p>
<ul>
<li><p>Accounts receivable turnover</p></li>
<li><p>Average days to pay</p></li>
<li><p>Accounts payable turnover</p></li>
<li><p>Inventory turnover</p></li>
<li><p>Revenue budget variance</p></li>
<li><p>Expense budget variance</p></li>
</ul>
<p>Profitability analysis:</p>
<ul>
<li><p>Revenue</p></li>
<li><p>Expenses</p></li>
<li><p>Cost of goods sold</p></li>
<li><p>Gross profit</p></li>
<li><p>Gross profit margin</p></li>
<li><p>Net income</p></li>
</ul>
<p>Investment analysis:</p>
<ul>
<li><p>Return on total assets</p></li>
</ul>
<p>Revised short-term solvency:</p>
<ul>
<li><p>Cash ratio</p></li>
<li><p>Cash position</p></li>
<li><p>Current ratio</p></li>
<li><p>Quick ratio</p></li>
</ul>
<p>Long-term solvency:</p>
<ul>
<li><p>Debt to equity</p></li>
<li><p>Debt to total assets</p></li>
<li><p>Times interest earned</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Treasurer</p></td>
<td><p>Treasurer asset analysis (displayed by default):</p>
<ul>
<li><p>Cash and cash equivalents</p></li>
<li><p>Short-term investments</p></li>
<li><p>Accounts receivable</p></li>
<li><p>Notes receivable</p></li>
<li><p>All other org. assets</p></li>
<li><p>Long-term investments</p></li>
<li><p>Return on total assets</p></li>
<li><p>Inventory and work in progress</p></li>
</ul>
<p>Profitability analysis:</p>
<ul>
<li><p>Revenue</p></li>
<li><p>Expenses</p></li>
<li><p>Cost of goods sold</p></li>
<li><p>Gross profit</p></li>
<li><p>Gross profit margin</p></li>
<li><p>Net income</p></li>
</ul>
<p>Investment analysis:</p>
<ul>
<li><p>Return on total assets</p></li>
</ul>
<p>Short-term solvency:</p>
<ul>
<li><p>Cash ratio</p></li>
<li><p>Cash position</p></li>
<li><p>Current ratio</p></li>
<li><p>Quick ratio</p></li>
</ul>
<p>Investment analysis:</p>
<ul>
<li><p>Return on total assets</p></li>
</ul>
<p>Operational efficiency</p>
<ul>
<li><p>Accounts receivable turnover</p></li>
<li><p>Average days to pay</p></li>
<li><p>Accounts payable turnover</p></li>
<li><p>Revenue budget variance</p></li>
<li><p>Expense budget variance</p></li>
<li><p>Inventory turnover</p></li>
</ul>
<p>Long-term solvency:</p>
<ul>
<li><p>Debt to equity</p></li>
<li><p>Debt to total assets</p></li>
<li><p>Times interest earned</p></li>
</ul>
<p>Treasurer liability analysis:</p>
<ul>
<li><p>Accounts payable</p></li>
<li><p>Notes payable</p></li>
<li><p>Interest payable</p></li>
<li><p>Other liabilities</p></li>
<li><p>Long-term debt</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Security

The General ledger cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Accountant

  - Accounting manager

  - Accounting supervisor

  - Accounts payable centralized payments clerk

  - Accounts payable clerk

  - Accounts payable manager

  - Accounts payable payments clerk

  - Accounts receivable clerk

  - Accounts receivable manager

  - Accounts receivable payments clerk

  - Accounts receivable centralized payments clerk

  - Budget clerk

  - Budget manager

  - Chief executive officer

  - Chief financial officer

  - Collections agent

  - Collections manager

  - Compliance manager

  - Financial controller

  - Treasurer

  


