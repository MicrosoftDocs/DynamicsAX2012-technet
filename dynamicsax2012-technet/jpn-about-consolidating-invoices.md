---
title: (JPN) About consolidating invoices
TOCTitle: (JPN) About consolidating invoices
ms:assetid: 8aa3b0dd-33ca-4a6a-ad1e-e488b5616909
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711087(v=AX.60)
ms:contentKeyID: 49386499
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- JP - 00007
audience: Application User
ms.search.region: Japan
---

# (JPN) About consolidating invoices 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can consolidate several vendor invoices, purchase orders, purchase returns, and purchase journals into a consolidated vendor invoice for payment instead of issuing payments for the separate vendor transactions. You can also consolidate customer invoices, sales orders, sales returns, and sales journals into a customer consolidated invoice that you can send to the customer.

You can create two or more consolidated invoices on the same day for a customer or for a vendor. After you create a consolidated invoice for a customer or for a vendor, you can pay the vendor or receive payment from the customer and settle the consolidated invoice for the amount of the payment.

The following calculations are performed for a consolidated invoice:

  - Invoice amount

  - Due date

## Calculating the invoice amount for a consolidated invoice

After you create and confirm a consolidated invoice in the **Consolidated invoice** form, the following amounts are calculated:

  - **Previous invoice amount** – The total invoice amount for the previous consolidation period.

  - **Previously paid amount** – The total amount paid for the previous consolidation period.

  - **Adjustment amount** – The adjustment amount for the previous consolidation period. The adjustment amount includes cash discounts and bank charges.

  - **Outstanding amount** – The total outstanding amount for the current consolidation period. The outstanding amount is calculated by using the following formula:
    
    Previous invoice amount – Paid amount – Adjustment amount

  - **Invoice amount during consolidation period** – The total invoice amount in the current consolidated invoice. This amount includes the sales tax.

  - **Total invoice amount** – The new total invoice amount for the current invoice. This amount is calculated by using the following formula:
    
    Outstanding amount + Invoice amount during consolidation period

## Calculating the due date for a consolidated invoice

Invoices are consolidated each month, based on the consolidation day that you specify for each vendor or customer. This consolidation day determines the day and period for which invoices are consolidated, and the date that payment is due.

If the last day of the month falls on a date that is earlier than the consolidation day that you specify, the invoices are consolidated on the last business day of the month. If you specify 31 for the consolidation day, and the current month has fewer than 31 days, the invoices are consolidated on the last business day of that month. For example, the invoices for June 2012 are consolidated on June 29, 2012, because that is the last business day of the month.

The following table shows how the payment due date is calculated for invoices that are generated on different days. The consolidation day is 10, and the payment date is the end of the month.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Invoice number</p></th>
<th><p>Invoice date</p></th>
<th><p>Consolidation day</p></th>
<th><p>Due date</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>INV001</strong></p></td>
<td><p>May 04, 2012</p></td>
<td><p>May 10, 2012</p></td>
<td><p>June 29, 2012</p></td>
</tr>
<tr class="even">
<td><p><strong>INV002</strong></p></td>
<td><p>May 10, 2012</p></td>
<td><p>May 10, 2012</p></td>
<td><p>June 29, 2012</p></td>
</tr>
<tr class="odd">
<td><p><strong>INV003</strong></p></td>
<td><p>May 18, 2012</p></td>
<td><p>June 10, 2012</p></td>
<td><p>July 31, 2012</p></td>
</tr>
<tr class="even">
<td><p><strong>INV004</strong></p></td>
<td><p>June 08, 2012</p></td>
<td><p>June 10, 2012</p></td>
<td><p>July 31, 2012</p></td>
</tr>
</tbody>
</table>


## See also

[(JPN) Set up a consolidated invoice for a customer](jpn-set-up-a-consolidated-invoice-for-a-customer.md)

[(JPN) Set up the terms of payment and the cutoff day for a customer](jpn-set-up-the-terms-of-payment-and-the-cutoff-day-for-a-customer.md)

[(JPN) Create, confirm, reopen, and print a consolidated customer invoice](jpn-create-confirm-reopen-and-print-a-consolidated-customer-invoice.md)

[(JPN) Mark sales invoices for consolidation and calculate due dates](jpn-mark-sales-invoices-for-consolidation-and-calculate-due-dates.md)

[(JPN) Settle customer consolidated invoices by using a payment journal](jpn-settle-customer-consolidated-invoices-by-using-a-payment-journal.md)

[(JPN) Settle customer consolidated invoices by using a payment proposal](jpn-settle-customer-consolidated-invoices-by-using-a-payment-proposal.md)

[(JPN) Set up a consolidated invoice for a vendor](jpn-set-up-a-consolidated-invoice-for-a-vendor.md)

[(JPN) Set up the terms of payment and the cutoff day for a vendor](jpn-set-up-the-terms-of-payment-and-the-cutoff-day-for-a-vendor.md)

[(JPN) Create, confirm, reopen, and print a consolidated vendor invoice](jpn-create-confirm-reopen-and-print-a-consolidated-vendor-invoice.md)

[(JPN) Mark purchase invoices for consolidation and calculate due dates](jpn-mark-purchase-invoices-for-consolidation-and-calculate-due-dates.md)

[(JPN) Settle vendor consolidated invoices by using a payment journal](jpn-settle-vendor-consolidated-invoices-by-using-a-payment-journal.md)

[(JPN) Settle vendor consolidated invoices by using a payment proposal](jpn-settle-vendor-consolidated-invoices-by-using-a-payment-proposal.md)

[Key tasks: Letter of credit or import collection for the import of items](key-tasks-letter-of-credit-or-import-collection-for-the-import-of-items.md)

[Key tasks: Letter of credit for the export of goods](key-tasks-letter-of-credit-for-the-export-of-goods.md)

  


