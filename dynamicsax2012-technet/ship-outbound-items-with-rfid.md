---
title: Ship outbound items with RFID
TOCTitle: Ship outbound items with RFID
ms:assetid: 168adf27-efa3-483e-9d04-a7ccf0bb2e88
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569891(v=AX.60)
ms:contentKeyID: 36056075
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- outgoing items
- radio frequency identification
- RFID
- tag level
---

# Ship outbound items with RFID 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

Before you can use radio frequency identification (RFID) with outbound items, you must:

  - Decide which items should be tagged with radio frequency identification (RFID) tags and the level of the tagging.

  - Activate the serial number dimension in the **Tracking dimension groups** form for the dimension group.

  - Specify 1 in the **Per qty.** field in the **Number groups** form to set the receipt quantity per number to one. Tags are connected to serial numbers so the receipt quantity must be one per serial number.

<!-- end list -->

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. On the **Action Pane**, click the **Sales order** tab, and then click **Sales order** to create a sales order.
    
    The RFID tagging requirements are transferred to the sales order line, but can still be changed.

2.  Double-click the new sales order, and click **Add line** to create a sales order line.

3.  Select an item in the **Item number** field, and then click **Inventory** \> **Output order** and create an output order.

4.  Click **Inventory management** \> **Common** \> **Shipments**. Create a shipment, click **Show lines**, and then click **Add** to add the item from the output order.

5.  Select a quantity in the **Quantity** field, save the transaction, and close the form.

6.  In the **Shipment** form, click **Functions** \> **Activate picking** to activate picking for the shipment.

7.  Click **Inventory management** \> **Common** \> **Picking routes**. Select a picking route in the **Picking route** field, and then click **Start picking route**.

8.  Click **Create picking pallet** and enter the appropriate options.
    

    > [!NOTE]
    > <P>On the <STRONG>RFID</STRONG> tab in the <STRONG>Picking routes</STRONG> form, you must set the server ID and device name before you can read and write tags.</P>



9.  Click **Approve details** to complete the shipment.

## See also

[About RFID](about-rfid.md)

[Work with RFID for inbound items](work-with-rfid-for-inbound-items.md)

[Start picking routes](start-picking-routes.md)

[About shipments](about-shipments.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

