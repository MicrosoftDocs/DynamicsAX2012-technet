---
title: Trace inventory settlement transactions
TOCTitle: Trace inventory settlement transactions
ms:assetid: 68eed109-25e8-4893-99e5-148f577133f7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231574(v=AX.60)
ms:contentKeyID: 36057960
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Trace inventory settlement transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Inventory close creates settlements that match issues to receipts. Microsoft Dynamics AX provides you with two means to trace how a transaction was settled, and what other transaction it was settled to. These two means are the Cost explorer and the transaction drillback process.

## Cost explorer

Use the **Cost explorer** form to trace the origin of cost prices through a tree structure view of issues and receipts.


> [!NOTE]
> <P>You must run the inventory close process before you can use the tree structure. This is because the tree structure uses the inventory settlements that occurred during the inventory close process to display cost price dependencies.</P>



1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Manage inventory** tab, click **Transactions** to open the **Inventory transactions** form.

3.  In the **Inventory transactions** form, click **Inventory** \> **Cost explorer**.

You can expand the nodes of the tree structure to see how cost prices are calculated. The cost price of a node is the total of the cost prices of the underlying nodes.

Examples of expanded views of node:

  - Expand a sales order line to view the settled receipts.

  - Expand a production order to view all the transactions that are included in the cost price of the production order. This could be bill of material (BOM) items, a route consumption, or adjustments.

  - Expand a transfer receipt to view the transfer issues.

## Transaction drillback

After inventory close is complete, you can view the transactions that were settled to each other during the process.

For example, you have the following purchase orders:

  - Purchase order number PO123 was entered for a quantity of 1 at a cost of USD 10.00.

  - Purchase order number PO456 was entered for a quantity of 1 at a cost of USD 15.00.

When the sales order number SO987 was posted, the cost amount of the sales order was USD 12.50. This is running average for this item at the time that the issue transaction was posted.

Assume that the FIFO inventory model was assigned to this item. When inventory close is run, sales order SO987 will be settled to purchase order PO123.

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**.

2.  In the **Closing and adjustment** form, click the **Settlements** button to open the **Settlements for voucher** form.

3.  Select a transaction on the **Overview** tab.

4.  Click the **Transaction** button to open the **Settlements in the transaction** form, where you can view the settled transaction and identify which issue was settled to which receipt.

## See also

[Cost explorer (form)](https://technet.microsoft.com/en-us/library/aa600945\(v=ax.60\))

[Settlements in the transaction (form)](https://technet.microsoft.com/en-us/library/aa571469\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

