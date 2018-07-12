---
title: Accounts receivable cube (CustCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack
TOCTitle: Accounts receivable cube (CustCube)
ms:assetid: 8243581b-7aea-4b7c-be3d-d86f94ab7e84
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh781073(v=AX.60)
ms:contentKeyID: 43894472
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Accounts receivable cube (CustCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the Accounts receivable cube to report on customer transactions and accounts receivable.

## Configuration keys

The following configuration keys are required to use all features of the Accounts receivable cube:

  - General ledger (LedgerBasic)

## Tables and views

The Accounts receivable cube uses data from the following tables and views:

  - CustBillingClassification table

  - CustPaymModeTable table

  - CustTrans table

  - CustTransOpen table

  - CustTransTotalSales view

## Measures

The Accounts receivable cube includes the following measure groups.

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
<td><p>Total open customer transaction amount, in accounting currency.</p></td>
<td><p>Company</p>
<p>Customer</p>
<p>Date (last interest date)</p>
<p>Date (due date)</p>
<p>Date (cash discount date)</p>
<p>Date (transaction date)</p>
<p>Date (exchange rate date)</p>
<p>Fiscal period date (transaction date – fiscal calendar)</p>
<p>Fiscal period date (due date – fiscal calendar)</p>
<p>Fiscal period date (cash discount date – fiscal calendar)</p>
<p>Fiscal period date (last interest date – fiscal calendar)</p></td>
</tr>
</tbody>
</table>


## Customer transactions

This measure group is based on the CustTrans table and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
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
   
	 Accounts receivable amount – transaction currency
  </p> </td>
    <td> <p>
   
	 CustTrans.AmountCur
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 Total customer transaction amount, in transaction currency.
  </p> </td>
    <td rowspan="4"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Billing classification
  </p> <p>
   
	 Methods of payment - customer
  </p> <p>
   
	 Customer transaction
  </p> <p>
   
	 Date (due date)
  </p> <p>
   
	 Date (last settlement date)
  </p> <p>
   
	 Date (closed date)
  </p> <p>
   
	 Date (transaction date)
  </p> <p>
   
	 Date (document date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Fiscal period date (last settlement date – fiscal calendar
  </p> <p>
   
	 Fiscal period date (closed date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (transaction date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (document date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (due date – fiscal calendar)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Accounts receivable settled amount – transaction currency
  </p> </td>
    <td> <p>
   
	 CustTrans.SettleAmountCur
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 Total amount of customer transactions that have been settled, in transaction currency.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Accounts receivable amount – accounting currency
  </p> </td>
    <td> <p>
   
	 CustTrans.AmountMST
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 Total customer transaction amount, in accounting currency.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Accounts receivable settled amount – accounting currency
  </p> </td>
    <td> <p>
   
	 CustTrans.SettleAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Total amount of customer transactions that have been settled, in accounting currency.
  </p> </td>
  </tr>
</table>


## Total customer sales

This measure group is based on the CustTransTotalSales view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
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
   
	 Accounts receivable total – accounting currency
  </p> </td>
    <td> <p>
   
	 CustTransTotalSales.AmountMST
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 Total customer sales, in accounting currency.
  </p> </td>
    <td rowspan="4"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Methods of payment - customer
  </p> <p>
   
	 Total customer sales
  </p> <p>
   
	 Date (due date)
  </p> <p>
   
	 Date (last settlement date)
  </p> <p>
   
	 Date (closed date)
  </p> <p>
   
	 Date (transaction date)
  </p> <p>
   
	 Date (document date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Fiscal period date (last settlement date – fiscal calendar
  </p> <p>
   
	 Fiscal period date (closed date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (transaction date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (document date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (due date – fiscal calendar)
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

The Accounts receivable cube does not include any calculated measures.

## Key performance indicators

The Accounts receivable cube does not include any key performance indicators (KPIs).

## Security

The Accounts receivable cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Accountant

  - Accounting manager

  - Accounting supervisor

  - Accounts payable manager

  - Accounts receivable centralized payments clerk

  - Accounts receivable clerk

  - Accounts receivable manager

  - Accounts receivable payments clerk

  - Chief executive officer

  - Chief financial officer

  - Collections agent

  - Collections manager

  - Compliance manager

  - Financial controller

  


