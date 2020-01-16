---
title: 'Scenario: Automatic settlement and prioritization'
TOCTitle: 'Scenario: Automatic settlement and prioritization'
ms:assetid: a0c9cfe3-e3e9-42fa-991a-64795efa6352
ms:mtpsurl: https://technet.microsoft.com/library/Hh692489(v=AX.60)
ms:contentKeyID: 41702387
author: Khairunj
ms.date: 06/13/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Scenario: Automatic settlement and prioritization 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You have two options when you settle payments with invoices and other transactions. You can manually select the transactions to settle, or Microsoft Dynamics AX can select the transactions automatically by using the automatic settlement functionality. This topic describes how transactions are settled if you select the **Automatic settlement** check box in the **Accounts receivable parameters** form. You can also customize how automatic settlements are processed by using the **Prioritize settlement** check box, the **Use priority for automatic settlements** check box, and the **Manage priority** link. For information about these options, see [Accounts receivable parameters (form)](https://technet.microsoft.com/library/aa576993\(v=ax.60\)).

The way that transactions are automatically settled can differ, depending on the method that you use for automatic settlement. The following methods are available:

  - User-defined settlement priority

  - Default automatic settlement

The following sections describe how transactions are settled for each method.

## Example transactions

The examples of settlements later in this topic are based on the following transactions. All transactions are for customer 2050.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction</p></th>
<th><p>Date</p></th>
<th><p>Amount</p></th>
<th><p>Cash discount terms</p></th>
<th><p>Cash discount date</p></th>
<th><p>Comments</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Invoice 1</p></td>
<td><p>August 15</p></td>
<td><p>100.00</p></td>
<td><p>2%14, Net 30</p></td>
<td><p>August 29</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Invoice 2</p></td>
<td><p>September 1</p></td>
<td><p>250.00</p></td>
<td><p>2%14, Net 30</p></td>
<td><p>September 15</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Invoice 3</p></td>
<td><p>October 15</p></td>
<td><p>500.00</p></td>
<td><p>2% 14/Net 30</p></td>
<td><p>October 29</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Interest note</p></td>
<td><p>October 15</p></td>
<td><p>7.00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>This interest note is for invoice 1 and invoice 2. The amount is calculated as 2 percent interest on amounts that are 30 or more days past due. For example, .02 * (100.00 + 250.00) = 7.00.</p></td>
</tr>
</tbody>
</table>


## User-defined settlement priority

If you select the **Use priority for automatic settlements** check box in the **Accounts receivable parameters** form, the settlement priority that you define in the **Settlement priority** form is used when transactions are selected for automatic settlement. For more information, see [Settlement priority (form)](https://technet.microsoft.com/library/hh208717\(v=ax.60\)). For this example, the following attributes are selected:

  - **Transaction type**
    
      - **Payment fees**
    
      - **Collection letters**
    
      - **Interest notes**
    
      - **Invoices**

  - **Transaction date**, **Ascending**

  - **Voucher**

If you post a payment for 700.00 on October 25, the following transactions are automatically selected for settlement.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Voucher</strong></p></th>
<th><p><strong>Date</strong></p></th>
<th><p><strong>Invoice</strong></p></th>
<th><p><strong>Amount in transaction currency</strong></p></th>
<th><p><strong>Amount to settle</strong></p></th>
<th><p><strong>Balance</strong></p></th>
<th><p><strong>Currency</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Interest note</p></td>
<td><p>10/15/2015</p></td>
<td><p></p></td>
<td><p>7.00</p></td>
<td><p>7.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>Invoice 1</p></td>
<td><p>8/15/2015</p></td>
<td><p>10001</p></td>
<td><p>100.00</p></td>
<td><p>100.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>Invoice 2</p></td>
<td><p>9/1/2015</p></td>
<td><p>10002</p></td>
<td><p>250.00</p></td>
<td><p>250.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>Invoice 3</p></td>
<td><p>10/15/2015</p></td>
<td><p></p></td>
<td><p>500.00</p></td>
<td><p>343.00</p></td>
<td><p>157.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Default automatic settlement

If there is no user-defined settlement priority, transactions are automatically selected for settlement based on the due date. The transactions that are settled must have the same currency as the transaction that they are settled with. If you post a payment for 700.00 on October 25, the following transactions are selected for settlement.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Voucher</strong></p></th>
<th><p><strong>Date</strong></p></th>
<th><p><strong>Invoice</strong></p></th>
<th><p><strong>Amount in transaction currency</strong></p></th>
<th><p><strong>Amount to settle</strong></p></th>
<th><p><strong>Balance</strong></p></th>
<th><p><strong>Currency</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Invoice 1</p></td>
<td><p>8/15/2015</p></td>
<td><p>10001</p></td>
<td><p>100.00</p></td>
<td><p>100.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>Invoice 2</p></td>
<td><p>9/1/2015</p></td>
<td><p>10002</p></td>
<td><p>250.00</p></td>
<td><p>250.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>Invoice 3</p></td>
<td><p>10/15/2015</p></td>
<td><p></p></td>
<td><p>500.00</p></td>
<td><p>350.00</p></td>
<td><p>150.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>Interest note</p></td>
<td><p>10/15/2015</p></td>
<td><p></p></td>
<td><p>7.00</p></td>
<td><p>0.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## See also

[Accounts receivable parameters (form)](https://technet.microsoft.com/library/aa576993\(v=ax.60\))

[About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md)

[Scenario: Settle a customer payment with an invoice](scenario-settle-a-customer-payment-with-an-invoice.md)

[Scenario: Cash discount handling for overpayments](scenario-cash-discount-handling-for-overpayments.md)

[Scenario: Settle a partial customer payment and settle the final payment in full before the discount date](scenario-settle-a-partial-customer-payment-and-settle-the-final-payment-in-full-before-the-discount-date.md)

[Scenario: Settle a partial customer payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-customer-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Settle a partial customer payment that has multiple discount periods](scenario-settle-a-partial-customer-payment-that-has-multiple-discount-periods.md)

[Scenario: Use one customer payment to settle multiple invoices that span multiple discount periods](scenario-use-one-customer-payment-to-settle-multiple-invoices-that-span-multiple-discount-periods.md)

[Scenario: Settle a partial customer payment that has discounts on credit notes](scenario-settle-a-partial-customer-payment-that-has-discounts-on-credit-notes.md)

  


