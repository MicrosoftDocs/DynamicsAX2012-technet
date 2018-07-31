---
title: 'Scenario: Settle a partial customer payment and settle the final payment in full before the discount date'
TOCTitle: 'Scenario: Settle a partial customer payment and settle the final payment in full before the discount date'
ms:assetid: 9d434af1-8628-4188-b957-146deda27be9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh545526(v=AX.60)
ms:contentKeyID: 37832518
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Scenario: Settle a partial customer payment and settle the final payment in full before the discount date 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fabrikam sells goods to customer 4028. Fabrikam offers a cash discount of 1 percent if the invoice is paid in 14 days. Invoices must be paid in 30 days. Fabrikam also offers cash discounts on partial payments. For information about these setup parameters, see [About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md) and [Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\)).

## Customer invoice for 1,000.00 on June 25

On June 25, Arnie enters and posts an invoice for 1,000.00 for customer 4028. Arnie can view this transaction in the **Customer transactions** form. (Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select customer 4028. On the **Action Pane**, click **Transactions**.)

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
<td><p>FTI-10010</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10010</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


In the **Customers** form, on the **Action Pane**, Arnie clicks the **Collect** tab, and then clicks **Settle open transactions**. He can use the **Settle open transactions** form to view the dates and amounts of cash discounts. The due date is July 25, and a cash discount of 10.00 is available if the invoice is paid by July 9.

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
<td><p></p></td>
<td><p>Normal</p></td>
<td><p>FTI-10010</p></td>
<td><p>4028</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10010</p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
<td><p>990.00</p></td>
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
<td><p>10.00</p></td>
</tr>
</tbody>
</table>


Arnie clicks the **Cash discount** tab to view the discount amount.

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
<td><p>7/9/2015</p></td>
<td><p>10.00</p></td>
<td><p>990.00</p></td>
</tr>
<tr class="even">
<td><p>7/25/2015</p></td>
<td><p>0.00</p></td>
<td><p>1,000.00</p></td>
</tr>
</tbody>
</table>


## Partial payment of 500.00 on July 1 by using the Enter customer payments form

Customer 4028 wants to settle half of this invoice, or 500.00, on July 1. Arnie can create a payment journal for this payment by opening the Accounts receivable **Payment journal** form. He selects a journal name, creates a journal, and then clicks **Enter customer payments**. He enters the payment information and marks the invoice that he entered. When Arnie enters 500.00 for the amount, he also enters 500.00 in the **Amount to pay** field in the grid. He sees that a discount of 5.05 can be taken. The calculation for this discount is 500.00 / 0.99 \* 0.01 = 5.05.

500.00 is divided by 0.99, because there is a 1 percent discount, so that the customer is paying 99 percent of the invoice. The result is then multiplied by the discount percentage, which is 1 percent, or 0.01. If the customer took the full discount of 10.00, the amount to settle would be 990.00.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Amount</strong></p></td>
<td><p>500.00</p></td>
</tr>
<tr class="even">
<td><p><strong>Settled</strong></p></td>
<td><p>500.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Remaining</strong></p></td>
<td><p>0.00</p></td>
</tr>
</tbody>
</table>


Discount information is shown in the grid at the bottom of the **Enter customer payments** form.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Cash discount amount to take</strong></p></th>
<th><p><strong>Cash discount taken</strong></p></th>
<th><p><strong>Amount to pay</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>5.05</p></td>
<td><p>0.00</p></td>
<td><p>500.00</p></td>
</tr>
</tbody>
</table>


If the customer wants to settle 500.00, or the payment plus the discount, the customer would submit a payment of 495.00. A discount of 5.00 would be calculated for a total of 500.00. To settle exactly half of the invoice, or 500.00, Arnie would enter 495.00, or 500.00 minus the 5.00 discount.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Amount</strong></p></td>
<td><p>495.00</p></td>
</tr>
<tr class="even">
<td><p><strong>Settled</strong></p></td>
<td><p>495.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Remaining</strong></p></td>
<td><p>0.00</p></td>
</tr>
</tbody>
</table>


