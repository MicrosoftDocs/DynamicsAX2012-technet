---
title: (ESP) About using delivery dates to calculate invoice due dates
TOCTitle: (ESP) About using delivery dates to calculate invoice due dates
ms:assetid: 2d854698-d871-45e9-a9fe-098c673ac140
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923402(v=AX.60)
ms:contentKeyID: 50934002
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Spain
---

# (ESP) About using delivery dates to calculate invoice due dates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Due dates for sales invoices, purchase invoices, and project invoices are calculated based on the delivery dates or receipt dates of items and services. Private companies and public administration companies can specify the maximum number of days, known as due date limits, within which invoice payments must be made. You can specify due date limits in the **Due date limits** form. If a due date limit is specified in the **Terms of payment** and **Item groups** forms, the calculated invoice due date is checked against the effective due date limit and is adjusted, if required, to comply with it.

To use delivery dates and calculate invoice due dates for sales invoices and purchase invoices, in the **Terms of payment** form, on the **Setup** FastTab, select the **Use the delivery date to calculate the payment due date** check box. For more information, see [(ESP) Terms of payment (modified form)](https://technet.microsoft.com/en-us/library/jj910987\(v=ax.60\)).

For sales invoices, the date that is specified in the **Confirmed receipt date** field on the **Sales order header** FastTab in the **Sales order** form is used as the delivery date.

For purchase invoices, the delivery date is the date on which the packing slip is posted. If there are multiple packing slips available for a purchase invoice, the earliest packing slip posting date is used as the delivery date. If no packing slip is available, the delivery date that is specified in the **Delivery date** field on the **Purchase order header** FastTab in the **Purchase order** form is used as the delivery date for the invoice.


> [!NOTE]
> <P>The <STRONG>Confirmed receipt date</STRONG> and <STRONG>Delivery date</STRONG> values for the sales order lines and purchase order lines are not used for due date calculation.</P>



Project sales order and project purchase order delivery dates are determined in the same way as those for regular sales invoices and purchase invoices. For the **Hour**, **Expense**, **Item**, **Fee**, and **On-account** transaction types, the transaction date is used as the delivery date.

## Calculate invoice due dates for sales and purchase invoices based on delivery dates and due date limits

To use delivery dates to calculate invoice due dates, in the **Terms of payment** form, on the **Setup** tab, select the **Use the delivery date to calculate the payment due date** check box.

In this example, if the **Use the delivery date to calculate the payment due date** check box is selected, the calculated payment due date for the selected terms of payment is displayed as follows.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Terms of payment</p></th>
<th><p>Delivery date</p></th>
<th><p>Due date limit</p></th>
<th><p>Calculated invoice due date</p></th>
<th><p>Adjusted invoice due date</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Current month + 15 days</p></td>
<td><p>June 9, 2013</p></td>
<td><p>30 days</p></td>
<td><p>15 days after the end of June, which is July 15, 2013. However, July 15 – June 9 = 36 days, which is more than the actual due date limit of 30 days.</p></td>
<td><p>July 9, 2013</p></td>
</tr>
</tbody>
</table>


If there are multiple packing slips available for a purchase invoice, the earliest packing slip posting date is used as the delivery date. For example, if packing slips are posted on June 12, 2013, June 15, 2013, and June 18, 2013, for a purchase invoice, June 12, 2013, is used as the delivery date.

If more than one due date limit applies to an invoice, the due date limit with the smallest number of days is used to calculate the invoice due date. For example, if due date limits are set up for 30 days and 45 days, the effective due date limit that is used to calculate the invoice due date is 30 days, regardless of where the due date limit is set up.

## See also

[(ESP) Set up due date limits to calculate invoice due dates](esp-set-up-due-date-limits-to-calculate-invoice-due-dates.md)

  


