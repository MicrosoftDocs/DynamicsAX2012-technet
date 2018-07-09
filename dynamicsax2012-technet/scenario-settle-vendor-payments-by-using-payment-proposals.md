---
title: 'Scenario: Settle vendor payments by using payment proposals'
TOCTitle: 'Scenario: Settle vendor payments by using payment proposals'
ms:assetid: 2569c66a-2f90-4686-9d2f-71b9309542c8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580587(v=AX.60)
ms:contentKeyID: 39519070
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Scenario: Settle vendor payments by using payment proposals [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fabrikam purchased products from vendors 3050, 3075, and 3100. The following invoices have been entered.

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
<th><p>Vendor</p></th>
<th><p>Invoice</p></th>
<th><p>Invoice date</p></th>
<th><p>Invoice amount</p></th>
<th><p>Due date</p></th>
<th><p>Discount date</p></th>
<th><p>Discount amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>3050</p></td>
<td><p>1001</p></td>
<td><p>June 15</p></td>
<td><p>500.00</p></td>
<td><p>July 15</p></td>
<td><p>June 29</p></td>
<td><p>10.00</p></td>
</tr>
<tr class="even">
<td><p>3050</p></td>
<td><p>1002</p></td>
<td><p>June 20</p></td>
<td><p>600.00</p></td>
<td><p>July 20</p></td>
<td><p>July 4</p></td>
<td><p>12.00</p></td>
</tr>
<tr class="odd">
<td><p>3075</p></td>
<td><p>1003</p></td>
<td><p>June 15</p></td>
<td><p>250.00</p></td>
<td><p>June 29</p></td>
<td><p></p></td>
<td><p>0.00</p></td>
</tr>
<tr class="even">
<td><p>3100</p></td>
<td><p>1004</p></td>
<td><p>June 17</p></td>
<td><p>100.00</p></td>
<td><p>July 17</p></td>
<td><p>July 1</p></td>
<td><p>1.00</p></td>
</tr>
</tbody>
</table>


On July 1, April pays vendors. She uses a payment proposal to help her complete this task more efficiently.

April clicks **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. She then clicks **Payment proposal** \> **Create payment proposal**.

April uses the **Vendor payment proposal** form to define the set of invoices that will be included in the proposal.

## Option 1: By cash discount

April selects **By cash discount** as the proposal type in the **Vendor payment proposal** form. For the range of payment dates, she uses June 26 to July 10. The following invoices are included in the proposal:

  - 1001, because the discount date of June 29 is in the range of payment dates

  - 1002, because the discount date of July 4 is in the range of payment dates

  - 1004, because the discount date of July 1 is in the range of payment dates

The following invoice is not included in the proposal:

  - 1003, because the invoice does not have a discount date

## Option 2: Per due date

April selects **Per due date** as the proposal type. For the range of payment dates, she uses June 26 to July 10. The following invoice is included in the proposal:

  - 1003, because the due date of June 29 is in the range of payment dates

The following invoices are not included in the proposal:

  - 1001, because the due date of July 15 is outside the range of payment dates

  - 1002, because the due date of July 20 is outside the range of payment dates

  - 1004, because the due date of July 17 is outside the range of payment dates

## Option 3: Due date and cash discount

April selects **Due date and cash discount** as the proposal type. For the range of payment dates, she uses June 26 to July 10. The following invoices are included in the proposal:

  - 1003, because the due date of June 29 is in the range of payment dates

  - 1001, because the discount date of June 29 is in the range of payment dates

  - 1002, because the discount date of July 4 is in the range of payment dates

  - 1004, because the discount date of July 1 is in the range of payment dates

## See also

[Scenario: Settle a vendor payment with an invoice](scenario-settle-a-vendor-payment-with-an-invoice.md)

[Scenario: Settle a partial vendor payment and settle the final payment in full before the discount date](scenario-settle-a-partial-vendor-payment-and-settle-the-final-payment-in-full-before-the-discount-date.md)

[Scenario: Settle a partial vendor payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-vendor-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Use the "Date to use to calculate discounts" field to control discount calculations for vendor payments](scenario-use-the-date-to-use-to-calculate-discounts-field-to-control-discount-calculations-for-vendor-payments.md)

[Scenario: Settle a partial vendor payment that has multiple discount periods](scenario-settle-a-partial-vendor-payment-that-has-multiple-discount-periods.md)

[Scenario: Settle a partial vendor payment that has discounts on vendor credit notes](scenario-settle-a-partial-vendor-payment-that-has-discounts-on-vendor-credit-notes.md)

[Scenario: Take a discount that is more than the calculated discount for a vendor payment](scenario-take-a-discount-that-is-more-than-the-calculated-discount-for-a-vendor-payment.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

