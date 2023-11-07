---
title: Correct a vendor invoice that was matched to the wrong product receipt line
TOCTitle: Correct a vendor invoice that was matched to the wrong product receipt line
ms:assetid: fd0c1913-16fd-4641-b5c6-ff57545076f0
ms:mtpsurl: https://technet.microsoft.com/library/Hh454990(v=AX.60)
ms:contentKeyID: 36993134
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
description: Learn how to correct a vendor invoice matched to the wrong product receipt line in Microsoft Dynamics AX 2012. Step-by-step guide included.
---

# Correct a vendor invoice that was matched to the wrong product receipt line 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you mistakenly invoice the wrong purchase order line, you can correct the error. First, create a credit note for the purchase order line. To create a credit note, enter a purchase order line that has a negative quantity. Then, enter the correct information for the purchase order line, and invoice the new purchase order line.

## Prerequisites

The procedures in this topic provide examples that are based on the purchase order and product receipts in the following scenario:

April, an accounts payable specialist at Fabrikam, creates purchase order PO100. This purchase order has one line, line 10, for item RM-CABLE/3. For this item, the unit conversion is 1 box = 200 each. The purchase order is for 10 boxes.

Fabrikam receives 2 boxes. Sammy, a shipping and receiving specialist, records product receipt PR01 for 2 boxes.

Fabrikam later receives 3 boxes. Sammy records product receipt PR02 for 3 boxes.

Fabrikam receives the invoice for the purchase order. April records invoice INV01, and she matches a quantity of 2 with the first product receipt, PR01, and a quantity of 1 with the second product receipt, PR02. April then posts the invoice.

April realizes that she recorded INV01 incorrectly. She matched the invoice line with both PR01 and PR02. Instead, the whole invoice line should have been matched with PR02.

## Enter a reversal line for the original purchase order line, and correct the product receipt

To correct the error, first enter a negative purchase order line, and then match this line with negative product receipts. In this example, Alicia, a purchasing agent at Fabrikam, works together with April to make the correction.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click the purchase order that contains the error. In this example, Alicia double-clicks PO100.

3.  In the **Purchase order lines** grid, click **Add line**.

4.  Enter the item number and other identifying information about the item. In this example, Alicia enters RM-CABLE/3.

5.  Enter the quantity as a negative number. In this example, Alicia enters -3.

6.  Confirm the purchase order.

7.  Record a negative product receipt to remove the posting of the original product receipt for the original purchase order line. In this example, Alicia deletes the default product receipt line that corresponds to the original purchase order line, line 10. She then enters two product receipts for the negative purchase order line, line 20. The default product receipt quantity is -3. Alicia enters PR01-1, with a purchase quantity of -2 boxes and an inventory quantity of -400 each. She then enters PR02-1, with a purchase quantity of -1 box and an inventory quantity of -200 each.

## Enter a credit note for the original purchase order line

Next, create a credit note to reverse the effect of the original invoice. By creating a credit note, you make sure that the correct cost is recorded for the returned product.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click the purchase order that contains the error. In this example, Alicia double-clicks PO100.

3.  On the **Action Pane**, click the **Invoice** tab, and then click **Invoice**.

4.  Enter an invoice number for the credit note. In this example, April enters IN01-01.

5.  Delete the positive line that corresponds to the positive purchase order line, line 10. Leave the negative line that corresponds to the negative purchase order line, line 20.

6.  On the **Action Pane**, click **Match product receipts**.

7.  In the upper pane, select the purchase order line that contains the negative quantity.

8.  In the lower pane, select the product receipts that contain the negative quantities, and then click **OK**. In this example, April selects PR01-1 and PR02-1.

9.  On the **Action Pane**, click **Invoice details**.

10. On the **Vendor invoice** tab, click **Post**, select posting settings, and then click **Post**.

## Enter the new purchase order line and product receipt

Next, enter a new purchase order line and product receipt to record the information again.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click the purchase order that contains the error. In this example, Alicia double-clicks PO100.

3.  In the **Purchase order lines** grid, click **Add line**.

4.  Enter the item number and other identifying information about the item. In this example, Alicia enters RM-CABLE/3.

5.  Enter the quantity as a positive number. In this example, Alicia enters 3.

6.  Confirm the purchase order.

7.  Record a positive product receipt to re-record the posting of the original product receipt for the original purchase order line. In this example, Alicia enters two product receipts that correspond to purchase order line 30. She enters PR01-2, with a purchase quantity of 2 boxes and an inventory quantity of 400 each. She then enters PR02-2, with a purchase quantity of 1 box and an inventory quantity of 200 each.

## Enter the new invoice

Finally, enter a new invoice, and then match this invoice to the correct product receipts.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click the purchase order that contains the error. In this example, April double-clicks PO100.

3.  On the **Action Pane**, click the **Invoice** tab, and then click **Invoice**.

4.  Enter an invoice number for the new invoice. In this example, April enters IN01-02.

5.  On the **Action Pane**, click **Match product receipts**.

6.  In the upper pane, select the original purchase order line. In this example, April selects line 10.

7.  In the lower pane, select the new positive product receipt that contains the correction quantity. In this example, April selects PR02 and enters a quantity of 2. Product receipt PR02, which has a quantity of 3, is now fully invoiced.

8.  In the upper pane, select the new purchase order line that contains the positive quantity. In this example, April selects line 30.

9.  In the lower pane, select the product receipt that contains the incorrect quantities, and then click **OK**. In this example, April selects PR02-2 and enters a quantity of 1. Purchase order line 30 is now fully matched.

10. On the **Action Pane**, click **Invoice details**.

11. Click **Post**, select posting settings, and then click **Post**.

## Summary

The following table describes the documents that are created and matched because of the corrections.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Purchase order line number</p></th>
<th><p>Quantity ordered</p></th>
<th><p>Product receipt</p></th>
<th><p>Purchase quantity received</p></th>
<th><p>Invoice</p></th>
<th><p>Invoice quantity received</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>10</p></td>
<td><p>10</p></td>
<td><p>PR01</p></td>
<td><p>2</p></td>
<td><p>INV01</p></td>
<td><p>2 (later reversed by PR01-1)</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p>PR02</p></td>
<td><p>3</p></td>
<td><p></p></td>
<td><p>1 (later corrected by PR01-2 for +2)</p></td>
</tr>
<tr class="odd">
<td><p>20</p></td>
<td><p>-3</p></td>
<td><p>PR01-1</p></td>
<td><p>-2</p></td>
<td><p>IN01-1</p></td>
<td><p>-2</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p>PR02-1</p></td>
<td><p>-1</p></td>
<td><p></p></td>
<td><p>-1</p></td>
</tr>
<tr class="odd">
<td><p>30</p></td>
<td><p>3</p></td>
<td><p>PR01-2</p></td>
<td><p>2</p></td>
<td><p>IN01-2</p></td>
<td><p>2 matched to PR02 on purchase order line 10. Therefore, the total matched quantity for PR02 is 3.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p>PR02-2</p></td>
<td><p>1</p></td>
<td><p></p></td>
<td><p>1 matched to PR02 on purchase order line 30.</p></td>
</tr>
</tbody>
</table>


## See also

[Match product receipts to invoice (form)](https://technet.microsoft.com/library/hh209552\(v=ax.60\))

[Purchase order (form)](https://technet.microsoft.com/library/aa557983\(v=ax.60\))

[Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\))

  


