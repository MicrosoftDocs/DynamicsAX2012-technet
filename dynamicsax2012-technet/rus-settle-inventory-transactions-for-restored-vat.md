---
title: (RUS) Settle inventory transactions for restored VAT
TOCTitle: (RUS) Settle inventory transactions for restored VAT
ms:assetid: 1fc96973-800c-40e9-9d9d-aab199f20039
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711458(v=AX.60)
ms:contentKeyID: 49387275
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Settle inventory transactions for restored VAT [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to update and settle inventory transactions for restored value-added tax (VAT). When you close an inventory transaction, you must settle an item issue transaction against the receipt of an item. You must define the sales tax code for domestic trading operations in the **Sales tax codes** form for sales tax codes of the **VAT 0%** type.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Select a sales order, and then double-click it to open the **Sales order** form.

2.  Create an export facture for a sales order. For more information, see [(RUS) Create an export facture](rus-create-an-export-facture.md).

3.  On the **Sales order lines** FastTab, select an item line, and then click **Inventory** \> **Marking** to open the **Marking** form.

4.  Select the **Set mark now** check box for each sales order line to mark the inventory transactions so that receipts and issues are linked.
    

    > [!NOTE]
    > <P>You can also click <STRONG>Auto</STRONG> to select transactions according to the specified dimension set and the first in, first out (FIFO) rule.</P>



5.  Click **OK** to link receipts and issues, and then calculate restored VAT amounts.

6.  Click **Invoice**, and then, in the **Generate** action group, click **Facture** to open the **Update facture** form.

7.  Click **OK** to update the facture and post the sales invoice.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

