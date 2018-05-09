---
title: 'Scenario: Settle a partial customer payment that has multiple discount periods'
TOCTitle: 'Scenario: Settle a partial customer payment that has multiple discount periods'
ms:assetid: e97ec73f-21aa-4e63-9e8e-75a8a20a5ab7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh545536(v=AX.60)
ms:contentKeyID: 37832546
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Scenario: Settle a partial customer payment that has multiple discount periods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fabrikam offers customer 4031 two cash discount periods. The customer receives a 2 percent discount if the invoice is paid in five days, and a 1 percent discount if the invoice is paid in 14 days. For information about these setup parameters, see [About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md) and [Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\)).

## Invoice for 1,000.00 on June 25

On June 25, Arnie enters and posts an invoice for 1,000.00 for customer 4031. When he reviews the cash discounts for this invoice, Arnie sees that customer 4031 receives a 20.00 discount if the invoice is paid by June 30. If the invoice is paid by July 9, the customer receives a 10.00 discount.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Cash discount date</strong></p></th>
<th><p><strong>Cash discount amount</strong></p></th>
<th><p><strong>Amount in transaction currency</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>6/30/2015</p></td>
<td><p>20.00</p></td>
<td><p>980.00</p></td>
</tr>
<tr class="even">
<td><p>7/9/2015</p></td>
<td><p>10.00</p></td>
<td><p>990.00</p></td>
</tr>
<tr class="odd">
<td><p>7/25/2015</p></td>
<td><p>0.00</p></td>
<td><p>1,000.00</p></td>
</tr>
</tbody>
</table>


Arnie can view this transaction in the **Customer transactions** form. (Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select customer 4031. On the **Action Pane**, click **Transactions**.)

<table>
<colgroup>
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Voucher</strong></p></th>
<th><p><strong>Transaction type</strong></p></th>
<th><p><strong>Date</strong></p></th>
<th><p><strong>Invoice</strong></p></th>
<th><p><strong>Amount in transaction currency</strong> debit</p></th>
<th><p><strong>Amount in transaction currency</strong> credit</p></th>
<th><p><strong>Balance</strong></p></th>
<th><p><strong>Currency</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>FTI-10030</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10030</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Payment for 294.00 on June 28

Customer 4031 wants to settle 300.00 of this invoice on June 28, which is in the first discount period. The customer will pay 294.00 and take a 6.00 discount. In the **Settle open transactions** form, the **Cash discount amount** value is 20.00, and the **Cash discount amount to take** value is 6.00.

<table style="width:100%;">
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 10%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Mark</strong></p></th>
<th><p><strong>Use cash discount</strong></p></th>
<th><p><strong>Voucher</strong></p></th>
<th><p><strong>Account</strong></p></th>
<th><p><strong>Date</strong></p></th>
<th><p><strong>Due date</strong></p></th>
<th><p><strong>Invoice</strong></p></th>
<th><p><strong>Amount in transaction currency</strong></p></th>
<th><p><strong>Currency</strong></p></th>
<th><p><strong>Amount to settle</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>FTI-10030</p></td>
<td><p>4031</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10030</p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
<td><p>294.00</p></td>
</tr>
</tbody>
</table>


Discount information is shown at the bottom of the **Settle open transactions** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Cash discount date</strong></p></td>
<td><p>6/30/2015</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash discount amount</strong></p></td>
<td><p>20.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Use cash discount</strong></p></td>
<td><p>Normal</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash discount taken</strong></p></td>
<td><p>0.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash discount amount to take</strong></p></td>
<td><p>6.00</p></td>
</tr>
</tbody>
</table>


After Arnie posts the payment, the invoice balance is 700.00.

## Payment for 693.00 on July 8

On July 8, the customer pays the rest of the invoice amount. A 7.00 discount, or 1 percent, is taken, because the payment was made in the second discount period.

<table style="width:100%;">
<colgroup>
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 9%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Mark</strong></p></th>
<th><p><strong>Use cash discount</strong></p></th>
<th><p><strong>Voucher</strong></p></th>
<th><p><strong>Account</strong></p></th>
<th><p><strong>Date</strong></p></th>
<th><p><strong>Due date</strong></p></th>
<th><p><strong>Invoice</strong></p></th>
<th><p><strong>Amount in transaction currency</strong> debit</p></th>
<th><p><strong>Amount in transaction currency</strong> credit</p></th>
<th><p><strong>Currency</strong></p></th>
<th><p><strong>Amount to settle</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>FTI-10030</p></td>
<td><p>4031</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10030</p></td>
<td><p>700.00</p></td>
<td><p></p></td>
<td><p>USD</p></td>
<td><p>693.00</p></td>
</tr>
</tbody>
</table>


Discount information is shown at the bottom of the **Settle open transactions** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Cash discount date</strong></p></td>
<td><p>7/09/2015</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash discount amount</strong></p></td>
<td><p>30.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Use cash discount</strong></p></td>
<td><p>Normal</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash discount taken</strong></p></td>
<td><p>6.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash discount amount to take</strong></p></td>
<td><p>7.00</p></td>
</tr>
</tbody>
</table>


The invoice balance is now 0.00. Arnie views the information in the **Customer transactions** form.

<table>
<colgroup>
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Voucher</strong></p></th>
<th><p><strong>Transaction type</strong></p></th>
<th><p><strong>Date</strong></p></th>
<th><p><strong>Invoice</strong></p></th>
<th><p><strong>Amount in transaction currency</strong> debit</p></th>
<th><p><strong>Amount in transaction currency</strong> credit</p></th>
<th><p><strong>Balance</strong></p></th>
<th><p><strong>Currency</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>FTI-10030</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10030</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>ARP-10030</p></td>
<td><p></p></td>
<td><p>6/28/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>294.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10030</p></td>
<td><p></p></td>
<td><p>6/28/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>6.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>ARP-10031</p></td>
<td><p></p></td>
<td><p>7/8/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>693.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-1031</p></td>
<td><p></p></td>
<td><p>7/8/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>7.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## See also

[Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\))

[About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md)

[Scenario: Settle a customer payment with an invoice](scenario-settle-a-customer-payment-with-an-invoice.md)

[Scenario: Automatic settlement and prioritization](scenario-automatic-settlement-and-prioritization.md)

[Scenario: Cash discount handling for overpayments](scenario-cash-discount-handling-for-overpayments.md)

[Scenario: Settle a partial customer payment and settle the final payment in full before the discount date](scenario-settle-a-partial-customer-payment-and-settle-the-final-payment-in-full-before-the-discount-date.md)

[Scenario: Settle a partial customer payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-customer-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Use one customer payment to settle multiple invoices that span multiple discount periods](scenario-use-one-customer-payment-to-settle-multiple-invoices-that-span-multiple-discount-periods.md)

[Scenario: Settle a partial customer payment that has discounts on credit notes](scenario-settle-a-partial-customer-payment-that-has-discounts-on-credit-notes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

