---
title: (RUS) Create and post a sales order for bailment
TOCTitle: (RUS) Create and post a sales order for bailment
ms:assetid: b345fe7f-8012-4f9f-b2d9-1fa6f0b4f4ec
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711530(v=AX.60)
ms:contentKeyID: 49387856
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and post a sales order for bailment [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post a sales order when you return items from storage. Taxes are not calculated when you create the sales order, and the sales invoice is not included in the factures.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click the **Updates** link, and then click **Update order lines**.

3.  In the **Updating %1** **Date of price** field, select **Prompt** to automatically update the price determination date when the value in the **Date of price** field in the sales order is modified.

4.  Click **OK** to close the form.

5.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

6.  On the **Action Pane**, click **Sales order** to create a new sales order for bailment.
    

    > [!NOTE]
    > <P>You cannot create a sales order for bailment for an item that is not inventoried, or for an item that is based on a category.</P>



7.  On the **Sales order** tab, click **Header view**.

8.  Click the **Setup** FastTab, and then, in the **Kind of activity** field, select **Bailee**.

9.  In the **Inventory profile** field, select an inventory profile for bailment.

10. Click the **Price and discount** FastTab.

11. In the **Date of price** field, select the date when the price for the item is determined in the trade agreement for bailment. If this field is blank, the current date is used.

12. Click the **Invoice** tab, and then click **Invoice** to open the **Posting invoice** form.

13. Enter the required details, and then click **OK** to post the sales order invoice for bailment. Customer and tax transactions are not created for bailment when you post the sales order invoice.

## See also

[(RUS) Post sales orders](rus-post-sales-orders.md)

[(RUS) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj733272\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

