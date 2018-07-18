---
title: Create a consolidated batch order
TOCTitle: Create a consolidated batch order
ms:assetid: d3e7ab59-5703-4c04-b9d7-c7af3571c2bc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh328581(v=AX.60)
ms:contentKeyID: 36688003
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a consolidated batch order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create, maintain, and view a consolidated order, which is an order that groups a bulk order with its related packed orders. To add an existing order to a consolidated order, the order status must be **Open** and the item being produced must be used in either making or consuming the same bulk item.


> [!TIP]
> <P>This procedure assumes that you have already completed the following setup tasks:</P>
> <UL>
> <LI>
> <P>Created the bulk and packed products. For more information, see <A href="add-a-batch-order-to-a-consolidated-batch-order.md">Add a batch order to a consolidated batch order</A>.</P>
> <LI>
> <P>Set up the bulk item conversion. For more information, see <A href="set-up-a-packed-item-to-bulk-item-conversion-factor.md">Set up a packed item to bulk item conversion factor</A>.</P>
> <LI>
> <P>Firmed the bulk order and packed orders using the <STRONG>Firm and Consolidate</STRONG> button in the <STRONG>Planned orders</STRONG> form. For more information, see <A href="firm-a-consolidated-batch-order.md">Firm a consolidated batch order</A>.</P></LI></UL>



1.  Click **Production control** \> **Common** \> **Consolidated batch orders**. The **Consolidated batch orders** list page is displayed.

2.  On the **Action Pane**, on the **Consolidated batch order** tab, in the **New** group, click **Consolidated batch order**. The **Consolidated batch orders** form is displayed.

3.  Add the bulk product to the consolidated batch order.
    
    1.  In the **Bulk Orders** pane, click **Functions** and select **Add to consolidated batch order**.
    
    2.  At the **Choose the consolidated batch order** prompt, select the bulk item and then click **OK**. The details for the bulk item are displayed in the **Bulk Orders** pane.
    
    3.  In the **Packed Orders** pane, click **Functions** and select **Add to consolidated batch order**.
    
    4.  At the **Choose the consolidated batch order** prompt, select the packed item and then click **OK**. The details for the packed item are displayed in the **Packed Orders** pane.

4.  When you finish adding bulk and packed items to the consolidated batch order, click **Functions** in the appropriate pane and select **Update consolidated batch order**. The header information for the consolidated batch order is updated to show the bulk item being produced and consumed and the consolidated quantity of the order.

## See also

[About consolidated batch orders](about-consolidated-batch-orders.md)

[Consolidated batch orders (list page)](https://technet.microsoft.com/en-us/library/hh328658\(v=ax.60\))

[Consolidated batch orders (form)](https://technet.microsoft.com/en-us/library/hh328731\(v=ax.60\))

  


