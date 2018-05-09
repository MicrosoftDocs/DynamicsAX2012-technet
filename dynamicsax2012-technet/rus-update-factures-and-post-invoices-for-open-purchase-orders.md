---
title: (RUS) Update factures and post invoices for open purchase orders
TOCTitle: (RUS) Update factures and post invoices for open purchase orders
ms:assetid: b0c84ded-ddc6-4327-ac23-8f18b6380455
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853217(v=AX.60)
ms:contentKeyID: 50396499
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- order
- purchase
- Russia
- RUS
- facture
---

# (RUS) Update factures and post invoices for open purchase orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can post purchase order invoices that are based on packing slips that include different types of order lines. If an invoice has not already been created for an open purchase order, the facture update can be processed and printed together with the invoice that is based on the order lines.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Create a purchase order, and then enter the required details. For more information, see [Create a purchase order](create-a-purchase-order.md).

3.  Click **Purchase** \> **Confirm** to confirm the purchase order.

4.  Click **Receive** \> **Product receipt** to post the packing slips for the purchase order.

5.  In the **Posting product receipt** form, on the **Overview** tab, in the **Product receipt** field, enter the product receipt number.

6.  On the **Lines** tab, modify the quantity that is ordered for each purchase order line in the packing slips, and then click **OK**.

7.  In the **Purchase order** form, click **Invoice** \> **Facture** to post the invoice and update the facture for the purchase order.

8.  In the **Update facture** form, on the **Vendor invoice** tab, in the **Number** and **Facture** fields, enter the invoice number and the facture number.

9.  Click **Retrieve product receipts**, and then, in the **Select product receipt** form, select the packing slips. Click **OK**.

10. In the **Update facture** form, click **Facture** \> **Post** to select the posting settings and update the facture for the packing slips that are selected. Both the invoice and facture are processed by using the specified document number and date.

## See also

[Open vendor invoices (list page)](https://technet.microsoft.com/en-us/library/hh454986\(v=ax.60\))

[Select product receipt - Purchase order (form)](https://technet.microsoft.com/en-us/library/hh597253\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

