---
title: About quarantine orders
TOCTitle: About quarantine orders
ms:assetid: 0f2731bc-a8e1-4406-84d0-9b387e2b06ce
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496417(v=AX.60)
ms:contentKeyID: 44080945
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About quarantine orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can quarantine an item or a group of items. For example, you might want to quarantine items for quality control reasons. When you quarantine items, you can either create the quarantine orders manually or set up the system to create the quarantine orders automatically. A setup in which quarantine orders are created automatically is called quarantine management.

## Quarantine management

The following options are available for quarantine management:

  - The item is put in a quarantine warehouse when the item is registered in purchasing. For this option, the **Registration requirements** check box is selected in the **Item model groups** form for the item model group for the item.

  - The item is put in a regular warehouse or a quarantine warehouse when the purchase is updated by using a product receipt. For this option, the **Registration requirements** check box is cleared in the **Item model groups** form for the item model group for the item.

  - The item is registered in a location journal at a regular warehouse. When the journal is posted, a pallet transport is generated to move the item from the regular warehouse to the quarantine warehouse. When the pallet transport is completed, a quarantine order is generated. The pallet is then moved to a quarantine warehouse.

At registration, a quarantine order is generated. This order has a status of **Started**. The **Quarantine management** check box must be selected in the **Item model groups** form for the item model group for the item. Additionally, in the **Warehouses** form, a quarantine warehouse must be selected in the **Quarantine warehouse** field for the main warehouse that is used.

When you create quarantine orders manually, you do not have to require that the current item be set up for quarantine management in the item model group. In this case, there must be at least one quarantine warehouse. In the **Quarantine orders** form, on the **Overview** tab, you can modify the inventory dimensions. To specify which inventory dimensions appear on the **Overview** tab, click **Inventory** \> **Dimensions display**.

## Statuses for quarantine orders

Quarantine orders can have the following statuses:

  - **Created**

  - **Started**

  - **Reported as finished**

  - **Ended**


> [!NOTE]
> <P>Only quarantine orders that have a status of <STRONG>Created</STRONG> or <STRONG>Ended</STRONG> can be deleted manually by pressing ALT+F9.</P>



## Created status

When a quarantine order is created manually, but the item is not yet put in the quarantine warehouse, the quarantine order has a status of **Created**. Two inventory transactions are generated. One is a receipt transaction that has a status of **On order** at the regular warehouse. The second is an issue transaction that has a status of **Ordered** at the quarantine warehouse. You can register or reserve items by using the usual processes.

## Started status

By clicking **Start**, you can start a quarantine order that was manually created. Quarantine orders that are automatically created have a status of **Started**. The item is moved from the regular warehouse to the quarantine warehouse, and two inventory transactions are generated. One transaction has a status of **Deducted**, and the other transaction has a status of **Received**. At the same time, two inventory transactions are created to handle the return transfer. These transactions are not dated. One transaction has a status of **Reserved physical**, and the other transaction has a status of **Ordered**.

## Reported as finished status

By clicking **Report as finished**, you can report a started quarantine order as finished. The item is released from quarantine but is not yet moved back to the regular warehouse. If you are using warehouse management, you can specify an item arrival journal that is initialized with the items for the quarantine order.

## Ended status

When a quarantine order that was reported as finished is ended, the item is moved from the quarantine warehouse back to the regular warehouse. The status of the item transaction is set to **Sold** at the quarantine warehouse and **Purchased** at the regular warehouse.

## See also

[Item model groups (form)](https://technet.microsoft.com/en-us/library/aa577092\(v=ax.60\))

[Create warehouses](create-warehouses.md)

[Warehouses (form)](https://technet.microsoft.com/en-us/library/aa620570\(v=ax.60\))

[About inventory blocking](about-inventory-blocking.md)

  


