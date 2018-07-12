---
title: 'Scenario: Settle a partial vendor payment and settle the final payment in full before the discount date'
TOCTitle: 'Scenario: Settle a partial vendor payment and settle the final payment in full before the discount date'
ms:assetid: 99928c66-04f5-4534-9cfa-6b774668f031
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597186(v=AX.60)
ms:contentKeyID: 39519251
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Scenario: Settle a partial vendor payment and settle the final payment in full before the discount date 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fabrikam buys goods from vendor 3064. The vendor gives Fabrikam a cash discount of 1 percent if the invoice is paid in 14 days. Invoices must be paid in 30 days. The vendor also lets Fabrikam take cash discounts on partial payments. For information about these setup parameters, see [About parameters for settlements in Accounts payable](about-parameters-for-settlements-in-accounts-payable.md) and [Accounts payable parameters (form)](https://technet.microsoft.com/en-us/library/aa596348\(v=ax.60\)).

On June 25, April enters an invoice for 1,000.00 for vendor 3064.

## Vendor invoice for 1,000.00 on June 25

On June 25, April enters and posts an invoice for 1,000.00 for vendor 3064. April can view this transaction in the **Vendor transactions** form. (Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select vendor 3064. On the **Action Pane**, click **Transactions**.)

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
<th><p><strong>Amount in transaction currency</strong> debit</p></th>
<th><p><strong>Amount in transaction currency</strong> credit</p></th>
<th><p><strong>Balance</strong></p></th>
<th><p><strong>Currency</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Inv-10010</p></td>
<td><p>6/25/2015</p></td>
<td><p>10010</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>-1,000.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


In the **Vendors** form, on the **Action Pane**, April clicks the **Invoice** tab, and then clicks **Settle open transactions**. She can use the **Settle open transactions** form to view the dates and amounts of cash discounts. The due date is July 25, and a cash discount of -10.00 is available if the invoice is paid by July 9.

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
<td><p>Inv-10010</p></td>
<td><p>3064</p></td>
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
<td><p>-10.00</p></td>
</tr>
</tbody>
</table>


April clicks the **Cash discount** tab to view the discount amount.

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


## Partial payment for 500.00 is made on July 1 by using the Settle open transactions form

April can create a payment journal for this payment by opening the Accounts payable **Payment journal** form. She selects a journal name, creates a journal, and then clicks **Lines** to enter a payment. The payment journal is displayed, where April enters a line for vendor 3064. April clicks **Functions** \> **Settlement**, so that she can mark payments for settlement. April marks the invoice and changes the value in the **Amount to settle** field to -500.00. She sees that the value in the **Cash discount amount** field is -10.00 for the full invoice, and the value in the **Cash discount amount to take** field is -5.05. Therefore, April is settling -505.05 of this invoice.

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
<td><p>-500.00</p></td>
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
<td><p>-5.05</p></td>
</tr>
</tbody>
</table>


If April wanted to settle exactly half of the invoice, she would submit a payment of 495.00. To settle exactly 500.00, April would enter -495.00 in the **Amount to settle** field. This amount would include a -5.00 discount.

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
<td><p>-495.00</p></td>
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
<td><p>-5.00</p></td>
</tr>
</tbody>
</table>


April closes the **Settle open transactions** form. A payment line for 495.00 is created in the journal, and April then posts the journal. April can review the vendor transactions in the **Vendor transactions** form. In this form, she sees that the invoice has a balance of -500.00. She also sees a payment of 495.00 and a discount of 5.00.

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
<td><p>Inv-10010</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10010</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>-500.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10010</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p>495.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10010</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p>5.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Remaining amount is paid on July 8

April pays the rest of the invoice for vendor 3064 on July 8, which is in the cash discount period. April creates the payment journal on July 8 and marks the transaction for settlement. She sees that the amount to be settled is 495.00. The value in the **Estimated cash discount** field is -5.00, because the 5.00 discount was taken previously.

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
<td><p>-5.00</p></td>
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


April posts this journal and reviews the vendor transactions in the **Vendor transactions** form. The balance for the invoice is now 0.00, and April sees the two payments and the two cash discounts.

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
<td><p>Inv-10010</p></td>
<td><p>Invoice</p></td>
<td><p>6/25/2015</p></td>
<td><p>10010</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10010</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p>495.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10010</p></td>
<td><p></p></td>
<td><p>7/1/2015</p></td>
<td><p></p></td>
<td><p>5.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10011</p></td>
<td><p></p></td>
<td><p>7/8/2015</p></td>
<td><p></p></td>
<td><p>495.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10011</p></td>
<td><p></p></td>
<td><p>7/8/2015</p></td>
<td><p></p></td>
<td><p>5.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## See also

[Scenario: Settle a vendor payment with an invoice](scenario-settle-a-vendor-payment-with-an-invoice.md)

[Scenario: Settle vendor payments by using payment proposals](scenario-settle-vendor-payments-by-using-payment-proposals.md)

[Scenario: Settle a partial vendor payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-vendor-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Use the "Date to use to calculate discounts" field to control discount calculations for vendor payments](scenario-use-the-date-to-use-to-calculate-discounts-field-to-control-discount-calculations-for-vendor-payments.md)

[Scenario: Settle a partial vendor payment that has multiple discount periods](scenario-settle-a-partial-vendor-payment-that-has-multiple-discount-periods.md)

[Scenario: Settle a partial vendor payment that has discounts on vendor credit notes](scenario-settle-a-partial-vendor-payment-that-has-discounts-on-vendor-credit-notes.md)

[Scenario: Take a discount that is more than the calculated discount for a vendor payment](scenario-take-a-discount-that-is-more-than-the-calculated-discount-for-a-vendor-payment.md)

  


