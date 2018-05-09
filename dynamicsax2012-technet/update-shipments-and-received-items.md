---
title: Update shipments and received items
TOCTitle: Update shipments and received items
ms:assetid: 6b793682-4c33-4049-a442-2ce6f6df40b3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571185(v=AX.60)
ms:contentKeyID: 36057991
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Update shipments and received items 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

Use the **Transfer orders** form to update shipments and received items. For more information, see [About shipments](about-shipments.md).

## Update shipment

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Press CTRL+N to create the transfer order and select the **Reserve items automatically** check box on the **Setup** tab. You will be asked to complete the From warehouse and To warehouse tabs if necessary.

3.  Press CTRL+N to create a new line on the **Lines** tab and select the item.

4.  Click **Inventory** \> **Output orders**, enter a quantity, and then click **OK**.

5.  Activate the shipment.

6.  Start and complete a picking route or a pallet transport.

7.  Complete and post the shipment in the **Transfer orders** form.

## Update received items

1.  Click **Inventory management** \> **Journals** \> **Item arrival** \> **Item arrival**.

2.  In the **Location journal** form, press CTRL+N to create an arrival journal.

3.  Click the **Default values** tab, select **Transfer order receive** in the **Reference** field. Select a journal number in the **Number** field.

4.  Click **Functions** and select **Create lines** to retrieve the transfer order.

5.  Select the **Initialize quantity** check box, and click **OK**.

6.  Click **Post** to post the journal line.

7.  Start and complete the pallet transport.

8.  Open the **Transfer orders** form to update the received items. For more information, see [Receive transfer orders](receive-transfer-orders.md).

## See also

[Activate shipments](activate-shipments.md)

[Start pallet transports](start-pallet-transports.md)

[Complete pallet transports](complete-pallet-transports.md)

[Start picking routes](start-picking-routes.md)

[Complete shipments](complete-shipments.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

