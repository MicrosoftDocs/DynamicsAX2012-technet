---
title: 'Scenario: Settle a partial vendor payment before the discount date with a final payment after the discount date'
TOCTitle: 'Scenario: Settle a partial vendor payment before the discount date with a final payment after the discount date'
ms:assetid: 0691c446-4cbf-4f39-900d-4a4541502ab4
ms:mtpsurl: https://technet.microsoft.com/library/Hh580562(v=AX.60)
ms:contentKeyID: 39519038
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Scenario: Settle a partial vendor payment before the discount date with a final payment after the discount date 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fabrikam purchases goods from vendor 3057. Fabrikam receives a cash discount of 1 percent if the invoice is paid in 14 days. Invoices must be paid in 30 days. The vendor also lets Fabrikam take cash discounts on partial payments. For information about these setup parameters, see [About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md) and [Accounts receivable parameters (form)](https://technet.microsoft.com/library/aa576993\(v=ax.60\)).

## Invoice for 1,000.00 on June 25

On June 25, April enters and posts an invoice for 1,000.00 for vendor 3057. April can view this transaction in the **Vendor transactions** form. (Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select vendor 3057. On the **Action Pane**, click **Transactions**.)

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
<td><p>Inv-10020</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10020</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>-1,000.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Partial payment for 297.00 with a discount on July 2

April wants to settle 300.00 of this invoice on July 2. The payment is eligible for a discount, because Fabrikam takes discounts on partial payments. Therefore, April pays 297.00 and takes a 3.00 discount. April can create a payment journal for this payment by opening the Accounts payable **Payment journal** form. She selects a journal name, clicks **Lines**, and then enters a line for vendor 3057. April then clicks **Functions** \> **Settlement**, so that she can mark payments for settlement.

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
<td><p>Inv-10020</p></td>
<td><p>3057</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10020</p></td>
<td><p>-1,000.00</p></td>
<td><p>USD</p></td>
<td><p>-297.00</p></td>
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
<td><p>-10.00</p></td>
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
<td><p>-3.00</p></td>
</tr>
</tbody>
</table>


April posts this payment. The invoice now has a balance of 700.00. April can view this transaction in the **Vendor transactions** form. (Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select vendor 3057. On the **Action Pane**, click **Transactions**.)

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
<td><p>Inv-10020</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10020</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>-700.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10020</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p>297.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10020</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p>3.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Remaining payment on July 15: 700.00 and Use cash discount = Normal

April pays the rest of this invoice on July 15, which is after the discount period. In the **Settle open transactions** form, no discount amount is displayed in the **Estimated cash discount** field, and the value in the **Cash discount amount** field is 0.00. When April pays the remaining 700.00, no additional discount will be taken.

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
<td><p>Inv-10020</p></td>
<td><p>3057</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10020</p></td>
<td><p>-700.00</p></td>
<td><p>USD</p></td>
<td><p>-700.00</p></td>
</tr>
</tbody>
</table>


Discount information is shown at the bottom of the **Settle open transactions** form. April can see that she has already taken a 3.00 discount.

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
<td><p>-3.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash discount amount to take</strong></p></td>
<td><p>0.00</p></td>
</tr>
</tbody>
</table>


April then posts the payment. When April opens the **Vendor transactions** form, she sees that the invoice has a balance of 0.00. She also sees that there are two payments. One payment is for 297.00 and has a 3.00 discount, and the other payment is for 700.00.

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
<td><p>Inv-10020</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10020</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10020</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p>297.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10020</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p>3.00</p>
<p></p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10021</p></td>
<td><p></p></td>
<td><p>7/15/2015</p></td>
<td><p></p></td>
<td><p>700.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Remaining payment on July 15: 693.00 and Use cash discount = Always

If the vendor lets April take a discount, even though she is paying after the discount date, she can change the value in the **Use cash discount** field to **Always**. The **Calculate cash discounts for partial payments** setting is overridden, and the discount is taken. The payment amount is 693.00, and the discount is the remaining 7.00. For information about the **Use cash discount** field, see [Settle open transactions - vendor (form)](https://technet.microsoft.com/library/aa619609\(v=ax.60\)).

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
<td><p>Inv-10020</p></td>
<td><p>3057</p></td>
<td><p>6/25/2015</p></td>
<td><p>7/25/2015</p></td>
<td><p>10020</p></td>
<td><p>700.00</p></td>
<td><p></p></td>
<td><p>USD</p></td>
<td><p>-693.00</p></td>
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
<td><p>-3.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash discount amount to take</strong></p></td>
<td><p>-7.00</p></td>
</tr>
</tbody>
</table>


April then posts the payment. When April opens the **Vendor transactions** form, she sees that the invoice has a balance of 0.00. She also sees that there are two payments. One payment is for 297.00 and has a 3.00 discount, and the other payment is for 693.00 and has a 7.00 discount.

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
<td><p>Inv-10020</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10020</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10020</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p>297.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10020</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p>3.00</p>
<p></p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10021</p></td>
<td><p></p></td>
<td><p>7/15/2015</p></td>
<td><p></p></td>
<td><p>693.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10021</p></td>
<td><p></p></td>
<td><p>7/15/2015</p></td>
<td><p></p></td>
<td><p>7.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## See also

[Scenario: Settle a vendor payment with an invoice](scenario-settle-a-vendor-payment-with-an-invoice.md)

[Scenario: Settle vendor payments by using payment proposals](scenario-settle-vendor-payments-by-using-payment-proposals.md)

[Scenario: Settle a partial vendor payment and settle the final payment in full before the discount date](scenario-settle-a-partial-vendor-payment-and-settle-the-final-payment-in-full-before-the-discount-date.md)

[Scenario: Use the "Date to use to calculate discounts" field to control discount calculations for vendor payments](scenario-use-the-date-to-use-to-calculate-discounts-field-to-control-discount-calculations-for-vendor-payments.md)

[Scenario: Settle a partial vendor payment that has multiple discount periods](scenario-settle-a-partial-vendor-payment-that-has-multiple-discount-periods.md)

[Scenario: Settle a partial vendor payment that has discounts on vendor credit notes](scenario-settle-a-partial-vendor-payment-that-has-discounts-on-vendor-credit-notes.md)

[Scenario: Take a discount that is more than the calculated discount for a vendor payment](scenario-take-a-discount-that-is-more-than-the-calculated-discount-for-a-vendor-payment.md)

  


