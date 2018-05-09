---
title: Set up items and services for not stocked trade
TOCTitle: Set up items and services for not stocked trade
ms:assetid: 64549ce7-0333-4090-a1e6-fa17755e0fbe
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh803002(v=AX.60)
ms:contentKeyID: 44080986
ms.date: 04/24/2017
mtps_version: v=AX.60
---

# Set up items and services for not stocked trade 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you do not want to track a product in inventory, but the product must still be expensed, you can set up the product so that it is not stocked. You set up products in the **Item model groups** form in Inventory management. For more information about item model groups, see [Item model groups (form)](https://technet.microsoft.com/en-us/library/aa577092\(v=ax.60\)).


> [!NOTE]
> <P>Stocked products include items and services. A service cannot be added to stock. However, pro forma stock transactions must be generated for services that contribute to the inventory value of tangible products. For example, pro forma stock transactions must be generated if a service is used to subcontract production steps.</P>
> <P>To convert a service item to a product that is not stocked, use the <STRONG>Convert to products not stocked</STRONG> form in Product information management to open the conversion wizard. This wizard guides you through the conversion. Stocked products that have a type of <STRONG>Item</STRONG> cannot be converted to products that are not stocked.</P>



1.  Click **Inventory management** \> **Setup** \> **Inventory** \> **Item model groups**.

2.  In the **Inventory policy** field group, clear the **Stocked product** check box. A cleared check box means that the cost is always expensed, but that the product is not tracked in inventory.
    

    > [!NOTE]
    > <P>If you select the <STRONG>Stocked product</STRONG> check box, the product is tracked in inventory. Products that are tracked in inventory generate inventory transactions.</P>
    > <P>For service items, the <STRONG>Stocked product</STRONG> check box should be cleared since service items should not generate on-hand quantities.</P>
    > <P>You cannot select or clear the <STRONG>Stocked product</STRONG> check box for an item model group if products are associated with the item model group.</P>



## See also

[Key tasks: Define products](key-tasks-define-products.md)

[Key tasks: Release products](key-tasks-release-products.md)

[Convert to products not stocked (form)](https://technet.microsoft.com/en-us/library/hh802990\(v=ax.60\))

[Create an Item product model group](create-an-item-product-model-group.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

