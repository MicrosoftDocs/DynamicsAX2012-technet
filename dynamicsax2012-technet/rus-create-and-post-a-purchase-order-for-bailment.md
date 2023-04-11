---
title: (RUS) Create and post a purchase order for bailment
TOCTitle: (RUS) Create and post a purchase order for bailment
ms:assetid: c2812f01-09db-43f7-bea6-b002988d2c51
ms:mtpsurl: https://technet.microsoft.com/library/JJ711574(v=AX.60)
ms:contentKeyID: 49387898
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and post a purchase order for bailment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post a purchase order to receive items for storage. Taxes are not calculated when you create the purchase order, and the purchase invoice is not included in factures.

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click the **Updates** link, and then click **Update order lines**.

3.  In the **Updating %1** **Date of price** field, select **Prompt** to automatically update the price determination date when the value in the **Date of price** field in the purchase order is modified.

4.  Click **OK** to close the form.

5.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

6.  On the **Purchase order** tab, click **Purchase order** to create a new purchase order for bailment.
    

    > [!NOTE]
    > <P>You cannot create a purchase order for bailment for an item that has not been inventoried, or for an item that is based on a category.</P>



7.  In the **Purchase order** form, on the **Action Pane**, click **Header view**.

8.  Click the **Setup** FastTab, and then, in the **Kind of activity** field, select **Bailee**.

9.  In the **Inventory profile** field, select an inventory profile for bailment.

10. Click the **Price and discount** FastTab.

11. In the **Date of price** field, select the date on which the price for the item is determined in the trade agreement for bailment. If this field is blank, the current date is used.

12. Click the **Invoice** tab, and then click **Invoice** to open the **Posting invoice** form. Click **OK** to post the purchase order invoice for bailment.

13. In the **Vendor invoice** form, enter the required details, and then click **OK** to post the purchase order invoice for bailment. Vendor and tax transactions are not created when you post the purchase invoice for bailment.

## See also

[(RUS) Accounts payable parameters (modified form)](https://technet.microsoft.com/library/jj923609\(v=ax.60\))

[(RUS) Create and post a sales order for bailment](rus-create-and-post-a-sales-order-for-bailment.md)

  


