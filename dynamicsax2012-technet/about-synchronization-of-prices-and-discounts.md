---
title: About synchronization of prices and discounts
TOCTitle: About synchronization of prices and discounts
ms:assetid: 4a280265-2c05-472b-929c-46a493a22f60
ms:mtpsurl: https://technet.microsoft.com/library/Aa497008(v=AX.60)
ms:contentKeyID: 36056956
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About synchronization of prices and discounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Discounts and prices are always synchronized between the intercompany sales order and the intercompany purchase order. You can also synchronize the price and discounts to and from the original sales order, so that all orders have the same prices and discounts. You do this from the **Intercompany** form that is accessed from the **General** tab on the **All customers** list page—either from **Sales and marketing** or from **Procurement and sourcing**.

The **Price and discount** field is synchronized to the intercompany sales order line. This means that by selecting the **Allow price edit** field and the **Allow discount edit** field, you have allowed a change between the intercompany sales order and the intercompany purchase order. A change to the unit price, price unit, or sales charge on the intercompany sales order determines the price on the intercompany purchase order line.

If the **Allow price edit** and **Allow discount edit** fields are enabled on the intercompany sales order or the intercompany purchase order, you can change the price or discount manually on either order. Otherwise, you cannot.

If the **Allow price edit** and **Allow discount edit** fields are not enabled on the intercompany sales order, you cannot make a manual change to the price (or charges) or discount on an intercompany sales order.

If the **Allow price edit** and **Allow discount edit** fields are not enabled on the intercompany purchase order, you cannot make a manual change to the price (or charges) or discount on an intercompany purchase order.

If the **Allow price edit** and **Allow discount edit** fields are enabled on both the intercompany purchase order and the intercompany sales order, you can make manual changes to both orders. However, this can cause a situation in which updates that are made by one person are overruled by updates that are made by another person in another company on the same order.


> [!NOTE]
> <P>If you have enabled the <STRONG>Price and discount</STRONG> field on both the intercompany purchase order and the intercompany sales order, you are not in control of the pricing.</P>



To avoid these types of conflicts, the best practice is to allow prices and discounts to be changed only on the intercompany sales order or the intercompany purchase order. This is accomplished by enabling the **Allow price edit** and **Allow discount edit** fields on either of these orders.

  


