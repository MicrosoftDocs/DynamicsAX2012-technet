---
title: 'Scenario: Use the "Date to use to calculate discounts" field to control discount calculations for vendor payments'
TOCTitle: 'Scenario: Use the "Date to use to calculate discounts" field to control discount calculations for vendor payments'
ms:assetid: 8d2245f5-495c-491b-b70a-602d2fb5cbb1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597164(v=AX.60)
ms:contentKeyID: 39519221
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Scenario: Use the \"Date to use to calculate discounts\" field to control discount calculations for vendor payments [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can take a cash discount that is based on a date other than the transaction date of the payment. You can do this by using the **Date to use for calculating discounts** field in the **Settle open transactions** form. This field is available only if you open the form from a list page, or from a form that opens when you double-click a record on a list page. For more information, see [Settle open transactions - vendor (form)](https://technet.microsoft.com/en-us/library/aa619609\(v=ax.60\)).

On June 28, April creates an invoice for 2,000.00 for vendor 3052. The invoice has a cash discount of 1 percent if the invoice is paid in 14 days.

## Payment for 500.00 on July 15 and Date to use for calculating discounts = Transaction date

April creates a payment for 500.00 on July 15, which is after the discount date. April opens the **Settle open transactions** form to view the transactions that can be settled. (Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. On the **Action Pane**, click **Invoice**, and then click **Settle open transactions**.)

April marks the two transactions, and then selects the payment line. She does not see any information about cash discounts, because the cash discount is shown when the invoice line is selected.

April selects the invoice line. She now sees the information about cash discounts. The default setting for the **Date to use for calculating discounts** field is **Transaction date**. No cash discount is taken, because the payment is after the discount date.

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
<td><p>Inv-10030</p></td>
<td><p>3052</p></td>
<td><p>6/28/2015</p></td>
<td><p>7/12/2015</p></td>
<td><p>10030</p></td>
<td><p>-2,000.00</p></td>
<td><p>USD</p></td>
<td><p>-1,980.00</p></td>
</tr>
<tr class="even">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>APP-10030</p></td>
<td><p>3052</p></td>
<td><p>7/15/2015</p></td>
<td><p>7/15/2015</p></td>
<td><p></p></td>
<td><p>500.00</p></td>
<td><p>USD</p></td>
<td><p></p></td>
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
<td><p>0.00</p></td>
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
<td><p>0.00</p></td>
</tr>
</tbody>
</table>


## Payment for 500.00 on July 15 and Date to use for calculating discounts = Selected date

In the **Settle open transactions** form, April changes the value in the **Date to use for calculating discounts** field to **Selected date**. She enters a date of July 10, which is in the discount period for the invoice. That date is used to calculate a cash discount for the transaction. In the **Settle open transactions** form, April sees that, by default, the full discount of 20.00 is displayed. The invoice line shows that the amount to settle is 1,980.00.

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
<td><p>Inv-10030</p></td>
<td><p>3052</p></td>
<td><p>6/28/2015</p></td>
<td><p>7/12/2015</p></td>
<td><p>10030</p></td>
<td><p>-2,000.00</p></td>
<td><p>USD</p></td>
<td><p>-1,980.00</p></td>
</tr>
<tr class="even">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>APP-10030</p></td>
<td><p>3052</p></td>
<td><p>7/15/2015</p></td>
<td><p>7/15/2015</p></td>
<td><p></p></td>
<td><p>500.00</p></td>
<td><p>USD</p></td>
<td><p>500.00</p></td>
</tr>
</tbody>
</table>


Discount information is shown at the bottom of the **Settle open transactions** form. The discount amount to take is 20.00, because the amount to settle for the invoice is the default amount, 1,980.00.

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
<td><p>-20.00</p></td>
</tr>
</tbody>
</table>


April updates the value in the **Amount to settle** field to 500.00. The value in the **Cash discount amount to take** field is calculated as 5.05.

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
<td><p>Inv-10030</p></td>
<td><p>3052</p></td>
<td><p>6/28/2015</p></td>
<td><p>7/12/2015</p></td>
<td><p>10030</p></td>
<td><p>2,000.00</p></td>
<td><p>USD</p></td>
<td><p>-500.00</p></td>
</tr>
<tr class="even">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>APP-10030</p></td>
<td><p>3052</p></td>
<td><p>7/15/2015</p></td>
<td><p>7/15/2015</p></td>
<td><p></p></td>
<td><p>500.00</p></td>
<td><p>USD</p></td>
<td><p>500.00</p></td>
</tr>
</tbody>
</table>


Discount information is shown at the bottom of the **Settle open transactions** form. The value in the **Cash discount amount to take** field is 5.05, because the amount to settle for the invoice was changed to the payment amount, 500.00.

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
<td><p>-5.05</p></td>
</tr>
</tbody>
</table>


## See also

[Scenario: Settle a vendor payment with an invoice](scenario-settle-a-vendor-payment-with-an-invoice.md)

[Scenario: Settle vendor payments by using payment proposals](scenario-settle-vendor-payments-by-using-payment-proposals.md)

[Scenario: Settle a partial vendor payment and settle the final payment in full before the discount date](scenario-settle-a-partial-vendor-payment-and-settle-the-final-payment-in-full-before-the-discount-date.md)

[Scenario: Settle a partial vendor payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-vendor-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Settle a partial vendor payment that has multiple discount periods](scenario-settle-a-partial-vendor-payment-that-has-multiple-discount-periods.md)

[Scenario: Settle a partial vendor payment that has discounts on vendor credit notes](scenario-settle-a-partial-vendor-payment-that-has-discounts-on-vendor-credit-notes.md)

[Scenario: Take a discount that is more than the calculated discount for a vendor payment](scenario-take-a-discount-that-is-more-than-the-calculated-discount-for-a-vendor-payment.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

