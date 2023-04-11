---
title: Create and post a purchase order for a potency item
TOCTitle: Create and post a purchase order for a potency item
ms:assetid: 0e57e6c4-0bff-46e4-b0e8-957c37a568e6
ms:mtpsurl: https://technet.microsoft.com/library/JJ838721(v=AX.60)
ms:contentKeyID: 50120604
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create and post a purchase order for a potency item 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the information in this topic to create, process, and post a purchase order for a potency item. The posted invoice provides the detailed adjusted unit price and net amount that is adjusted and calculated based on the actual potency of the received inventory batch material. Before you can create and post a purchase order for a potency item, you must complete the following tasks:

1.  Assign batch attributes to a potency item. For more information, see [Assign batch attributes to a potency item](assign-batch-attributes-to-a-potency-item.md).

2.  Add batch attribute values to an inventory batch for potency items. For more information, see [Add batch attribute values to an inventory batch for potency items](add-batch-attribute-values-to-an-inventory-batch-for-potency-items.md).

3.  Set up an attribute-based pricing formula for a potency item. For more information, see [Set up an attribute-based pricing formula for a potency item](set-up-an-attribute-based-pricing-formula-for-a-potency-item.md).

4.  Create a purchase trade agreement and add attribute-based pricing details to it. For more information, see [Update a trade agreement with new commodity pricing](update-a-trade-agreement-with-new-commodity-pricing.md) and [Trade agreements (form)](https://technet.microsoft.com/library/aa499393\(v=ax.60\)).

## Process a purchase order for a potency item

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, click **New** \> **Purchase order**, or double-click a purchase order. For more information, see [(PM) Purchase order (form)](https://technet.microsoft.com/library/hh328589\(v=ax.60\)) and [Create a purchase order](create-a-purchase-order.md).

2.  Select or create a purchase order line.

3.  Click the **Line details** FastTab, and then click the **Price and discount** tab.

4.  In the **Attribute-based pricing ID** field, verify the attribute-based pricing ID for specified potency item.
    

    > [!NOTE]
    > <P>The adjusted unit price and adjusted net amount are not calculated because the receipt and pricing calculations based on the received potency are not completed.</P>



5.  On the **Purchase** tab, click **Confirm** to confirm the purchase order.

6.  Post the purchase order. For more information, see Process a purchase order.

## See also

[Attribute-based pricing data (form)](https://technet.microsoft.com/library/jj838766\(v=ax.60\))

  


