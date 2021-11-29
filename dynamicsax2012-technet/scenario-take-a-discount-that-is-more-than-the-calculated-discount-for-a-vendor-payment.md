---
title: 'Scenario: Take a discount that is more than the calculated discount for a vendor payment'
TOCTitle: 'Scenario: Take a discount that is more than the calculated discount for a vendor payment'
ms:assetid: 8ffae42a-e65c-4139-bb99-b58619e63468
ms:mtpsurl: https://technet.microsoft.com/library/Hh597172(v=AX.60)
ms:contentKeyID: 39519232
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Scenario: Take a discount that is more than the calculated discount for a vendor payment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Vendor 3051 gives Fabrikam a cash discount of 4 percent if an invoice is paid in seven days. April enters an invoice on June 29 for 1,000.00. The vendor lets April take a discount of 60.00 instead of the default discount of 40.00 that is available for this invoice. April opens the Accounts payable **Payment journal** form, and then creates a payment journal. She clicks **Lines** to open the **Settle open transactions** form, and then clicks **Functions** \> **Settlement**. She marks the invoice and changes the **Cash discount amount** field value to 60.00.

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
<td><p>Inv-10040</p></td>
<td><p>3051</p></td>
<td><p>6/29/2015</p></td>
<td><p>7/29/2015</p></td>
<td><p>10040</p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
<td><p>940.00</p></td>
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
<td><p>60.00</p></td>
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
<td><p>60.00</p></td>
</tr>
</tbody>
</table>


April posts the payment journal. The invoice is fully settled with a payment of 940.00 and a discount of 60.00.

## See also

[Scenario: Settle a vendor payment with an invoice](scenario-settle-a-vendor-payment-with-an-invoice.md)

[Scenario: Settle vendor payments by using payment proposals](scenario-settle-vendor-payments-by-using-payment-proposals.md)

[Scenario: Settle a partial vendor payment and settle the final payment in full before the discount date](scenario-settle-a-partial-vendor-payment-and-settle-the-final-payment-in-full-before-the-discount-date.md)

[Scenario: Settle a partial vendor payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-vendor-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Use the "Date to use to calculate discounts" field to control discount calculations for vendor payments](scenario-use-the-date-to-use-to-calculate-discounts-field-to-control-discount-calculations-for-vendor-payments.md)

[Scenario: Settle a partial vendor payment that has multiple discount periods](scenario-settle-a-partial-vendor-payment-that-has-multiple-discount-periods.md)

[Scenario: Settle a partial vendor payment that has discounts on vendor credit notes](scenario-settle-a-partial-vendor-payment-that-has-discounts-on-vendor-credit-notes.md)

  


