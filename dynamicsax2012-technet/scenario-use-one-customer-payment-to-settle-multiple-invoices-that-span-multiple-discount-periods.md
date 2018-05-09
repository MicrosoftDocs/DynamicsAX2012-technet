---
title: 'Scenario: Use one customer payment to settle multiple invoices that span multiple discount periods'
TOCTitle: 'Scenario: Use one customer payment to settle multiple invoices that span multiple discount periods'
ms:assetid: 2c04c15c-6355-4f4b-b7fb-9a73c547b232
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh545517(v=AX.60)
ms:contentKeyID: 37832497
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Scenario: Use one customer payment to settle multiple invoices that span multiple discount periods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fabrikam sells goods to customer 4032. Fabrikam offers a cash discount of 1 percent if the invoice is paid in 14 days, and also offers cash discounts on partial payments. For information about these setup parameters, see [About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md) and [Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\)).

## Three invoices that have a total balance of 3,000.00

Customer 4032 has three invoices:

  - Invoice FTI-10040, for 1,000.00, was entered on May 15. This invoice is eligible for a cash discount of 1 percent if it is paid in 14 days.

  - Invoice FTI-10041, for 1,000.00, was entered on June 25. This invoice is eligible for a cash discount of 1 percent if it is paid in 14 days.

  - Invoice FTI-10042, for 1,000.00, was entered on June 25. This invoice is eligible for a cash discount of 2 percent if it is paid in five days, and 1 percent if it is paid in 14 days.

## Settle all invoices on June 29 with a total payment of 2,970.00

If Arnie creates a payment journal to fully settle these invoices on June 29, the payment would be 2,970.00. The total of all discount amounts would be 30.00.

Arnie opens the Accounts receivable **Payment journal** form. He creates a journal, and then clicks **Lines**. In the **Account** field, he selects customer 4032, and then clicks **Functions** \> **Settlement**. In the **Settle open transactions** form, Arnie selects the **Mark** check box for all three invoice lines.

  - The payment for invoice FTI-10040 would be 1,000.00, with no cash discount.

  - The payment for invoice FTI-10041 would be 990.00, with a cash discount of 1 percent, or 10.00.

  - The payment for invoice FTI-10042 would be 980.00, with a cash discount of 2 percent, or 20.00.

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
<td><p>FTI-10040</p></td>
<td><p>4032</p></td>
<td><p>5/15/2015</p></td>
<td><p>6/15/2015</p></td>
<td><p>10040</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>USD</p></td>
<td><p>1,000.00</p></td>
</tr>
<tr class="even">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>FTI-10041</p></td>
<td><p>4032</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10041</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>USD</p></td>
<td><p>990.00</p></td>
</tr>
<tr class="odd">
<td><p>Selected and highlighted</p></td>
<td><p>Normal</p></td>
<td><p>FTI-10042</p></td>
<td><p>4032</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10042</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>USD</p></td>
<td><p>980.00</p></td>
</tr>
</tbody>
</table>


Discount information for invoice FTI-10042 is shown at the bottom of the **Settle open transactions** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Cash discount date</strong></p></td>
<td><p>7/4/2015</p></td>
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
<td><p>20.00</p></td>
</tr>
</tbody>
</table>


The customer balance is 0.00.

## Settle all invoices on July 1 with a total payment of 2,980.00

If Arnie creates a payment journal to fully settle these invoices on July 1, the payment would be 2,980.00.

Arnie opens the Accounts receivable **Payment journal** form. He creates a journal, and then clicks **Lines**. In the **Account** field, he selects customer 4032, and then clicks **Functions** \> **Settlement**. He selects the **Mark** check box for all three invoice lines.

  - The payment for invoice FTI-10040 would be 1,000.00, with no cash discount.

  - The payment for invoice FTI-10041 would be 990.00, with a cash discount of 1 percent, or 10.00.

  - The payment for invoice FTI-10042 would be 990.00, with a cash discount of 1 percent, or 10.00. Although July 1 is after the period for the 2 percent discount, it is still in the period for the 1 percent discount.

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
<td><p>FTI-10040</p></td>
<td><p>4032</p></td>
<td><p>5/15/2015</p></td>
<td><p>6/15/2015</p></td>
<td><p>10040</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>USD</p></td>
<td><p>1,000.00</p></td>
</tr>
<tr class="even">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>FTI-10041</p></td>
<td><p>4032</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10041</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>USD</p></td>
<td><p>990.00</p></td>
</tr>
<tr class="odd">
<td><p>Selected and highlighted</p></td>
<td><p>Normal</p></td>
<td><p>FTI-10042</p></td>
<td><p>4032</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10042</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>USD</p></td>
<td><p>990.00</p></td>
</tr>
</tbody>
</table>


