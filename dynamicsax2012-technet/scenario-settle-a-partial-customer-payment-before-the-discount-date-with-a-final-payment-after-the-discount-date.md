---
title: 'Scenario: Settle a partial customer payment before the discount date with a final payment after the discount date'
TOCTitle: 'Scenario: Settle a partial customer payment before the discount date with a final payment after the discount date'
ms:assetid: de9b60bb-4530-442b-9a76-b054b3d9fd1a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh545534(v=AX.60)
ms:contentKeyID: 37832539
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Scenario: Settle a partial customer payment before the discount date with a final payment after the discount date [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fabrikam sells goods to customer 4027. Fabrikam offers a cash discount of 1 percent if the invoice is paid in 14 days. Invoices must be paid in 30 days. Fabrikam also offers cash discounts on partial payments. For information about these setup parameters, see [About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md) and [Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\)).

## Invoice for 1,000.00 on June 25

On June 25, Arnie enters and posts an invoice for 1,000.00 for customer 4027. Arnie can view this transaction in the **Customer transactions** form. (Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select customer 4027. On the **Action Pane**, click **Transactions**.)

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
<td><p>FTI-10020</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10020</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Partial payment for 297.00 with a discount on July 2

Customer 4027 wants to settle 300.00 of this invoice on July 2. The payment is eligible for a discount, because Fabrikam offers discounts on partial payments. Therefore, customer 4027 pays 297.00 and takes a 3.00 discount. Arnie can create a payment journal for this payment by opening the Accounts receivable **Payment journal** form. He selects a journal name, clicks **Lines**, and then enters a line for customer 4027. Arnie then clicks **Functions** \> **Settlement**, so that he can mark payments for settlement.

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
<th><p><strong>Amount in transaction currency</strong> debit</p></th>
<th><p><strong>Currency</strong></p></th>
<th><p><strong>Amount to settle</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>FTI-10020</p></td>
<td><p>4027</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10020</p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
<td><p>297.00</p></td>
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
<td><p>10.00</p></td>
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
<td><p>3.00</p></td>
</tr>
</tbody>
</table>


Arnie posts this payment. The invoice now has a balance of 700.00. Arnie can view this transaction in the **Customer transactions** form. (Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select customer 4027. On the **Action Pane**, click **Transactions**.)

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
<td><p>FTI-10020</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10020</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>700.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>ARP-10020</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>297.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10020</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>3.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Remaining payment for 700.00 on July 11

Customer 4027 pays the rest of this invoice on July 11, which is after the discount period. In the **Settle open transactions** form, a discount amount is not displayed in the **Estimated cash discount** field, and the value in the **Cash discount amount** field is 0.00. When customer 4027 pays the remaining 700.00, no additional discount will be taken.

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
<th><p><strong>Amount in transaction currency</strong> debit</p></th>
<th><p><strong>Currency</strong></p></th>
<th><p><strong>Amount to settle</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>FTI-10020</p></td>
<td><p>4027</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10020</p></td>
<td><p>700.00</p></td>
<td><p>USD</p></td>
<td><p>700.00</p></td>
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
<td><p>0.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Use cash discount</strong></p></td>
<td><p>Normal</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash discount taken</strong></p></td>
<td><p>3.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash discount amount to take</strong></p></td>
<td><p>0.00</p></td>
</tr>
</tbody>
</table>


If Arnie changes the value in the **Use cash discount** field to **Always**, the **Calculate cash discounts for partial payments** setting is overridden, and the discount is taken. The payment amount is 693.00, and the discount is the remaining 7.00.

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
<td><p>Always</p></td>
<td><p>FTI-10020</p></td>
<td><p>4027</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10020</p></td>
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
<td><p>7.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Use cash discount</strong></p></td>
<td><p>Always</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash discount taken</strong></p></td>
<td><p>3.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash discount amount to take</strong></p></td>
<td><p>7.00</p></td>
</tr>
</tbody>
</table>


Arnie changes the value in the **Use cash discount** field back to **Normal**, because he is not letting this customer take the remaining discount of 7.00. For information about the **Use cash discount** field, see [Settle open transactions - customer (form)](https://technet.microsoft.com/en-us/library/aa558602\(v=ax.60\)).

Arnie then posts the payment. When Arnie opens the **Customer transactions** form, he sees that the invoice has a balance of 0.00. He also sees that there are two payments. One payment is for 297.00 and has a 3.00 discount, and the other payment is for 700.00.

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
<td><p>FTI-10020</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10020</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>ARP-10020</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>297.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10020</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>3.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>ARP-10021</p></td>
<td><p></p></td>
<td><p>7/11/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>700.00</p></td>
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

[Scenario: Settle a partial customer payment that has multiple discount periods](scenario-settle-a-partial-customer-payment-that-has-multiple-discount-periods.md)

[Scenario: Use one customer payment to settle multiple invoices that span multiple discount periods](scenario-use-one-customer-payment-to-settle-multiple-invoices-that-span-multiple-discount-periods.md)

[Scenario: Settle a partial customer payment that has discounts on credit notes](scenario-settle-a-partial-customer-payment-that-has-discounts-on-credit-notes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

