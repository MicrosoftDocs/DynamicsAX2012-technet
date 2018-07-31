---
title: 'Scenario: Settle a partial vendor payment that has multiple discount periods'
TOCTitle: 'Scenario: Settle a partial vendor payment that has multiple discount periods'
ms:assetid: cf724698-86ec-4f6e-b296-c407a17751f5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597247(v=AX.60)
ms:contentKeyID: 39519325
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Scenario: Settle a partial vendor payment that has multiple discount periods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Vendor 3054 offers Fabrikam a cash discount of 2 percent if an invoice is paid in five days, and a cash discount of 1 percent if an invoice is paid in 14 days.

## Invoice for 1,000.00 on June 28

On June 28, April creates an invoice for 1,000.00 for vendor 3054. April can view this transaction in the **Vendor transactions** form. (Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select vendor 3054. On the **Action Pane**, click **Transactions**.)

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
<td><p>Inv-10060</p></td>
<td><p>6/28/2015</p></td>
<td><p>10060</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>-1,000.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


The following cash discount dates and amounts are available for this invoice.

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
<td><p>7/3/2015</p></td>
<td><p>20.00</p></td>
<td><p>980.00</p></td>
</tr>
<tr class="even">
<td><p>7/12/2015</p></td>
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


## Payment for 294.00 on July 2

On July 2, April creates a payment of 300.00 for this invoice. Because this payment is made in the first discount period, a discount of 2 percent is taken. April can create a payment journal for this payment by opening the Accounts payable **Payment journal** form. She selects a journal name, creates a journal, and then clicks **Lines** to enter a payment. The payment journal is displayed, where April enters a line for vendor 3054. April then clicks **Functions** \> **Settlement**, so that she can mark the invoice that will be settled. She updates the value in the **Amount to settle** field to 300.00, and she sees that the value in the **Cash discount amount to take** field is changed to 6.12.

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
<td><p>Inv-10060</p></td>
<td><p>3054</p></td>
<td><p>6/28/2015</p></td>
<td><p>7/28/2015</p></td>
<td><p>10060</p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
<td><p>300.00</p></td>
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
<td><p>7/02/2015</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash discount amount</strong></p></td>
<td><p>-20.00</p></td>
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
<td><p>-6.12</p></td>
</tr>
</tbody>
</table>


April wants to settle a total of 300.00. She changes the value in the **Amount to settle** field to 294.00, and she sees that the value in the **Cash discount amount to take** field is changed to 6.00.

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
<td><p>Inv-10060</p></td>
<td><p>3054</p></td>
<td><p>6/28/2015</p></td>
<td><p>7/28/2015</p></td>
<td><p>10060</p></td>
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
<td><p>7/02/2015</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash discount amount</strong></p></td>
<td><p>-20.00</p></td>
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
<td><p>-6.00</p></td>
</tr>
</tbody>
</table>


April posts the payment. In the **Vendor transactions** form, she can view the transactions. She sees that 300.00 has been applied to the invoice. This amount includes a discount of 6.00. Therefore, the remaining balance is 700.00.

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
<td><p>Inv-10060</p></td>
<td><p>6/28/2015</p></td>
<td><p>10060</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>-700.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10060</p></td>
<td><p>7/2/2015</p></td>
<td><p></p></td>
<td><p>294.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10060</p></td>
<td><p>7/2/2015</p></td>
<td><p></p></td>
<td><p>6.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Payment for 495.00 on July 8

April applies 500.00 to the invoice for a payment that is made on July 8. In the **Settle open transactions** form, April clicks the **Cash discount** tab. She sees the dates and amounts for the two cash discounts that are available. Because this payment is made in the second discount period, a discount of 1 percent, or 5.00, is taken. This amount is calculated as half of the 1 percent discount on 1,000.00, or half of 10.00.

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
<td><p>7/3/2015</p></td>
<td><p>20.00</p></td>
<td><p>680.00</p></td>
</tr>
<tr class="even">
<td><p>7/12/2015</p></td>
<td><p>10.00</p></td>
<td><p>690.00</p></td>
</tr>
<tr class="odd">
<td><p>7/25/2015</p></td>
<td><p>0.00</p></td>
<td><p>700.00</p></td>
</tr>
</tbody>
</table>


April settles the payment as follows.

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
<td><p>Inv-10060</p></td>
<td><p>3054</p></td>
<td><p>6/28/2015</p></td>
<td><p>7/28/2015</p></td>
<td><p>10060</p></td>
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
<td><p>7/12/2015</p></td>
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
<td><p>-6.00</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash discount amount to take</strong></p></td>
<td><p>-5.00</p></td>
</tr>
</tbody>
</table>


In the **Vendor transactions** form, April sees that the new balance is 200.00.

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
<td><p>Inv-10060</p></td>
<td><p>6/28/2015</p></td>
<td><p>10060</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>-200.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10060</p></td>
<td><p>7/2/2015</p></td>
<td><p></p></td>
<td><p>294.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10060</p></td>
<td><p>7/2/2015</p></td>
<td><p></p></td>
<td><p>6.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10061</p></td>
<td><p>7/12/2015</p></td>
<td><p></p></td>
<td><p>495.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10061</p></td>
<td><p>7/12/2015</p></td>
<td><p></p></td>
<td><p>5.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Payment for 200.00 on July 20

April creates a final payment on July 20. No discount is taken, because the payment is made after both discount periods. The balance for the invoice is 0.00.

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
<td><p>Inv-10060</p></td>
<td><p>6/28/2015</p></td>
<td><p>10060</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>-200.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10060</p></td>
<td><p>7/2/2015</p></td>
<td><p></p></td>
<td><p>294.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10060</p></td>
<td><p>7/2/2015</p></td>
<td><p></p></td>
<td><p>6.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10061</p></td>
<td><p>7/12/2015</p></td>
<td><p></p></td>
<td><p>495.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10061</p></td>
<td><p>7/12/2015</p></td>
<td><p></p></td>
<td><p>5.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>APP-10062</p></td>
<td><p>7/20/2015</p></td>
<td><p></p></td>
<td><p>200.00</p></td>
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

[Scenario: Settle a partial vendor payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-vendor-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Use the "Date to use to calculate discounts" field to control discount calculations for vendor payments](scenario-use-the-date-to-use-to-calculate-discounts-field-to-control-discount-calculations-for-vendor-payments.md)

[Scenario: Settle a partial vendor payment that has discounts on vendor credit notes](scenario-settle-a-partial-vendor-payment-that-has-discounts-on-vendor-credit-notes.md)

[Scenario: Take a discount that is more than the calculated discount for a vendor payment](scenario-take-a-discount-that-is-more-than-the-calculated-discount-for-a-vendor-payment.md)

  


