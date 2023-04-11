---
title: 'Scenario: Settle a partial vendor payment that has discounts on vendor credit notes'
TOCTitle: 'Scenario: Settle a partial vendor payment that has discounts on vendor credit notes'
ms:assetid: 28083a6a-d77c-43f0-a5b6-c8a219d94f00
ms:mtpsurl: https://technet.microsoft.com/library/Hh580592(v=AX.60)
ms:contentKeyID: 39519076
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Scenario: Settle a partial vendor payment that has discounts on vendor credit notes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fabrikam’s vendors give cash discounts on credit notes. Vendor 3050 lets Fabrikam take a cash discount of 1 percent if an invoice is paid in 14 days.

On June 29, April creates an invoice for 1,000.00 for vendor 3050. On July 2, she creates a credit note for 200.00.

In the **Vendors** form, on the **Action Pane**, April clicks the **Invoice** tab, and then clicks **Settle open transactions**. She can use the **Settle open transactions** form to mark both the credit note and the invoice for settlement. A discount of 2.00 is calculated on the credit note. Therefore, the total value of the credit note is reduced to 198.00.

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
<td><p>Inv-10070</p></td>
<td><p>3050</p></td>
<td><p>6/29/2015</p></td>
<td><p>7/29/2015</p></td>
<td><p>10070</p></td>
<td><p>-1,000.00</p></td>
<td><p>USD</p></td>
<td><p>-990.00</p></td>
</tr>
<tr class="even">
<td><p>Selected and highlighted</p></td>
<td><p>Normal</p></td>
<td><p>CR-10070</p></td>
<td><p>3050</p></td>
<td><p>7/2/2015</p></td>
<td><p>7/29/2015</p></td>
<td><p></p></td>
<td><p>200.00</p></td>
<td><p>USD</p></td>
<td><p>198.00</p></td>
</tr>
</tbody>
</table>


Discount information for the credit note is shown at the bottom of the **Settle open transactions** form.

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
<td><p>2.00</p></td>
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
<td><p>2.00</p></td>
</tr>
</tbody>
</table>


April clicks **Update**. She then reviews the completed settlement. April sees that 198.00 of the credit note was applied, and a discount of 2.00 was taken on the invoice. Therefore, the total is 200.00.

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
<td><p>Selected and highlighted</p></td>
<td><p>Normal</p></td>
<td><p>Inv-10070</p></td>
<td><p>3050</p></td>
<td><p>6/29/2015</p></td>
<td><p>7/29/2015</p></td>
<td><p>10070</p></td>
<td><p>-1,000.00</p></td>
<td><p>USD</p></td>
<td><p>-200.00</p></td>
</tr>
<tr class="even">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>CR-10070</p></td>
<td><p>3050</p></td>
<td><p>7/2/2015</p></td>
<td><p>7/29/2015</p></td>
<td><p>CR-10070</p></td>
<td><p>200.00</p></td>
<td><p>USD</p></td>
<td><p>198.00</p></td>
</tr>
</tbody>
</table>


Discount information for the invoice is shown at the bottom of the **Settle open transactions** form.

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
<td><p>-2.00</p></td>
</tr>
</tbody>
</table>


April can review the vendor transactions in the **Vendor transactions** form. (Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select a vendor. On the **Action Pane**, click **Transactions**.) In this form, April sees that the invoice has a balance of -800.00. She also sees a credit note for 198.00 and a discount of 2.00.

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
<td><p>Inv-10070</p></td>
<td><p>Invoice</p></td>
<td><p>6/29/2015</p></td>
<td><p>10070</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>-800.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>Inv-10071</p></td>
<td><p></p></td>
<td><p>7/2/2015</p></td>
<td><p>CR10071</p></td>
<td><p>200.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="odd">
<td><p>DISC-10071</p></td>
<td><p></p></td>
<td><p>7/2/2015</p></td>
<td><p></p></td>
<td><p>2.00</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>DISC-10071</p></td>
<td><p></p></td>
<td><p>7/2/2015</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>2.00</p></td>
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

[Scenario: Settle a partial vendor payment that has multiple discount periods](scenario-settle-a-partial-vendor-payment-that-has-multiple-discount-periods.md)

[Scenario: Take a discount that is more than the calculated discount for a vendor payment](scenario-take-a-discount-that-is-more-than-the-calculated-discount-for-a-vendor-payment.md)

  