Discount information for invoice FTI-10042 is shown at the bottom of the **Settle open transactions** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Cash discount date</strong></p></td>
<td><p>7/13/2015</p></td>
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


## Partial settlement on June 29 with a total payment of 1,485.00

Customer 4032 can pay a partial amount, such as half of each invoice.

Arnie opens the Accounts receivable **Payment journal** form. He creates a journal, and then clicks **Lines**. He enters the payment date, and then clicks **Functions** \> **Settlement**, so that he can mark payments for settlement. On each line, he enters the amount to settle. When a line is selected, Arnie sees the discount amount for that line and the discount amount that is taken. Because the customer is paying half of the invoice, Arnie sees that the value in the **Cash discount amount** field for FTI-10042 is 20.00, but the value in the **Cash discount taken** field is 10.00. The payment amount is 1,485.00.

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
<td><p>FTI-10040</p></td>
<td><p>4032</p></td>
<td><p>5/15/2015</p></td>
<td><p>6/15/2015</p></td>
<td><p>10040</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>USD</p></td>
<td><p>500.00</p></td>
</tr>
<tr class="even">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>FTI-10041</p></td>
<td><p>4032</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10041</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>USD</p></td>
<td><p>495.00</p></td>
</tr>
<tr class="odd">
<td><p>Selected and highlighted</p></td>
<td><p>Normal</p></td>
<td><p>FTI-10042</p></td>
<td><p>4032</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10042</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>USD</p></td>
<td><p>490.00</p></td>
</tr>
</tbody>
</table>


Discount information for invoice FTI-10042 is shown at the bottom of the **Settle open transactions** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Cash discount date</strong></p></td>
<td><p>7/4/2015</p></td>
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
<td><p>10.00</p></td>
</tr>
</tbody>
</table>


If Arnie manually creates a payment journal for 1,485.00, clicks **Functions** \> **Settlement**, and then marks all three transactions, and Arnie does not adjust the value in the **Amount to settle** field for each transaction when he closes the form, the following message will be displayed:

**The total amount of marked transactions is different from the journal amount. Change journal amount?**

If Arnie wants the payment amount to be only 1,485.00, he clicks **No**, and then posts the journal. The transactions are settled as follows:

  - Invoice FTI-10040 is fully settled for 1,000.00, because it was entered on May 15, and it is the oldest invoice. No cash discount is taken. The remaining amount on the payment transaction is 485.00.

  - Invoice FTI-10041 is not settled at all. Invoices FTI-10041 and FTI-10042 were entered on the same date. However, a 1 percent discount is available to invoice FTI-10041, and a 2 percent discount is available to invoice FTI-10042. Because a better discount is available to invoice FTI-10042, the remaining 485.00 is settled with invoice FTI-10042.

  - Invoice FTI-10042 is settled with the remaining 485.00. Fabrikam offers partial discounts. Because the invoice had a 2 percent discount, the customer pays 98 percent of the invoice. The discount is 9.90 (485.00 / 0.98 \* 0.02). The amount is divided by 0.98, because there is a 2 percent discount, so that the customer pays 98 percent of the invoice. The result is then multiplied by the discount percentage, or 2 percent. The payment of 485.00 plus the discount of 9.90 is 494.90. The amount of the original invoice was 1,000.00. Therefore the transaction has a balance of 505.10, which is 1,000.00 – 494.90.
    
    Arnie views the information in the **Customer transactions** form.

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
<td><p>FTI-10040</p></td>
<td><p>Invoice</p></td>
<td><p>5/15/2015</p></td>
<td><p>10040</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>FTI-10041</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10041</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>FTI-10042</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10042</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>505.10</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>ARP-10040</p></td>
<td><p></p></td>
<td><p>6/29/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>1,485.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10040</p></td>
<td><p></p></td>
<td><p>6/29/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>9.90</p></td>
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

[Scenario: Settle a partial customer payment that has multiple discount periods](scenario-settle-a-partial-customer-payment-that-has-multiple-discount-periods.md)

[Scenario: Settle a partial customer payment that has discounts on credit notes](scenario-settle-a-partial-customer-payment-that-has-discounts-on-credit-notes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

