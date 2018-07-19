---
title: 'Scenario: Settle a partial customer payment that has discounts on credit notes'
TOCTitle: 'Scenario: Settle a partial customer payment that has discounts on credit notes'
ms:assetid: 3de1a679-f764-4f7d-abdc-31c03d9b5195
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh545518(v=AX.60)
ms:contentKeyID: 37832498
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Scenario: Settle a partial customer payment that has discounts on credit notes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fabrikam allows for cash discounts on partial payments and for discounts on credit notes. For information about these setup parameters, see [About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md) and [Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\)).

## Invoice for 1,000.00 and credit note for 100.00

Customer 4035 has an invoice for 1,000.00 and credit note for 100.00. Each has a 1 percent discount if it is paid in 14 days. Arnie can view this information in the **Customer transactions** form. (Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select customer 4035. On the **Action Pane**, click **Transactions**.)

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
<td><p>FTI-10050</p></td>
<td><p>Invoice</p></td>
<td><p>6/28/2015</p></td>
<td><p>10050</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
</tr>
<tr class="even">
<td><p>CCRN-10050</p></td>
<td><p>Credit note</p></td>
<td><p>6/28/2015</p></td>
<td><p>CR-10050</p></td>
<td><p></p></td>
<td><p>100.00</p></td>
<td><p>-100.00</p></td>
<td><p>USD</p></td>
</tr>
</tbody>
</table>


## Settle a credit note with an invoice

In the **Customers** form, on the **Action Pane**, Arnie clicks the **Collect** tab, and then clicks **Settle open transactions**. He can use the **Settle open transactions** form to view the cash discount dates and amounts. He marks the two documents, and then clicks **Update** to settle the transactions. There is a discount of -1.00 on the credit note, because Fabrikam allows for discounts on credit notes.

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
<td><p>FTI-10050</p></td>
<td><p>4035</p></td>
<td><p>6/28/2015</p></td>
<td><p>7/28/2015</p></td>
<td><p>10050</p></td>
<td><p>1,000.00</p></td>
<td><p>USD</p></td>
<td><p>990.00</p></td>
</tr>
<tr class="even">
<td><p>Selected</p></td>
<td><p>Normal</p></td>
<td><p>CCRN-10050</p></td>
<td><p>4035</p></td>
<td><p>6/28/2015</p></td>
<td><p>7/28/2015</p></td>
<td><p>CR-10050</p></td>
<td><p>-100.00</p></td>
<td><p>USD</p></td>
<td><p>-99.00</p></td>
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
<td><p>-1.00</p></td>
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
<td><p>-1.00</p></td>
</tr>
</tbody>
</table>


The settlement will be 100.00, and will include a payment of 99.00 and a discount of 1.00.

## See also

[Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\))

[About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md)

[Scenario: Settle a customer payment with an invoice](scenario-settle-a-customer-payment-with-an-invoice.md)

[Scenario: Automatic settlement and prioritization](scenario-automatic-settlement-and-prioritization.md)

[Scenario: Cash discount handling for overpayments](scenario-cash-discount-handling-for-overpayments.md)

[Scenario: Settle a partial customer payment and settle the final payment in full before the discount date](scenario-settle-a-partial-customer-payment-and-settle-the-final-payment-in-full-before-the-discount-date.md)

[Scenario: Settle a partial customer payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-customer-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Settle a partial customer payment that has multiple discount periods](scenario-settle-a-partial-customer-payment-that-has-multiple-discount-periods.md)

[Scenario: Use one customer payment to settle multiple invoices that span multiple discount periods](scenario-use-one-customer-payment-to-settle-multiple-invoices-that-span-multiple-discount-periods.md)

  