Discount information is shown in the grid at the bottom of the **Enter customer payments** form.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Cash discount amount to take</strong></p></th>
<th><p><strong>Cash discount taken</strong></p></th>
<th><p><strong>Amount to pay</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>5.00</p></td>
<td><p>0.00</p></td>
<td><p>495.00</p></td>
</tr>
</tbody>
</table>


Arnie clicks **Save in journal**. The transaction is saved in the payment journal.

## Partial payment for 500.00 on July 1 by using the Settle open transactions form

Instead of clicking **Enter customer payments** in the payment journal, Arnie can click **Lines** to enter a payment. The payment journal is displayed, where Arnie can enter a line for customer 4028. Arnie clicks **Functions** \> **Settlement**, so that he can mark payments for settlement. Arnie marks the invoice and changes the value in the **Amount to settle** field to 500.00. Again, he sees that the value in the **Cash discount amount** field is 10.00 for the full invoice, and the value in the **Cash discount amount to take** field is 5.05. Therefore, Arnie is settling 505.05 of this invoice.

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
<td><p>FTI-10010</p></td>
<td><p>4028</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10010</p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
<td><p>500.00</p></td>
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
<td><p>5.05</p></td>
</tr>
</tbody>
</table>


If the customer wants to settle exactly half of the invoice, the customer would submit a payment of 495.00. To settle exactly 500.00, Arnie would enter 495.00 in the **Amount to settle** field. This amount would include a 5.00 discount.

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
<td><p>FTI-10010</p></td>
<td><p>4028</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10010</p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
<td><p>495.00</p></td>
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
<td><p>5.00</p></td>
</tr>
</tbody>
</table>


Arnie closes the **Settle open transactions** form. A payment line for 495.00 is created in the journal, and Arnie then posts the journal. Arnie can review the customer transactions in the **Customer transactions** form. In this form, he sees that the invoice has a balance of 500.00. He also sees a payment of 495.00 and a discount of 5.00.

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
<td><p>FTI-10010</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10010</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>500.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>ARP-10010</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>495.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10010</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>5.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Remaining amount is paid on July 8

Customer 4028 pays the rest of this invoice on July 8, which is in the cash discount period. Arnie creates the payment journal on July 8 and marks the transaction for settlement. He sees that the amount to be settled is 495.00. The value in the **Estimated cash discount** field is 5.00, because the 5.00 discount was taken previously.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Marked total</strong></p></td>
<td><p>495.00</p></td>
</tr>
<tr class="even">
<td><p><strong>Estimated cash discount</strong></p></td>
<td><p>5.00</p></td>
</tr>
</tbody>
</table>


Information about the marked transaction is shown in the grid in the **Settle open transactions** form.

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
<td><p>FTI-10010</p></td>
<td><p>4028</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10010</p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
<td><p>495.00</p></td>
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
<td><p>5.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash discount amount to take</strong></p></td>
<td><p>5.00</p></td>
</tr>
</tbody>
</table>


Arnie posts this journal and reviews the customer transactions in the **Customer transactions** form. The balance for the invoice is now 0.00, and Arnie sees the two payments and the two cash discounts.

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
<td><p>FTI-10010</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10010</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>ARP-10010</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>495.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10010</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>5.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>ARP-10011</p></td>
<td><p></p></td>
<td><p>7/8/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>495.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10011</p></td>
<td><p></p></td>
<td><p>7/8/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>5.00</p></td>
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

[Scenario: Settle a partial customer payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-customer-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Settle a partial customer payment that has multiple discount periods](scenario-settle-a-partial-customer-payment-that-has-multiple-discount-periods.md)

[Scenario: Use one customer payment to settle multiple invoices that span multiple discount periods](scenario-use-one-customer-payment-to-settle-multiple-invoices-that-span-multiple-discount-periods.md)

[Scenario: Settle a partial customer payment that has discounts on credit notes](scenario-settle-a-partial-customer-payment-that-has-discounts-on-credit-notes.md)

  


