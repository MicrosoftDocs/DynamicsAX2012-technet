---
title: About transfer orders
TOCTitle: About transfer orders
ms:assetid: 74a3291d-fc11-42a7-ae98-ece4ce8de00f
ms:mtpsurl: https://technet.microsoft.com/library/Aa550021(v=AX.60)
ms:contentKeyID: 36687846
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- transfer orders
- manage transfer orders
audience: Application User
ms.search.region: Global
---

# About transfer orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

You use transfer orders to handle items that are in transit between warehouses within the same company, but across different geographical sites. You can manage transfer orders from the **Transfer orders** form.

## Transportation time

To automatically calculate the transportation time between the ship date and the receipt date, select a method in the **Accounts receivable parameters** form, in the **Delivery date control** field in the **Shipments** area. The method that you select becomes the default delivery date control method for new transfer orders. Enter details in the **Transport** form about the method of transportation, the shipping point and receiving point, and the number of days it takes using the various forms of transportation.


> [!NOTE]
> <P>The shipping point and the receiving point are always of the <STRONG>Warehouse</STRONG> type.</P>



## Master planning

When you firm planned transfer orders, they become transfer orders. When more than one planned transfer order between the same warehouses is firmed, the shipment date and receipt date are taken from the earliest order date and latest delivery date of all the planned transfer orders. Additionally, you can assign a planned transfer order to a transfer order before firming the planned transfer order.

## Warehouse management

If you use warehouse management, you can ship directly from the **Shipments** form and receive directly from the **Item arrival** journal:

  - **Shipments** form – Click **Inventory management** \> **Common** \> **Shipments**.

  - **Item arrival** journal – Click **Inventory management** \> **Journals** \> **Item arrival** \> **Item arrival**.

## Posting to general ledger

When items are transferred to a warehouse on a different site, the transaction results in postings to the general ledger. If the site dimension link is activated, postings to the general ledger are associated with the respective site dimension attribute value. You activate the site dimension link by using the **Dimension link** form:

  - Click **Inventory management** \> **Setup** \> **Posting** \> **Dimension link**.

For more information, see [Configure and manage financial dimension links to sites](configure-and-manage-financial-dimension-links-to-sites.md) and [Item group (form)](https://technet.microsoft.com/library/aa575515\(v=ax.60\)).

## See also

[Set up transfer order parameters](set-up-transfer-order-parameters.md)

[Update shipments and received items](update-shipments-and-received-items.md)

[Set up delivery date control](set-up-delivery-date-control.md)

  


